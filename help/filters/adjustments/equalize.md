---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/adjustments/equalize.html"
breadcrumb-title: ''
description: Utilice el filtro Ecualizar en Substance 3D Sampler para redistribuir los valores de brillo y mejorar el contraste de la imagen automáticamente.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Equalize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ecualizar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---


# Ecualizar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-equalize-18-n-d.png)

**En:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro Ecualizar ajusta el contraste local en función de un rango de distancia. El objetivo del filtro Ecualizar es reducir grandes diferencias en cada canal. Como resultado, suele ser útil como parte del flujo de trabajo de imagen a material (B2M): el filtro de imagen a material (impulsado por IA) incluye una pasada de ecualización dentro del filtro para mejorar los resultados.

Las imágenes siguientes muestran el **filtro Ecualizar** en acción.

![](../../assets/3d-2d-filters-cropped-0033-equalizer-in.jpg)

Antes de agregar el filtro **Ecualizar**, hay una variación significativa en el mapa de height y el color base de este material.

![](../../assets/3d-2d-filters-cropped-0032-equalizer-out.jpg)

Después de agregar **Ecualizar filtro**, el mapa de height y los canales de color base son más uniformes sin perder detalles.

</td>
</tr>
</table>

## Tutorial sobre el filtro Ecualizar

## Parámetros

<b>Parámetros básicos</b>

* <b>Mosaico de entrada</b>: alternar\
  Cuando esta opción está activada, trate el material como si estuviera embaldosado repetidamente, de modo que los valores de color del borde opuesto influyan en los cambios que se realicen cerca de los bordes.
* <b>Radio</b>: 0-1\
  Extienda el efecto Ecualizar en un área más amplia.
* <b>Sangrado de color</b>: 0-1\
  Controla los colores que se desvanecen en el área circundante.
* <b>Detalles locales</b>: 0-1\
  Ajuste cómo el filtro Ecualizar intenta conservar los detalles locales.

<b>*Canal*</b>

Los controles de cada canal funcionan del mismo modo.

* <b>Reemplazar parámetros comunes</b>: alternar\
  Active esta opción para personalizar el efecto Ecualizar para este canal. Cuando se activa, aparecen controles adicionales:
  * <b>Mosaico de entrada</b>: alternar\
    Cuando esta opción está activada, trate el material como si estuviera embaldosado repetidamente, de modo que los valores de color del borde opuesto influyan en los cambios que se realicen cerca de los bordes.
  * <b>Radio</b>: 0-1\
    Extienda el efecto de ecualización por un área más amplia.
  * <b>Mantener diferencias locales</b>: alternar\
    Active esta opción para que el efecto de ecualización funcione con una resolución más alta para mantener los detalles
* <b>Modo de destino</b>:\
  Seleccione cómo sesgar el efecto Ecualizar. De forma predeterminada, Ecualizar intenta mover los colores hacia el color medio del canal. Utilice el parámetro para sesgar hacia un color o valor seleccionado. Con la opción Parámetro seleccionada, aparecerá un control adicional:
  * <b>Destino</b>: selección de color\
    Seleccione un color o valor para que actúe como destino del algoritmo de ecualización.
* <b>Variación de color personalizada</b>: Reguladores de HSL\
  Ajuste el tono, el croma (saturación) y la luminancia (luminancia) del resultado después de ejecutar el algoritmo de ecualización para el canal especificado.

<b>Máscara</b>

* <b>Máscara personalizada</b>: alternar\
  Habilitar o deshabilitar el uso de una máscara personalizada para este filtro
* <b>Máscara personalizada</b>: imagen/pincel\
  Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D
* <b>Inversión de máscara personalizada</b>: alternar
