---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/tools/upscale.html"
breadcrumb-title: ''
description: Usa la herramienta Ampliación en Substance 3D Sampler para aumentar la resolución de textura mediante la tecnología de ampliación impulsada por IA.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ampliar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 2%

---


# Ampliar

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![Icono de filtro](../../assets/SAPR_SuperResolution_18_N_D.png)

**En:** Herramientas

</td>
<td style="border: 0;" valign="top">

## Descripción

El filtro <b>Aumentar escala de </b>usa IA para aumentar la muestra de los canales PBR (ColorBase, Rugosidad, Normal, Metálico, Height) de las capas que están debajo.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">



</td>
<td style="border: 0;" valign="top">

![](../../assets/F5W_vAHaYAQLsz7.jpg)

</td>
</tr>
</table>

En este ejemplo, comenzamos con una imagen de 1024 x 1024 px, pero el resultado de salida es 4098 x 4098 px. Los resultados que usan el filtro <b>Upscale</b> están más definidos.

</td>
<td style="border: 0;" valign="top">

>[!NOTE]
>
> **Filtro avanzado**
> 
> <b>Upscale</b> es un filtro avanzado.\
> Para usarlo a su máxima capacidad y evitar resultados borrosos, recomendamos establecer las capas debajo de <b>Ampliación</b> en Máx. entrada de capa o Mín. entrada de capa.
> 
> No hay límites sobre cuántos filtros <b>Upscale </b> se pueden usar, pero aumentar la resolución por encima de 8k podría afectar significativamente al rendimiento.

</td>
</tr>
</table>

## Parámetros

<b>Parámetros básicos</b>

* <b>Ejemplo </b>: Alternar grupo de botones\
  Elija el factor de multiplicación para aumentar la escala

## Cómo aplicar el

![](../../assets/SAPR_Upscale_screen_001.png)

En la imagen de arriba, la imagen de baja resolución es procesada por [Image to Material (AI Powered)](image-to-material.md).

![](../../assets/SAPR_Upscale_Screen_003.png)

El filtro <b>Ampliar escala</b> se agrega para mostrar los resultados. Alucina los detalles para alcanzar una mayor resolución manteniendo la calidad del material. Puede elegir entre las propiedades para aumentar la resolución 2 o 4.
