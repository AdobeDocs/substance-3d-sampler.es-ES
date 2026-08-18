---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/3d-capture/editing-3d-captured-meshes.html"
breadcrumb-title: ''
description: Aprenda a editar mallas capturadas en 3D en Substance 3D Sampler para perfeccionar la geometría, corregir problemas y optimizar la calidad de la malla.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Edición de mallas capturadas en 3D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '806'
ht-degree: 0%

---


# Edición de mallas capturadas en 3D

>[!WARNING]
>
> La compatibilidad con captura 3D se ha eliminado a partir de la versión 5.1 de Sampler.

## Edición de mallas capturadas en 3D

En esta guía del usuario, repasaremos algunas técnicas para editar y posprocesar objetos capturados en 3D en Substance 3D Sampler.

¿Prefiere ver esto como un tutorial de vídeo? Puedes encontrarlo [aquí.](https://youtu.be/6_EZEAR0Uy8?si=6AaCUHD6nnWZyKUE "Tutorial de vídeo sobre el captura 3D avanzada: postprocesamiento en malla")

![](../assets/post-processing-3d-capture.png)

Una vez que haya terminado el proceso de Captura 3D y agregado una malla a su proyecto de Sampler, puede hacer modificaciones en él. Pueden ser cambios en la malla o en el material. Los filtros de malla son nuevos desde Sampler 4.0. Los filtros de material utilizan todos los filtros conocidos que ya existían en Sampler.

Cuando editas un objeto 3D capturado en Sampler, <b>puedes apilar filtros de malla y de material de forma mixta</b>, estos se aplican automáticamente a la parte correcta de tus datos. La lista de filtros rápidos no distingue entre los dos tipos.

## Filtros de malla

Veamos primero los filtros de malla. Hay dos en Sampler: <b>transformación de malla</b> y <b>proceso posterior de malla</b>.

<b>Transformación de malla</b> es un filtro sencillo que te permite <b>traducir</b>, <b>rotar</b> y <b>escalar</b> tu malla. Por lo general, puede voltear un objeto o ajustar su escala. Cualquier digitalización incluye una transformación preaplicada.

<b>El proceso posterior de malla</b> es el mismo que el paso posterior al procesamiento al final del cuadro de diálogo de Captura 3D, pero en un filtro dinámico. Te permite <b>remesh</b>, <b>re-uv</b> y <b>rehacer</b> tus texturas. El objetivo de este filtro es <b>optimizar las mallas reduciendo el tricount, mejorando las UV y reduciendo la textura</b>. Uno de los mejores resultados de su uso, es el diseño UV mejorado. Por defecto, las salidas de Captura 3D originales tienen UV muy fragmentados, por lo general las nuevas UV automáticas son una mejora.

No es un filtro rápido, cada vez que se cambia un parámetro, se procesa la malla. Lo mejor es ser un poco paciente con ello.

## Filtros de material

Los filtros de materiales son mucho más diversos; cualquier cosa que se pueda usar en materiales normales se puede usar en el material de la malla del captura 3D, pero tenga en cuenta que los resultados podrían no funcionar siempre, ya que muchos filtros están pensados para materiales uniformes de mosaico.

Los filtros más útiles suelen ser los ajustes como <b>contraste</b> brillante, <b>saturación del tono</b>, así como algunos de los filtros más avanzados para editar canales. Como no pudimos capturar la rugosidad de nuestro objeto, usaremos algunos filtros para recuperarlo.

Puedes usar un <b>filtro de saturación del tono</b> para obtener aún más los colores que coinciden con los reales de tu objeto. Hay mejores formas de obtener precisión de color, pero están mucho más involucradas que este filtro rápido.

A continuación, es posible que desee recuperar los reflejos que existían en el objeto. Podemos usar el filtro <b>Reemplazo de color</b> aquí. Reemplazar color le permite seleccionar un color de la textura y cambiar todas las áreas con ese color.

De forma predeterminada, colorea todo el color que hayas seleccionado, pero si activas <b>Segmentación avanzada</b>, luego lo configuras en <b>Máscara desde color base</b> y <b>Reemplazar</b> en <b>Rugosidad</b>, puedes hacer que toda la rugosidad del área del color seleccionado sea mucho más brillante. Jugar con la variación de luminosidad y el rango de máscara puede ayudar a perfeccionar la máscara.

Por último, quizá te interese devolver un poco de detalle del color base a la rugosidad. El <b>filtro de cambio de canal</b> me permite mezclar y fusionar detalles entre diferentes canales. Puedes establecer la <b>entrada en Basecolo</b>r, la <b>salida en Roughness</b> y jugar con el modo de fusión y la opacidad para obtener algo interesante y lo suficientemente cerca de la vida real.

Por último, si desea tener más control sobre la rugosidad final, puede utilizar un filtro Contraste de brillo y configurarlo para que afecte al canal de rugosidad. A continuación, se ajustan los valores para que la rugosidad sea un poco más crujiente.

Cada objeto es diferente y, según el conjunto de datos, pueden ser necesarios ajustes específicos. Incluso puedes usar la <b>herramienta Tampón de clonar</b> para borrar partes de la textura que quieras eliminar, como capturar marcadores de ayuda. Solo ten en cuenta que cualquier filtro de material que utilice ubicaciones específicas en tu textura dependerá de tu diseño UV, así que haz el procesamiento de la malla antes que cualquier filtro de material.

Una vez que estés satisfecho con tu objeto y tus texturas, puedes <b>exportar </b>tu resultado mediante el cuadro de diálogo <b>Compartir > Exportar como</b>. Los ajustes generales le permiten elegir el nombre y la ruta, los ajustes de malla le permiten elegir el formato de malla 3D y los ajustes de material le permiten configurar el material de la malla. Puede desactivar la malla o el material para exportar solo uno de ellos de forma individual. Una vez exportada, la malla está lista para utilizarse en otras aplicaciones 3D.
