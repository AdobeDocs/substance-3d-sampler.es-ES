---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/quilt-stitch.html"
breadcrumb-title: ''
description: Utilice el generador de punto de tejido en Substance 3D Sampler para crear patrones de tejidos acolchados y texturas de costura para materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Quilt Stitch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Costura de tejido
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '401'
ht-degree: 0%

---


# Costura de tejido

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-quiltstitch-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Emula un patrón de tejido unido en tus materiales con este filtro.

*Antes y después de aplicar el filtro **Punto de tejido**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0005-quilt-stitch-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0004-quilt-stitch-out.jpg){width="200px"}

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
* **Selección de motivo**:\
  Seleccione el estilo de patrón para la unión/tejido a seguir
* **Importe**: 1-5\
  Controlar la cantidad de mosaico del motivo
* **Rotación**:\
  Girar el motivo
* **Puntada**: alternar\
  Active esta opción para añadir un punto superior y ver la sección de parámetros correspondiente
* **Junta**: alternar\
  Activar para añadir una unión y ver la sección de parámetros correspondiente
* **Tejido**: alternar\
  Active esta opción para añadir tejidos y ver la sección de parámetros correspondiente
* **Pintura de borde**: alternar\
  Active esta opción para pintar la arista entre las secciones acolchadas y ver la sección del parámetro correspondiente
* **Avanzado**: alternar\
  Habilitar para ver los parámetros **Advanced**

**Puntada**

* **Color de puntada superior**: selección de color\
  Defina el color del hilo utilizado para el punto superior
* **Desplazamiento de puntada superior**: 0-1\
  Desplazar el punto superior de los bordes del área de tejido
* **Rotación de puntada superior**: 0-1\
  Cambiar la orientación de los puntos que componen el punto superior
* **Escala de puntada superior**: 0-1\
  Ajuste el tamaño del punto superior en cada dimensión: anchura, longitud y height
* **Intensidad de punción**: 0-1\
  Ajuste la sangría en el tejido causada por el punto superior
* **Rugosidad de puntada superior**: 0-1\
  Ajuste la rugosidad de la rosca
* **Puntada metálica**: 0-1\
  Ajuste el valor metálico de la rosca

**Costura**

* **Costura** **Selección**:\
  Seleccione el estilo de costura a utilizar
* **Intensidad de la costura**: 0-1\
  Modificar la intensidad normal y de height de la costura
* **Intensidad de estiramiento**: 0-1\
  Ajusta el impacto que tiene el estiramiento de la tela en la costura. Este efecto es bastante sutil.

**Tejido**

* **Tipo de tejido**:\
  Seleccione el estilo de tejido que desea utilizar
* **Intensidad de tejido**:\
  Ajuste la intensidad normal y de height del efecto de tejido

**Pintura de borde**

* **Selección de bordes**:\
  Seleccione si el dolor anula o no los detalles normales y de height del material subyacente
* **Color de borde**: selección de color\
  Seleccionar el color de pintura
* **Rugosidad del borde**: 0-1
* **Edge Metallic**: 0-1

**Avanzado**

* **Height de Material base**: 0-1\
  Ajuste la intensidad del mapa de height a partir del material subyacente
* **Intensidad normal**: 0-1\
  Ajuste la intensidad de los cambios normales del mapa debido al filtro **Punto de tejido**. Esto no afecta a la normalidad del material subyacente.
