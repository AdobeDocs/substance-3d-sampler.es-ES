---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/generators/floor-tiles.html"
breadcrumb-title: ''
description: Utilice el generador de azulejos de piso en Substance 3D Sampler para crear patrones de azulejos de piso realistas y texturas cerámicas para materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Floor Tiles
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Azulejos de piso
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '787'
ht-degree: 0%

---


# Azulejos de piso

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-floortiles-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro Mosaicos de suelo divide el material subyacente y lo convierte en una disposición de Mosaicos de suelo.

Las imágenes a continuación muestran un material de hormigón convertido en baldosas de suelo con un patrón de damas.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0031-floor-tiles-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0030-floor-tiles-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

Parámetros

<b>Parámetros básicos</b>

* <b>Raíz aleatoria</b>: \
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* <b>Número de materiales</b>: \
  Cambie el número de materiales que desea convertir en azulejos de piso. El primer material viene determinado por las capas situadas bajo la capa del filtro Mosaicos. Si se selecciona, se puede añadir el segundo como entrada
* <b>Intensidad de materiales de entrada</b>: 0-1 \
  Cuánto se verán los detalles de los materiales de entrada en los azulejos
* <b>Invertir Materiales</b>: Alternar \
  Cuando utilice dos materiales, intercambie el lugar en el que aparecen en los mosaicos.
* <b>Variación de color</b>: 0-1 \
  Cuánto varía el color entre cada azulejo del mismo material
* <b>Radio de bisel</b>: 0-1 \
  Tamaño del azulejo vs el tamaño del mortero
* <b>Profundidad biselada</b>: 0-1 \
  Profundidad del mortero
* <b>Redondez del bisel</b>: 0-1 \
  Determina los ángulos exteriores de los azulejos
* <b>Granulado de superficie</b>: 0-1 \
  Determina el grado de detalle del material original que aparece en los mapas normal y de height de los azulejos
* <b>Máscara de motivo</b>: Entrada.  \
  Cada máscara de motivo de azulejos de suelo tiene un conjunto diferente de parámetros disponibles. Aquí solo se tratan los parámetros disponibles para <b>Square Tile</b>

  * <b>Raíz aleatoria </b>\
    La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
  * <b>X Cantidad </b>\
    Ajustar el número de columnas de azulejos
  * <b>Importe Y</b> \
    Ajustar el número de líneas de azulejos
  * <b>Degradado </b> \
    Ajusta la proporción del tamaño del azulejo en comparación con el tamaño del mortero.
  * <b>Aleatorio de luminancia</b>\
    Como la luminancia influye en el mapa de height, este parámetro elimina aleatoriamente algunos mosaicos
  * <b>Rotación de motivo</b>: 0-1 \
    Rota el ángulo de los azulejos, manteniéndolos alejados unos de otros para evitar la superposición
  * <b>Escala de forma:</b> 0-1 \
    Ajusta la proporción del tamaño del azulejo en comparación con el tamaño del mortero.
  * <b>Escala de forma aleatoria </b>\
    Añade aleatoriamente alguna diferencia en el tamaño de los azulejos
  * <b>Tamaño de forma </b>\
    Ajustar la longitud y la anchura de los azulejos
  * <b>Tamaño de forma aleatorio </b>\
    Añada un toque aleatorio a la longitud y la anchura de los azulejos
  * <b>Modo de desplazamiento de posición</b>: Lista desplegable
  * <b>Desplazamiento de posición </b>\
    Cambia aleatoriamente las columnas de azulejos para que los azulejos no estén alineados horizontalmente
  * <b>Posición aleatoria</b> \
    Coloca los azulejos aleatoriamente en la superficie, con alguna superposición potencial entre los azulejos
  * <b>Rotación de forma </b>\
    Gire el ángulo de las baldosas en la misma dirección, mientras las mantiene lo más cerca posible con una superposición potencial
  * <b>Rotación de forma aleatoria </b>\
    Gire aleatoriamente el ángulo de las baldosas, manteniéndolas lo más cerca posible con una superposición potencial

<b>Hueco</b>

* <b>Color de hueco</b>: selección de color \
  Cambiar el color entre azulejos
* <b>Rugosidad de hueco</b>: 0-1 \
  Cambie el valor de rugosidad del material entre azulejos.
* <b>Hueco metálico</b>: 0-1 \
  Cambie el valor metálico del material entre azulejos.
* <b>Height de hueco</b>: 0-1 \
  Cambie el valor de height del material entre azulejos.
* <b>Irregularidad De Hueco</b>: 0-1 \
  Ajusta la precisión con la que se aplicará el mortero entre los azulejos.

<b>Edad</b>

* <b>Inclinación del piso</b>: 0-1 \
  Añade un poco de inclinación a los azulejos aleatorios
* <b>Aleatorio de Height</b> \
  Agregar una diferencia de height entre azulejos de forma aleatoria
* <b>Dirt</b>: 0-1 \
  Añadir dirt a los azulejos y al espacio
* <b>Daños</b>: 0-1 \
  Quite algunos fragmentos del borde del bisel de cada azulejo, aleatoriamente
* <b>Imperfecciones</b> \
  Añade pequeños agujeros e imperfecciones en los azulejos

<b>Parámetros técnicos</b>

* <b>Escala de material</b>: 0-1 \
  Escala del material dentro de las baldosas
* <b>Intensidad normal</b>: 0-1 \
  Ajuste la intensidad de la normal de la brecha, las baldosas y el material dentro de

<b>Guía de uso</b>

El filtro Azulejos de suelo le permite convertir rápidamente su material en azulejos. La mayor parte del filtro Azulejos de suelo es bastante fácil de usar, excepto cuando se utilizan varios materiales. Para utilizar dos materiales:

1. Establezca <b>Parámetros básicos > Número de materiales</b> en 2.
1. Arrastre el segundo material a la ranura de entrada que ha aparecido bajo el filtro Mosaicos de suelo en la pila de capas.
1. Ajuste los parámetros del material de entrada hasta que esté satisfecho con el resultado.

Si bien es posible añadir varios materiales y filtros en una sola ranura de entrada, generalmente es una buena idea evitar hacerlo, ya que añade complejidad y puede dificultar la lectura del material cuando vuelva a él más adelante. En su lugar, cree nuevos materiales en el proyecto y, a continuación, arrastre una instancia del nuevo material a la ranura de entrada. Cuando actualice el material en el proyecto, se actualizará automáticamente en la ranura de entrada, lo que le proporcionará un control total y simplificará la pila de capas.
