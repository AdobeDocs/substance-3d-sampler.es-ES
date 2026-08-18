---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/decal.html"
breadcrumb-title: ''
description: Utilice el generador de pegatinas de Substance 3D Sampler para crear patrones de pegatinas y texturas de superposición para superficies de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Decal
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pegatina
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '321'
ht-degree: 1%

---


# Pegatina

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-decal-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro de pegatinas le permite añadir instancias de otro material en una ubicación específica. Esto resulta útil para agregar elementos como pegatinas o detalles específicos que podrían no ser fáciles de generar mediante procedimientos.

En las imágenes que aparecen a continuación se muestra el **filtro de pegatinas** que se está utilizando para añadir daños al concreto.

![](../../assets/3d-2d-filters-cropped-0045-decal-in.jpg)

Antes de añadir la calcomanía, la capa base de hormigón está limpia y no está dañada.

![](../../assets/3d-2d-filters-cropped-0044-decal-out.jpg)

Con el **filtro de pegatinas** aplicado, se añaden grietas realistas y daños al material.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Modo de segmentación**:\
  Determina si se va a colocar en mosaico más allá de los identificadores de la **vista 2D**.\
  H significa Horizontal, mientras que V significa Vertical.
* **Coincidencia de color de material de fondo**: 0-1\
  Ajusta los colores del material de la pegatina para que coincidan con el valor de color de las capas que hay debajo.
* **Modo de fusión normal**:\
  Ajuste cómo se mezclan las normales entre el material de pegatina y las capas subyacentes
* **Mezcla de opacidad normal**: 0-1\
  Cambiar la opacidad de las normales del material de pegatina
* **Posición del Height de pegatinas**: 0-1\
  Ajuste el height de la pegatina en relación con el height de las capas subyacentes
* **Escala de Height de pegatinas**: 0-1\
  Cambio del contraste del mapa de height para el material de pegatina

**Parámetros avanzados**

* **Transformación de pegatinas**:\
  Ajuste los valores de transformación de matriz para la pegatina. En general, es más fácil usar los controladores de la **vista 2D** para ajustar la transformación de la pegatina.
* **Etiqueta** **Desplazamiento**: -1 a 1\
  Ajuste el desplazamiento del adhesivo.

## Guía de uso

Para utilizar el filtro de pegatinas:

1. Añadir el filtro de pegatinas a la pila de capas
1. Debajo de la capa de pegatina, aparecerá una ranura de entrada
1. Arrastre el material de pegatina a la ranura de entrada de la capa de pegatina

Puede ajustar los parámetros de filtro en el **panel Propiedades** seleccionando la capa de pegatina.

Puede ajustar los parámetros del material de entrada de pegatinas en el **panel Propiedades** seleccionando el material en la ranura de entrada.
