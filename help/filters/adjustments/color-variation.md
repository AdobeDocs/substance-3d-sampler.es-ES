---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/adjustments/color-variation.html"
breadcrumb-title: ''
description: Usa el filtro Variación de color de Substance 3D Sampler para añadir diversidad y variación de color a las texturas para obtener materiales más naturales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Color Variation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Variación de color
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '534'
ht-degree: 1%

---


# Variación de color

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-colorpalette-18-n-d.png)

**En:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro Variación de color le permite reemplazar varios colores en el color base o en el canal de difusión a la vez. Esto es similar al **filtro Reemplazo de color**, pero mientras que **Variación de color** te permite ajustar varios colores en un filtro, **Reemplazo de color** te da más control sobre la máscara usada para reemplazar colores y se puede usar en varios canales.

En las imágenes siguientes, el filtro **Variación de color** se ha utilizado para ajustar no solo el color blanco subyacente para que parezca un turquesa pálido, sino también para aumentar el contraste de muchas de las motas más pequeñas.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0047-color-variation-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0046-color-variation-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Recuento de colores**: 1-10\
  Modificar el número de colores que reemplazarán a los colores del canal
* **Variación de luminosidad**: 0-1\
  Ajuste en qué medida los valores de luminosidad se ven afectados por el color reemplazado
* **Segmentación**:\
  Base la máscara utilizada para aplicar colores en un canal diferente.
* **Modo de selección de color**:\
  Elija si desea seleccionar los colores de origen de forma manual o automática. Si se elige el modo de selección **Manual**, usa los controles de la **vista 2D** para seleccionar los colores.
  * **Mostrar Ayudante De Texto**: alternar\
    Este control solo es visible si **Modo de selección de color** está establecido en **Manual**. Cuando se habilita, **Show Text Helper** agregará etiquetas de texto a los controles en la **vista 2D** para distinguir más fácilmente los controles de selección de color
* **Color X**: selección de color\
  El número de controles de color disponibles depende del valor seleccionado con **Número de colores**. Para cada color, seleccione el color nuevo para reemplazar el color del material original.

## Guía de uso

El **filtro Variación de color** te permite modificar rápidamente varios colores del canal de color base a la vez. Para algunos materiales, esto puede ser útil para hacer pequeños ajustes, pero el **filtro Variación de color** es el mejor para revisar completamente los colores de tu material con un solo filtro.

Para usar el filtro **Variación de color**:

1. Agregue el **filtro Variación de color** a la pila de capas
1. Ajuste el número de colores que desea reemplazar con **Número de colores**. El filtro reemplazará todo el color del canal: el control **Número de colores** te permite establecer con cuántos colores nuevos se reemplazarán los colores existentes.
1. Si lo desea, seleccione **Segmentation** o un canal diferente en el que basar los colores. Por ejemplo, puede seleccionar el canal metálico y usar **Modo de selección de color > Manual** para colocar un controlador en un valor metálico negro y otro en un valor metálico blanco. Con esta configuración, puede controlar el color de las partes metálicas y no metálicas de su material de forma individual.
1. Seleccione un **Modo de selección de color**. Con el modo manual seleccionado, aparecen controladores en la **vista 2D** que le permiten seleccionar el color base original que reemplazará el nuevo color. Habilite **Show Text Helper** para realizar un seguimiento de qué identificador está vinculado a qué color.
1. Modifique los valores de color con los controles **Color 1 - 10**.
1. Ajuste la **variación de luminosidad** para ajustar en qué medida se ve afectada la luminosidad por la sustitución del color. Con una **variación de luminosidad** baja, puedes aplanar los colores de tu material por completo o usar una **variación de luminosidad** alta para mantener los detalles de los colores originales.
