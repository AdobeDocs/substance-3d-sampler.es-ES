---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/scripting-and-development/create-a-plugin-with-python-and-qml.html"
breadcrumb-title: ''
description: Aprenda a crear complementos con Python y QML para Substance 3D Sampler para crear interfaces de usuario personalizadas y ampliar la funcionalidad.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Plugin with Python and QML
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Crear un complemento con Python y QML
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '729'
ht-degree: 0%

---


# Crear un complemento con Python y QML

Esta guía describe cómo crear un plugin de autoguardado simple con Python y QML.

## Estructura del complemento

Los complementos de Sampler requieren al menos un archivo Python y QML para poder importarse, pero también se pueden incluir otros archivos, como imágenes utilizadas para iconos en el panel de complementos. En el ejemplo siguiente, hay 3 archivos:

* **autosave.py** contiene la lógica del complemento y determina cómo funciona.
* **autosave.qml** define el aspecto del complemento en Sampler.
* **autosave.svg** es un gráfico vectorial que se utiliza como icono del complemento.

Una vez que tenga los archivos necesarios para el complemento en una sola carpeta, puede añadirlo a Sampler a través de Editar > Preferencias > Complementos y scripts. Para obtener más información sobre la administración de complementos, haz clic [aquí](manage-installed-plugins-and-scripts.md).

## Python

El siguiente código es el archivo python completo del complemento de autoguardado. A continuación se muestra una breve descripción de lo que está haciendo el código, pero el código también incluye comentarios con más información:

1. Importar los módulos correspondientes.
   1. Qt es un conjunto de herramientas GUI multiplataforma. QtcCore, QtQml y QtQuick son módulos que utilizamos para comunicarnos entre autosave.py y autosave.qml.
1. Defina un método **save()** que guarde el proyecto cada X minutos.
1. Cree una clase de autoguardado. Esta clase especifica cómo se conecta el método **save()** a la interfaz de usuario del complemento para que los parámetros puedan cambiar el comportamiento del complemento
1. Defina un método **register\_qml\_type()** que realice la configuración del complemento.
1. Llame al complemento desde Sampler.

### autosave.py

```
## Import QT & QML modules to create the UI

from PySide2 import QtCore, QtQml, QtQuick 

## Import Sampler API

import substance_sampler as ssa 

## Import other modules for this specific example

import datetime 

import os 

import threading 

 

 

## Save the project every X minutes

def save(interval): 

    global t 

    ssa.save_project() 

    if ssa.save_project(): 

        now = datetime.datetime.now() 

        print("Autosave: %d:%d:%d" % (now.hour, now.minute, now.second)) 

    t = threading.Timer(interval, save, [interval]) 

    t.start() 

 

 

t = None 

 

 

## Declare the API AutoSave

class AutoSave(QtQuick.QQuickItem): 

    def __init__(self, parent=None): 

        super(AutoSave, self).__init__(parent) 

 

## Declare a first API function

## This function can be called from the QML file

## with 2 arguments, one string and one integer

    @QtCore.Slot(str, int) 

    def start_auto_save(self, default_path, interval): 

        if not ssa.save_project(): 

            ssa.save_project_as(os.path.join(default_path, "autosave.ssa")) 

        global t 

        t = threading.Timer(10, save, [interval]) 

        t.start() 

        print("Launch Autosave") 

 

## Second function of the API

## With no argument

    @QtCore.Slot(None) 

    def stop_auto_save(self): 

        global t 

        t.cancel() 

        print("Stop Autosave") 

 

 

## Function to declare the API and the panel

## First argument is Python class of your API

## Second argument is name of the API you will use in the QML file

## Third and fourth is the API version. In this case, 1.0

## Last is the name of the panel in Sampler UI

def register_qml_type(): 

    QtQml.qmlRegisterType(AutoSave, "AutoSave", 1, 0, "AutoSave") 

 

 

## Execute the plugin in Sampler UI thread

ssa.run_in_main_thread(register_qml_type)
```


## QML

