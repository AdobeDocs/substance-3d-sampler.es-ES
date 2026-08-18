---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/wear-and-finish/oxidate.html"
breadcrumb-title: ''
description: Usa el filtro Oxidate en Substance 3D Sampler para añadir efectos de oxidación y empañamiento a los materiales metálicos para conseguir apariencias envejecidas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Oxidate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Oxidar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '395'
ht-degree: 0%

---


# Oxidar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-oxidate-18-n-d.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Añade una capa de oxidación sobre la parte superior del material.*Una superficie arrugada tiene aplicado el **filtro Oxidate**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0019-oxidate-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0018-oxidate-out.jpg){width="200px"}

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
* **Áreas de destino**: alternar\
  Permite cambiar la forma en que se aplica el efecto de oxidación en todo el material. Cuando se habilita, aparece el siguiente control:
  * **Intensidad de áreas de destino**: 0-1\
    Ajuste la extensión del efecto de áreas de destino.
  * **Difusión**: 0-1\
    Ajuste hasta dónde se extiende la oxidación.
* **Color**: selección de color\
  Seleccione el color base del filtro. Los colores base modifican el tono de todos los colores que componen el efecto comburente.
* **Variaciones de color**: 0-1\
  Ajuste la escala del efecto de variación de color.
* **Densidad**: 0-1\
  Cambie la densidad de cobertura del efecto.
* **Sangrado de borde**: 0-1\
  Modifique cómo los bordes del efecto de oxidación se desvanecen en áreas no oxidadas.
* **Revisiones**: 0-1\
  Se trata de un control independiente para modificar la máscara entre las áreas oxidadas y no oxidadas. Combínelo con la densidad y otros controles para ajustar los bordes de las áreas oxidadas.
* **Chipping**: 0-1\
  Fruncir en el área oxidada para revelar el material subyacente.
* **Manchas**: 0-1\
  Ajuste la cantidad de tinción superpuesta sobre el material.
* **Rugosidad de la corrosión**: 0-1\
  Ajuste la rugosidad de las áreas oxidadas.
* **Corrosión metálica**: 0-1\
  Ajuste los valores metálicos de las áreas oxidadas.
* **Intensidad de ruido**: 0-1

**Máscara**

* **Usar máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D.
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfoca la máscara.
  * **Máscara personalizada - Invertir**: alternar\
    Invierte la máscara.
  * **Opacidad de máscara personalizada**: 0-1\
    Ajuste la opacidad de la máscara.

**Parámetros técnicos**

Los siguientes parámetros le permiten ajustar el valor con nombre de todo el material sin agregar una capa de ajuste como **Brillo/Contraste** o **Tono/Saturación**

* **Luminosidad**: 0-1
* **Contraste**: -1 a 1
* **Cambio de tono**: 0-1
* **Saturación**: 0-1
* **Intensidad normal**: 0-1
* **Intervalo de Height**: 0-1
* **Posición del Height**: 0-1
* **Intensidad de Oclusión ambiente**: 0-1
