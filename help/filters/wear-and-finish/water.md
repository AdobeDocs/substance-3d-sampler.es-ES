---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/wear-and-finish/water.html"
breadcrumb-title: ''
description: Usa el filtro Agua de Substance 3D Sampler para añadir efectos de agua, humedad y humedad a tus materiales y texturas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Water
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Agua
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Agua

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-water-18-n-d.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el **Filtro erosionado** para desgastarte en los puntos álgidos de tu material.

![](../../assets/water-compare.png)

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Nivel de agua**: 0-1\
  Ajusta el height del agua.
* **Oscuridad del agua**: 0-1\
  Aclarar o oscurecer el agua.
* **Humedad de los bordes**: 0-1\
  Ajuste hasta qué punto por encima de la línea de agua el material parece húmedo.
* **Habilitar Dirt en el agua**: alternar\
  Añada dirt a la parte superior del agua modificando ligeramente el mapa de rugosidad. La **sección de Dirt** solo aparece si este parámetro está habilitado.
* **Máscara personalizada**: alternar\
  Cuando se activa, aparece el siguiente control adicional:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara personalizada o use el pincel para pintar una máscara directamente en la **vista 2D**.

**Dirt**

Esta sección solo aparece si **Parámetros básicos > Habilitar Dirt en agua** está habilitado

* **Cantidad de Dirt**: 0-1\
  Ajuste la cantidad de dirt flotando en la superficie del agua.
* **Intensidad de Distorsión**: 0-1\
  Controle la cantidad de distorsión del dirt superficial basándose en la intersección entre el agua y el resto del material.
* **Intensidad del borde del Dirt**: 0-1\
  Ajuste la intensidad del dirt de la superficie cerca de los bordes de la máscara de dirt.
* **Distancia de borde del Dirt**: 0-1\
  Controle la distancia del borde del dirt desde la intersección entre las áreas húmedas y secas del material.
* **Precisión de borde**: 0-1\
  Ajuste la precisión del borde del dirt.
* **Deformación de borde**: 0-1\
  Deforme el borde para romper la uniformidad de la superficie del dirt.

**Parámetros avanzados**

* Distancia de humedad de **bordes**: 0-1\
  Controle hasta dónde se extiende la humedad del borde en las áreas secas.
* **Cantidad de desenfoque de Profundidad**: 0-1\
  Ajuste cuánto se desenfoca el color base de las áreas que están bajo el agua.
* **Opacidad De Desenfoque De Profundidad**: 0-1\
  Ajusta la transparencia del agua.
* **Color de lodo**: selección de color\
  Cambie el color del dirt que se encuentra en la parte superior de la superficie del agua.
* **Opacidad del lodo**: 0-1\
  Ajustar la transparencia del lodo.
