---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/tools/atlas-creator.html"
breadcrumb-title: ''
description: Utilice la herramienta Atlas Creator en Substance 3D Sampler para crear atlas de texturas a partir de varias imágenes para una organización eficaz del material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Creator
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas Creator
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '469'
ht-degree: 0%

---


# Atlas Creator

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlasgenerator-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

**Atlas Creator** **filter** te permite convertir materiales e imágenes en un atlas. Después, puedes usar otros filtros como **Atlas scatter** y **Atlas splitter** para usar elementos de atlas en los materiales.

Las imágenes a continuación muestran un atlas de hojas de selva antes y después de ser procesado por **Atlas Creator**.

![](../../assets/3d-2d-filters-cropped-0041-atlas-creator-in.jpg)

En la imagen anterior, se ha importado y convertido una imagen de atlas en un material, pero sigue sin ser un material de atlas porque el mapa de opacidad no tiene en cuenta elementos individuales.

![](../../assets/3d-2d-filters-cropped-0040-atlas-creator-out.jpg)

Después de ejecutar **Atlas Creator**, se genera un mapa de opacidad y el área entre los elementos del atlas se rellena en el canal de color base.

</td>
</tr>
</table>

Parámetros

**Parámetros básicos**

* **Quitar formas pequeñas**: 0-1

  Utilice esta opción para ajustar el tamaño mínimo de los objetos dentro del atlas. Esto resulta útil para eliminar artefactos.
* **Opacidad - Influencia de crominancia**: 0-2

  Perfecciona los bordes de los elementos del atlas en función de los valores de color.
* **Agregar opacidad**: imagen/pincel

  Importa un archivo para usarlo como máscara o usa el pincel para pintar áreas que deberían ser opacas directamente en la **vista 2D**.

Guía de uso

## Preparación de una imagen de atlas

Antes de usar el **filtro Atlas Creator**, es recomendable que te asegures de que la imagen del atlas esté preparada correctamente.

**Atlas Creator** funciona según el color de la imagen y no tiene en cuenta la transparencia. Esto significa que la mejor manera de preparar la imagen del atlas es asegurarse de que el espacio entre los elementos sea un blanco o negro uniforme, lo que facilita que **Atlas Creator** genere la máscara de opacidad.

## Generar un material de atlas a partir de una imagen

**Atlas Creator** está diseñado para convertir una imagen de atlas en un atlas de materiales.

1. Importe la imagen de origen a la pila de capas.
1. Si se le solicita que seleccione una plantilla de creación de material, seleccione Imagen a material. De lo contrario, con la imagen en la pila de capas, añade un filtro **Imagen a material (impulsado por IA)** encima de la imagen.
1. Espera a que el filtro **Imagen a material** convierta tu imagen de origen en un material. Ajuste los parámetros hasta que esté satisfecho con el resultado.
1. Agregue el **filtro Creador de Atlas** a la parte superior de la pila de capas.
1. Ajusta los parámetros del **Creador de Atlas** hasta que te guste el resultado.

1. Añada la imagen a la pila de capas. Si se le solicita que seleccione una plantilla de creación de material, seleccione **Usar como mapa de bits**.
1. Con la capa de imagen seleccionada, en el **panel Propiedades**, cambia **Uso de salida** a **Color base**.
1. Agregue **Atlas Creator** a la parte superior de la pila de capas.
1. Ajuste los parámetros del **Creador de Atlas** hasta que esté satisfecho con los resultados: vea el canal de opacidad en la **vista 2D** para ver los resultados del filtro con mayor claridad.
1. Use el **panel Exportar** para exportar los canales generados.
