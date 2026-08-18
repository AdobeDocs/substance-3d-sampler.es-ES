---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/warp.html"
breadcrumb-title: ''
description: Utilice la herramienta Deformar de Substance 3D Sampler para aplicar efectos de deformación direccional y distorsión a las texturas y capas de material.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Warp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Deformar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 1%

---


# Deformar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-warp-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El **filtro de deformación** te permite deformar el material en función de una serie de ruidos generados.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Selección de ruido**:\
  Seleccione el ruido en el que desea basar la deformación. Los distintos ruidos pueden crear efectos diferentes.
* **Escala de ruido**: 0-10\
  Ajuste la escala del ruido de origen. El ruido siempre será de azulejo.
* **Tipo**:\
  Seleccione el método que se utilizará para deformar el material. Si se seleccionan **Deformación direccional** o **Deformación multidireccional**, aparecerá un parámetro adicional:
  * **Ángulo de deformación**: 0-1\
    Ajuste la dirección en la que se produce la deformación
* **Intensidad**: 0-1\
  Ajuste la intensidad de la deformación.
* **Ruido personalizado**: alternar\
  Active esta opción para usar un ruido personalizado en lugar de la selección en **Selección de ruido**. Los parámetros disponibles cambiarán en función de si **Ruido personalizado** está habilitado o deshabilitado. Si se activa, aparecerán los siguientes parámetros:
  * **Desenfoque de ruido personalizado**: 0-1\
    Desenfocar el ruido personalizado
  * **Ruido personalizado**: imagen/pincel\
    Importe un mapa de ruido personalizado para utilizarlo como origen de deformación.
* **Deformación por canal**: alternar\
  Cuando se activa, aparecen secciones adicionales para controlar la deformación de cada canal de forma independiente. Para cada canal están disponibles los siguientes parámetros:
  * ***Nombre de canal***: alternar\
    Alterne si el **filtro de deformación** afecta a este canal.
  * **Modo De Fusión**:\
    Seleccione cómo se mezclan los resultados de la deformación de este canal con la capa subyacente
  * **Opacidad**: 0-1\
    Cambiar la opacidad de los resultados de filtro de este canal.
