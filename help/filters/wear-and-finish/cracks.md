---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/wear-and-finish/cracks.html"
breadcrumb-title: ''
description: Usa el filtro Grietas de Substance 3D Sampler para añadir patrones de grietas realistas y efectos de daño de la superficie a tus materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Cracks
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Grietas
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '299'
ht-degree: 1%

---


# Grietas

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-cracks-18-n-d.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el **filtro de Grietas** para envejecer y dañar tu material al agregarle una red de grietas y grietas.

**Filtro de Grietas** aplicado a un material de mármol limpio.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0043-cracks-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0042-cracks-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Extender Grietas**: 0-1\
  Ajuste hasta dónde se extienden las grietas: esto modifica la anchura y la longitud de la grieta.
* **Importe de Grietas**: 0-1\
  Cambie el número de grietas que aparecen.

**Máscara**

* **Usar máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D.
  * **Máscara personalizada - Invertir**: alternar\
    Invierte la máscara.

**Grietas**

* **Color de Grietas**: selección de color\
  Cambie el color de la superficie interior revelada por las grietas.
* **Rugosidad de las Grietas**: 0-1\
  Ajuste el valor de rugosidad de las grietas.
* **Opacidad de rugosidad de Grietas**: 0-1\
  Ajuste cuánto afecta el valor **Rugosidad de las Grietas** al mapa de rugosidad
* **Grietas metálicas**: 0-1\
  Modifique el valor metálico de las grietas.
* **Opacidad metálica de las Grietas**: 0-1\
  Ajuste el impacto del valor **Grietas metálicas** en el mapa metálico
* **Intensidad de height de las Grietas**: 0-1\
  Ajuste la profundidad de las grietas. Esto afecta tanto al mapa de height como a los resultados normales del mismo.

**Parámetros avanzados**

* **Intensidad normal**: 0-1\
  Ajusta la fuerza de la grieta normal.
* **Intervalo de Height**: 0-1\
  Modifique el rango de height del material completo. Para ajustar el height de las grietas, use **Grietas > Intensidad de Height de las Grietas**.
* **Posición del Height**: 0-1\
  Desplazar el mapa de height del material completo.
