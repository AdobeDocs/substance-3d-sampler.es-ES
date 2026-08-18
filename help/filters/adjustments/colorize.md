---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/adjustments/colorize.html"
breadcrumb-title: ''
description: Utilice el filtro Colorear de Substance 3D Sampler para aplicar tintes de color y efectos de coloración monocromos a texturas y materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Colorize
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Colorear
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 1%

---


# Colorear

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_ColorFill_18_N_D.png)

**En:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Colorear te permite añadir color a una selección de canales sin perder detalle.

>[!NOTE]
>
> Si bien el filtro Colorear te permite modificar el canal normal, no es una buena idea hacerlo a menos que conozcas bien cómo funciona el canal normal y cuál será el impacto en tu material. Se trata de una función avanzada que, por lo general, sólo debería ser necesaria en circunstancias específicas.

En estas imágenes se ha utilizado el filtro **Colorear** para ajustar el color base y obtener un material de madera mucho más rico.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0045-colorize-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0044-colorize-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

Los parámetros disponibles en esta sección cambian en función de **Selección de canal**.

* **Selección de canal**:\
  Seleccione el canal al que afectará el filtro. Es recomendable ver el canal seleccionado en la vista 2D para ver directamente los resultados del filtro.
  * ***Opciones de color base/emisión***
    * ***Nombre de canal*** **- Color**: selección de color\
      Seleccione el color utilizado para colorear el canal
    * ***Nombre de canal*** **: mantener luminosidad**: alternar\
      Si se activa, se mantendrán los valores de Luminosidad o Luminosidad de los colores originales
    * ***Nombre de canal*** **- Intensidad**: 0-1\
      Ajuste la intensidad del efecto Colorear.
  * ***Opciones de canal normal***
    * **Normal - Ángulo de Pendiente**: 0-90\
      Modificar el degradado de la normal
    * **Normal - Dirección**: 0-360\
      Ajuste la dirección de las caras normales
    * **Normal - Mantener luminosidad**: alternar\
      Si se activa, se mantendrá la luminosidad de las normales originales
    * **Normal - Intensidad**: 0-1\
      Ajuste la intensidad del efecto Colorear.
* **Máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfocar la máscara
  * **Máscara personalizada - Invertir**: alternar\
    Invertir la máscara
