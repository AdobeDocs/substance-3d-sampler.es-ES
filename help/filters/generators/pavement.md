---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/pavement.html"
breadcrumb-title: ''
description: Utilice el generador de pavimentos de Substance 3D Sampler para crear texturas realistas de pavimentos y superficies de carreteras para materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Pavement
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pavimento
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '384'
ht-degree: 1%

---


# Pavimento

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pavement-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Convierte tu material en un patrón de pavimento. El filtro de pavimento incluye una serie de opciones para cambiar el estilo de patrón de forma rápida y sencilla.

*Ejemplo del **filtro de pavimento**.*

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Escala de Material base**: 0-1\
  Controlar la escala del material utilizado en cada ladrillo
* **Espaciado entre ladrillos**: 0-1\
  Modificar la cantidad de espacio entre ladrillos
* **Redondez de vértice**: 0-1\
  Haga que las esquinas de los ladrillos sean más o menos redondeadas.
* **Redondez de borde**: 0-1\
  Suaviza los bordes de los ladrillos para que parezcan más desgastados de su uso
* **Intensidad de inclinación**: 0-1\
  Cambiar la intensidad de la inclinación aleatoria aplicada a cada ladrillo
* **Intensidad de elevación aleatoria**: 0-1\
  Modifique la variación de height de los ladrillos entre sí.

**Patrón**

Cada patrón tiene un conjunto diferente de parámetros disponibles que aparecerán cuando el patrón se seleccione en **Tipo de patrón**. Experimenta con parámetros para ver el efecto.

* **Tipo de patrón**:\
  Seleccione el motivo para colocar los ladrillos.

**Conjunto**

* **Height**&#x200B;**conjunto: 0-1**\
  Modificar el height del material entre ladrillos
* **Ancho de unión**: 0-1\
  Ajustar hasta dónde se superpone el material entre los ladrillos a los bordes de los ladrillos
* **Variación de ancho de unión**: 0-1\
  Ajuste la aleatoriedad de la **Anchura de unión**
* **Luminosidad conjunta**: 0-1\
  Modifique el aspecto del material entre los ladrillos. Esto puede resultar útil para enmascarar objetos.

**Parámetros avanzados**

* **Intensidad de superficie**: 0-1\
  Controle la intensidad de las normales para deformaciones superficiales como grietas o melladuras.
* **Tamaño de superficie (cm)**: 0-1000\
  Ajustar el tamaño físico representado por el material
* **Escala de Height superficial (cm)**: 0-1000\
  Cambiar el espacio físico representado por el mapa de height
* **Smoothness de superficie**: 0-1\
  Controlar la cantidad de variación y detalle en la superficie
* **Surface Poke**: 0-1\
  Añada daño o variación a la superficie modificando el height y las normales de forma aleatoria
* **Umbral de máscara de perforación superficial**: 0-1\
  Modifique el umbral de la máscara usada para controlar **Surface Poke**
* **Habilitar Scalemap**: alternar\
  Utilice un mapa de escala para ajustar el tamaño de los ladrillos según su posición
* **Intensidad del mapa de escala**: 0-1\
  Ajuste el impacto del mapa de escala en la escala de los ladrillos.
