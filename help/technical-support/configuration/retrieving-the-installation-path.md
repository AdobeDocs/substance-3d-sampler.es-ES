---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/configuration/retrieving-the-installation-path.html"
breadcrumb-title: ''
description: Obtenga información sobre cómo recuperar la ruta de instalación de Substance 3D Sampler en diferentes plataformas con fines de secuencias de comandos y configuración.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > Retrieving the installation path
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Recuperación de la ruta de instalación
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 5%

---


# Recuperación de la ruta de instalación

Esta página reagrupa información sobre las formas de recuperar la ruta de instalación de la aplicación en función de la versión y la plataforma.

## Windows

### Escritorio de Creative Cloud

1. Abra el Editor del Registro de Windows (**regedit**).
1. Vaya a la clave del registro: **&#x200B; HKEY\_LOCAL\_MACHINE\Software\Microsoft\Windows\CurrentVersion\App Rutas\**
1. Abra la subclave denominada **Adobe Substance 3D Sampler.exe**
1. El valor de la clave contiene la ruta de acceso al ejecutable de la aplicación donde está instalada

>[!NOTE]
>
> Esta clave del Registro sólo está disponible desde la versión 3.\
> Para versiones anteriores, la ruta de instalación se puede recuperar de las asociaciones de archivos en **HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\ Explorer\FileExts**.

### Substance 3D independiente

1. Abra el Editor del Registro de Windows (**regedit**).
1. Vaya a la clave del registro: **HKEY\_LOCAL\_MACHINE\ SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall**
1. Busque la subclave que coincida con el ID de aplicación de la versión de la aplicación (consulte la tabla siguiente)
1. El valor de la clave contiene la ruta de la ubicación de instalación de la aplicación

| Versión | AppId |
| --- | --- |
| De **1.x (2019.x) a 2.x** | {B3506E85-E98F-4D48-A010-BE4DEE27D108} |
| **3.x (o posterior)** | {ED4A4ABC-9B7D-44B8-984A-C8A994B69CFD} |

### Vapor

La aplicación se instala en la subcarpeta **steamapps/common/** de la carpeta de instalación de Steam.

## Mac

En Mac, la aplicación se instala de la siguiente manera:

| Versión | Ruta |
| --- | --- |
| **3.x o posterior** | **/Applications/Adobe Substance 3D Sampler.app** |
| **Heredado** | **/Applications/Substance Alchemist.app** |

## Linux

En Linux, el paquete rpm se instala en la siguiente ruta:

| Versión | Ruta |
| --- | --- |
| **3.x o posterior** | **/opc/Adobe/Adobe\_Substance\_3D\_Sampler** |
| **Heredado** | **/opc/Allegorithmic/Substance\_Alchemist** |
