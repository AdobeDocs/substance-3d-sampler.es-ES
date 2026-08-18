---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-3-4.html"
breadcrumb-title: ''
description: Consulte las notas de la versión 3.4 de Substance 3D Sampler para obtener más información sobre las nuevas funciones diseñadas para aumentar la velocidad y la calidad en los flujos de trabajo 3D.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.4
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 3.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '838'
ht-degree: 0%

---


# Versión 3.4

**Substance 3D Sampler 3.4.0** presenta una serie de nuevas características diseñadas para aumentar la velocidad y la calidad de los flujos de trabajo 3D.

*Fecha de publicación: 6 de septiembre de 2022*

## Funciones principales

## Parámetros expuestos

Modifique materiales paramétricos dentro de cualquier software que admita archivos SBSAR, como CLO, UE5, Blender, Photoshop y Illustrator, entre otros.\
Esto es ahora posible gracias a la nueva capacidad de Sampler de exponer parámetros de recursos, lo que le permite acelerar las iteraciones y deshacerse de las idas y venidas entre Sampler y otros software.

Expone los parámetros de tu material con solo hacer clic en una chincheta.

Los puntos de color le ayudarán a navegar por los parámetros expuestos y los diferentes paneles.

## Creación de Python

Ahora puede crear complementos y secuencias de comandos, lo que le permite personalizar su interfaz, lo que facilita la integración de Sampler en su canalización y configurar el flujo de trabajo general, de la forma que desee.\
Esto podría permitirle, por ejemplo, crear un script que le permita automatizar tareas repetitivas como exportar varios materiales en un solo clic.

Descubre cómo crear tu primer script o complemento [aquí](../scripting-and-development/scripting-and-development.md).

## Propiedades físicas de CLO

Ahora puede crear textiles que se comporten de forma realista con simulaciones físicas. Esto se consigue introduciendo propiedades físicas del tejido, como la curvatura, la distorsión y la fricción.\
Con esta actualización, el SBSAR contendrá la información física en sus metadatos, que son utilizados por CLO para garantizar que el material reaccione de manera realista.

## De imagen a material (con tecnología de IA)

Imagen a material (con tecnología de IA) ya está disponible en MacOS y se ejecuta de forma nativa en dispositivos con Apple Silicon.

## Notas de la versión

### 3.4.0 Arancini

*(Fecha de publicación: 6 de septiembre de 2022)*

**Agregado:**

[Parámetros expuestos] Nuevo Panel Parámetros expuestos\
[Parámetros expuestos] Botón Nuevo en los parámetros al pasar el ratón para exponer y desexponer parámetros en el panel Propiedades\
[Parámetros expuestos] Nuevo menú contextual que se muestra al hacer clic con el botón derecho en los parámetros para exponer y desexponer parámetros en el panel Propiedades\
[Parámetros expuestos] Los parámetros expuestos se enumeran en el Panel Parámetros expuestos\
[Parámetros expuestos] Se añaden puntos de color y discos de color en varios lugares para identificar fácilmente los parámetros expuestos\
[Parámetros expuestos] Las etiquetas de parámetros se pueden editar en el Panel Parámetros expuestos\
[Parámetros expuestos] Mostrar una advertencia para los parámetros no exportables\
[Parámetros expuestos] Se muestra una advertencia al mover una capa con parámetros de mezcla expuestos a un lugar en el que se ocultan\
[Parámetros expuestos] Los parámetros expuestos se exportan en formatos SBS y SBSAR\
[Metadatos] Compatibilidad con plantillas de metadatos personalizadas\
[Metadatos] Nueva plantilla de metadatos de propiedades físicas de CLO\
[Metadatos] Añadir iconos al pasar el ratón para añadir o quitar metadatos personalizados\
[API de Python] Nueva API de Python\
[API de Python] API para creación de activos\
[API de Python] API para la administración de capas\
[API de Python] API para la administración de parámetros\
[API de Python] API para la administración de proyectos\
[API de Python] Se puede activar y desactivar un complemento.\
[API de Python] Se puede acceder a la documentación de la API de Python en el menú Ayuda\
[Scripts] Nueva sección de scripts y complementos en el menú emergente Preferencias\
[Scripts] Cree e importe complementos para personalizar la interfaz de Sampler con sus propios paneles\
[Scripting] Los complementos pasan a formar parte de la interfaz de Sampler y se pueden acoplar y mover como paneles estándar de Sampler\
[Scripting] Barra de botones dedicada para los complementos en la barra de herramientas derecha de Sampler\
[Scripting] Crear e importar scripts para realizar una lista de tareas determinadas\
[Scripts] Iniciar scripts de Python a través del menú Scripts\
[Scripts] Los complementos y scripts se pueden eliminar, reordenar y volver a cargar desde la ventana Preferencias\
[Scripting] Se han añadido parámetros de línea de comandos —run-script\
[Registros] Nuevo panel Registros\
[Registros] Active el panel Registros desde la ventana Preferencias\
[Registros] Nueva barra de acciones para borrar, copiar y pegar registros de exportación\
[Propiedades] Botón nuevo en los parámetros que se colocan sobre el cursor para restablecer el valor del parámetro\
[Propiedades] Nuevo menú contextual que se muestra al hacer clic con el botón derecho en los parámetros para restablecer el valor del parámetro\
[Contenido] Imagen a material (con tecnología de IA) ahora funciona en MacOS\
[Motor] Actualice el motor del Substance a la versión 8.6.0

**Corregido:**

[Aplicación] La aplicación se podía bloquear al salir cuando estaba en curso una generación de miniaturas\
[Aplicación] La aplicación puede bloquearse al utilizar Guardar como al salir\
[Aplicación] La aplicación se puede bloquear durante el apagado en MacOS\
[Aplicación] Al guardar con el cuadro de diálogo de color abierto, no se guardan los cambios\
[Exportar] La convención de nomenclatura de uso no es correcta al exportar\
[Capas] Si se suelta un material encima de un filtro, es posible que se bloquee\
[Capas] Si se actualiza una pila de capas obsoleta, es posible que se actualicen pilas de capas no relacionadas\
[Metadatos] Se exportan los campos vacíos\
[Metadatos] Cuando solo hay un elemento de metadatos, la interfaz de usuario le permite intentar reordenarlo\
[Proyecto] El cálculo nunca termina después de duplicar un material\
[Project] El recurso del proyecto se duplica después de guardar el proyecto inicial\
[Project] Cálculos innecesarios al cambiar de recurso\
[Procesamiento] Algunas pilas de capas no se procesan correctamente después de eliminar una capa\
[Security] Solucione CVE-2015-20107\
[UI] Las salidas 2D pueden ser borrosas dependiendo del tamaño de la ventana\
[UI] La vista previa de activos puede permanecer abierta en la parte superior cuando la aplicación pierde el enfoque\
[UI] Las esquinas redondeadas de la pantalla de bienvenida tienen un fondo cuadrado opaco

**Problemas conocidos:**

[Selector de color] Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente\
[Contenido] El widget de luz de forma no funciona en modo de proyección esférica\
[Interoperabilidad] El material con desplazamiento enviado a Stager perderá los controles de desplazamiento