El archivo QML define la interfaz de usuario del complemento. QML significa Qt Markup Language (Lenguaje de marcado Qt) y se comporta de forma similar a otros lenguajes de marcado como HTML y XML. Puede [obtener más información sobre QML aquí](https://doc.qt.io/qt-6/qmlapplications.html#:~:text=QML%20is%20a%20user%20interface%20specification%20and%20programming,imperative%20JavaScript%20expressions%20combined%20with%20dynamic%20property%20bindings.).

La estructura general de autosave.qml es la siguiente:

1. Importa módulos.
   1. Los módulos Qt importados son necesarios para los elementos de la interfaz de usuario utilizados en el fichero.
   1. También se importa la clase de API de guardado automático creada en **autosave.py**. El archivo QML hace referencia a esta clase en la línea 20.
1. Cree variables que deban ser objeto de seguimiento.
   1. **autoSaveFolder** es la carpeta en la que se guardará automáticamente el archivo de Sampler.
   1. **intervalo** es la cantidad de tiempo en segundos entre autoguardados.
   1. Se utiliza **textColor** para que el color del texto en la interfaz de usuario del complemento se pueda actualizar en un solo lugar.
1. Creación de instancias de la API Python
1. Defina la IU.
   1. Esto incluye enlaces a la API python creada en **autosave.py**. Por ejemplo:
      1. La línea 47 actualiza el valor de la variable **timing** en el archivo QML cada vez que se cambia el elemento &quot;Autosave each (min):&quot;.
      1. La línea 64 llama a la función **start\_auto\_save** desde la API y pasa las variables **timing** y **autoSaveFolder** como parámetros.
1. Cree un método para limpiar la ruta de archivo predeterminada.

### autosave.qml

```
/* 

Import Qt modules to design the UI 

https://doc.qt.io/qt-5/qtqml-syntax-basics.html 

*/ 

import QtQuick 2.15 

import QtQuick.Controls 2.15 

import Qt.labs.platform 1.1 

import AutoSave 1.0 // Import API defined in the Python file 

 

Rectangle { 

  id: root 

  anchors.fill: parent 

  color: "#333333" 

 

  property var autoSaveFolder: removeQmlFilePathPrefix(StandardPaths.writableLocation(StandardPaths.DocumentsLocation)) 

  property var timing: 300 

  property var textColor: "#b3b3b3" 

 

  AutoSave { 

      id: api // Instantiate the Python API 

  } 

 

  Column { 

    id: controls 

    anchors.top: parent.top + 10 

    anchors.left: parent.left + 10 

    anchors.right: parent.right 

    width: parent.width 

    spacing: 20 

    leftPadding: 10 

    topPadding: 10 

 

    Column { 

        spacing: 5 

        Text { 

            id: timingTitle 

            text: "Autosave every (min): " 

            color: root.textColor 

        } 

        SpinBox { 

            id: timingControl 

            from: 1 

            to: 10 

            stepSize: 1 

            value: 5 

 

            onValueModified: ()=>{ 

                root.timing = timingControl.value * 60 

            } 

        } 

    } 

    Row { 

        Text { 

            text: "Off" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

        Switch { 

            id: toggle 

            checked: false 

 

            onClicked: ()=>{ 

                if (checked === true) { 

                    api.start_auto_save(root.autoSaveFolder, root.timing) // Call a function of the API with 2 arguments 

                } 

                else if (checked === false) { 

                    api.stop_auto_save() // Call a function of the API 

                } 

            } 

        } 

        Text { 

            text: "On" 

            color: root.textColor 

            anchors.verticalCenter: toggle.verticalCenter 

        } 

 

    } 

    Column { 

        spacing: 5 

        Text { 

            text: "Default Autosave Path" 

            color: root.textColor 

            } 

        Row { 

            id: folderInput 

            TextField { 

                id: folderText 

                text: root.autoSaveFolder 

                readOnly: true 

            } 

            Button { 

                id: folderSelection 

                text: qsTr("...") 

                width: 40 

                onClicked: ()=>{ 

                    folderDialog.open() 

                    } 

            } 

        } 

    } 

 

    FolderDialog { 

        id: folderDialog 

 

        onAccepted: ()=>{ 

            root.autoSaveFolder = removeQmlFilePathPrefix(folderDialog.currentFolder) 

        } 

    } 

 

  } 

      function qmlFilePathPrefix() { 

        if (Qt.platform.os === "windows") { 

            return "file:///" 

        } 

        return "file://" 

    } 

    function removeQmlFilePathPrefix(filePath) { 

        var prefix = qmlFilePathPrefix() 

        return filePath.toString().replace(prefix, '') 

    } 

}
```


## SVG

Es posible que hayas notado que **autosave.svg** no se llama explícitamente ni se menciona en **autosave.py** o **autosave.qml**. Esto se debe a que Sampler busca un archivo de SVG con el mismo nombre que el archivo PY y lo utiliza automáticamente como icono del complemento.

>[!NOTE]
>
> Si la carpeta del complemento contiene un SVG con un nombre de archivo que no coincide con el archivo PY del complemento, este no incluirá ningún icono. Esto puede dar la impresión de que el complemento no ha aparecido en la interfaz de usuario de Sampler. Si este es el caso, mueva el cursor sobre la barra derecha de Sampler para resaltar el complemento.
> 
> El navegador no admite el elemento de vídeo HTML5

Si la carpeta del complemento no contiene un archivo de SVG, se utilizará en su lugar un icono de complemento predeterminado.

A continuación se muestra un ejemplo de SVG que puede utilizar para el complemento de guardado automático creado anteriormente.

[autosave.svg](https://helpx.adobe.com/content/dam/help/en/substance-3d/documentation/sadoc/files/234455541/234455542/1/1662460696349/autosave.svg)

## Limitaciones del complemento de autoguardado

El complemento de autoguardado creado anteriormente es funcional, pero no es perfecto. Por ejemplo, ajustar el intervalo de autoguardado después de habilitar autoguardado no cambiará el tiempo entre autoguardado: deberá deshabilitar y volver a habilitar autoguardado para que el valor de la interfaz de usuario se envíe a la API.

Si es nuevo en el trabajo conjunto con Python y QML, corregir este error es una forma útil de entender cómo las diferentes partes del plugin se comunican entre sí.
