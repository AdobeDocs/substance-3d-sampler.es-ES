---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/interface/panels/share-panel.html"
breadcrumb-title: ''
description: Aprenda a utilizar el panel Exportar de Substance 3D Sampler para exportar materiales como archivos o enviarlos directamente a otras aplicaciones.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Export panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Panel Exportar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '487'
ht-degree: 3%

---


# Panel Exportar

En el <b>panel Exportar</b>, puedes exportar tus activos como archivos generales o enviar activos directamente a otras aplicaciones.

## Enviar a...

Las opciones Enviar a... le permiten enviar directamente el contenido a otras aplicaciones instaladas en el sistema. Esto suele ser mucho más rápido que importar y exportar recursos.

Actualmente, Sampler admite el envío a:

* **Substance 3D Painter**: importa materiales y entornos que puedas usar al aplicar texturas a tus activos.
* **Substance 3D Stager**: importa luces de ambiente para cambiar el estado de ánimo de la escena. Solo disponible con luces de ambiente, desactivado para materiales.

Los materiales siempre se envían como SBSAR, los entornos como EXR.

## Exportar

Haga clic en **Exportar como...** para exportar el activo en el que estás trabajando actualmente. Seleccione si desea modificar la configuración General o la configuración de Material en el menú de la izquierda.

### Configuración general

Con la opción Configuración general seleccionada, puede cambiar el nombre del material y la ubicación de almacenamiento. También puede alternar la creación de una subcarpeta para el material. Esto puede resultar útil al exportar en un formato de imagen que cree varios archivos.

### Configuración de materiales

Con la configuración de Material seleccionada, puede cambiar varios parámetros para controlar cómo se exportará el material:

| Configuración | Descripción |
| --- | --- |
| Formato | Elija si desea exportar como SBS, SBSAR o como una colección de imágenes en un formato de imagen específico |
| Ajuste preestablecido | Seleccione un ajuste preestablecido para organizar automáticamente la exportación para una aplicación específica. [Aquí tienes disponible más información sobre los ajustes preestablecidos](../../getting-started/export/default-presets/default-presets.md). Los ajustes preestablecidos solo están disponibles cuando se selecciona un formato de imagen. |
| Compresión | Elija si la compresión prioriza la velocidad o la eficiencia <br> <ul> <li> **Automático**: Permitir que Sampler elija. <li> **Mejores**: Maximiza la eficacia de compresión para archivos más pequeños. <li> **Ninguno**: Sin compresión, los archivos exportados se abren y cierran con mayor rapidez, pero el tamaño de los archivos es mayor. </ul> |
| Resolución | Cambie la resolución de la exportación. Esta opción aparece de forma diferente según el formato seleccionado <br> <ul> <li> **SBSAR/SBS**: Seleccione una anchura y un height por defecto para el material. Se pueden actualizar más adelante. <li> **Formato de imagen**: Seleccione entre **Salida de capas**, que exporta cada mapa con el tamaño definido por la pila de capas, o **Anular todo**, que le permite especificar un ancho y un height para la exportación. |
| Modelo de material | Seleccione si desea exportar como material estándar de Adobe o como material de OpenPBR. La opción que seleccione dependerá de las demás aplicaciones que utilice en la canalización. Diferentes canales estarán disponibles en función del Modelo de material. |
| Canales | Alterne los canales que se deben exportar como parte del activo. |

>[!NOTE]
>
> Para obtener más información sobre las opciones del cuadro de diálogo Exportar y otra información, como los formatos de archivo, consulta el [artículo de exportación](../../getting-started/export/export.md) y su [subartículo sobre la ventana de exportación](../../getting-started/export/export-window/export-window.md).

Cuando estés satisfecho con la configuración de exportación, haz clic en **Exportar**. La exportación aparecerá en la cola de exportación, que muestra una lista de las exportaciones recientes. Haga clic en el icono de carpeta de cualquier exportación para abrir la ubicación del archivo de dicha exportación.
