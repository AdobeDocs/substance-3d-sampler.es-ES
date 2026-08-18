---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/rust.html"
breadcrumb-title: ''
description: Usa el filtro de Óxido de Substance 3D Sampler para añadir efectos realistas de óxido y corrosión a los materiales y superficies metálicos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Rust
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Óxido
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 0%

---


# Óxido

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-rust-18-n-d.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el **filtro de Óxido** para añadir una capa de metal oxidado a tu material.

En las imágenes siguientes puedes ver un material metálico antes y después de añadir el **filtro de Óxido**.

![](../../assets/3d-filters-cropped-0002-rust-out.jpg){width="200px"}

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Difusión de Óxido**: 0-1\
  Controlar la extensión o la cantidad de óxido.
* **Influencia de Edge**: 0-1\
  Ajuste la forma en que el óxido interactúa con los bordes en función del mapa de curvatura.
* **Smoothness de pliego**: 0-1\
  Aumente esto para hacer que las áreas oxidadas sean más gruesas o disminuyan para hacerlas más detalladas.
* **Afectar sólo al metal**: alternar\
  Cuando está habilitado, el **filtro de Óxido** solo afectará a las áreas que tengan un valor metálico mayor que 0.

**Óxido**

* **Forma de Óxido**:\
  Cambiar el patrón en el que se basa el óxido.
* **Intensidad de Óxido**: 0-1\
  Modifique la intensidad del efecto óxido. Al aumentar este valor, el óxido se ve más antiguo y más fuerte.

**Pelar**

* **Escala de pelado**: 0-1\
  Cambie la escala del óxido de descamación.
* **Intensidad normal de cáscara**: 0-1\
  Ajuste la visibilidad de las normales de la cáscara.
* **Intensidad del Height de pelado**: 0-1\
  Ajuste el impacto de las cáscaras en el mapa de height.

**Drips**

* **Intensidad de goteo**: 0-1\
  Cambie la intensidad del efecto de goteo.
* **Orientación de goteos**: 0-1\
  Orienta los goteos para que se correspondan con la gravedad o el viento.
* **Longitud de goteo**: 0-1\
  Ajuste hasta dónde se extienden los goteos desde el origen.

**Máscara**

* **Usar máscara**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D.
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfoca la máscara.
  * **Máscara personalizada - Invertir**: alternar\
    Invierte la máscara.
