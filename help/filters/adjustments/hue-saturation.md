---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/hue-saturation.html"
breadcrumb-title: ''
description: Utilice el filtro Tono/Saturación en Substance 3D Sampler para ajustar los valores de tono, saturación y luminosidad en texturas y materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > HueSaturation
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: SaturaciónDeTono
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---


# Matiz/Saturación

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-hueandsat-18-n-d.png)

**En:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro Tono/Saturación le permite ajustar el color de su color base y difundir canales. También puede utilizar una máscara para modificar específicamente los colores solo de partes de la imagen.

Las imágenes siguientes muestran el **filtro Tono/Saturación** que se usa para ajustar el Tono de un material de mosaico.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0027-hue-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0026-hue-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Tono**: -1 a 1\
  Ajustar el tono de la imagen: esto es útil para corregir los colores en el flujo de trabajo de Imagen a material.
* **Saturación**: -1 a 1\
  Ajuste la saturación para hacer que los colores resalten o disminuya la intensidad del color.
* **Luminosidad**: -1 a 1\
  Modifica la luminosidad de los colores.
* **Colorear**: alternar\
  Cuando está desactivado, el filtro ajusta los colores que ya están presentes. Cuando está activado, el filtro reemplazará los colores en función de los reguladores Tono, Saturación y Luminosidad, al tiempo que mantiene los detalles.

**Máscara**

* **Usar máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfocar la máscara
  * **Máscara personalizada - Invertir**: alternar\
    Invertir la máscara
