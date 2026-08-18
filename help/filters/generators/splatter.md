---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/generators/splatter.html"
breadcrumb-title: ''
description: Usa el generador de salpicaduras en Substance 3D Sampler para crear salpicaduras de pintura y efectos de patrones aleatorios para texturas de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Splatter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Salpicadura
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '736'
ht-degree: 0%

---


# Salpicadura

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-splatter-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Dispersa instancias de otros materiales por el material.

>[!NOTE]
>
> Para los materiales del atlas, utilice en su lugar el filtro de Atlas scatter.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Entrada de material**:\
  Seleccione el número de materiales que se utilizarán como entradas. Nota: una capa de Splatter con 3 ranuras de entrada, pero solo una ranura llena con una entrada, aparecerá de forma diferente a una capa de Splatter con 1 ranura de entrada y esa ranura llena con la misma entrada. Por esta razón, se recomienda utilizar solo tantas entradas como sean necesarias.
* **Tamaño de cuadrícula**: 1-64\
  El tamaño de la cuadrícula determina el número de instancias creadas por el filtro Dispersión.
* **Profundidad de Height AO**: 0-1\
  Ajuste la intensidad del AO para las instancias creadas por el filtro.

**Forma**

* **Escala**: 0-5\
  Ajustar el tamaño base de todas las instancias
* **Escala aleatoria**: 0-1\
  Ajuste la aleatoriedad del valor de escala para cada instancia
* **Escalar sin superposición**: 0-1\
  Modificar el tamaño de las instancias para evitar superposiciones
* **Posición aleatoria**: 0-2\
  Controlar la aleatoriedad de la dispersión de instancias
* **Aleatorio de rotación**: 0-1\
  Controlar la aleatoriedad de la rotación de instancias
* **Rotación desde la Pendiente de fondo**: 0-1\
  Modifique el impacto que tienen las normales del material subyacente en la rotación de instancias.

**Color base**

* **Coincidencia de Albedo**: 0-1\
  Hacer coincidir el color de las instancias con el color del material subyacente
* **Ajuste de HSL**: 0-1\
  Ajuste del tono, la saturación y la luminosidad de las instancias
* **Aleatorio de HSL**: 0-1\
  Controlar la aleatoriedad del tono, la saturación y la luminosidad de cada instancia

**Normal**

* **Normal desde** **Fondo**: 0-1\
  Ajuste en qué medida la normalidad del material bajo cada instancia afecta a la normal de la instancia.
* **Ángulo normal aleatorio**: 0-1\
  Incline las normales de cada instancia en un ángulo aleatorio.

**Rugosidad**

* **Ajuste de rugosidad**: -1 a 1\
  Añadir o restar del valor de rugosidad de manera uniforme en todas las instancias
* **Aleación de rugosidad**: -1 a 1\
  Añadir o restar aleatoriamente del valor de rugosidad de cada instancia
* **Rugosidad Del Fondo**: 0-1\
  Ajustar el grado de impacto del valor de rugosidad del material subyacente en el valor de rugosidad de cada instancia

**Height**

* **Desplazamiento de Height**: -1 a 1\
  Desplazar el height de instancias. Esto puede afectar al modo en que las instancias se fusionan con el material subyacente.
* **Aleatorio de desplazamiento de Height**: 0-1\
  Añada un valor aleatorio al desplazamiento de height de cada instancia
* **Escala de Height**: 0-2\
  Ajuste el height de todas las instancias.
* **Escala aleatoria de Height**: 0-1\
  Añada un valor aleatorio al height de cada instancia
* **Sesgar desde Pendiente grande**: 0-1\
  Añada una pendiente a cada instancia para que coincida con la pendiente del material subyacente
* **Smoothness de Pendiente de fondo**: 0-2\
  Ajuste la pendiente del fondo para los propósitos del parámetro **Sesgar desde Pendiente grande**
* **Ajustar al fondo**: 0-1\
  Controle en qué medida el mapa de height de fondo afecta al mapa de height de instancias. Esto le permite ajustar instancias alrededor de los detalles del fondo
* **Fondo conformado suave**: 0-1\
  Ajustar la cantidad de detalles visibles debido a **Ajustar al fondo**

**Metálico**

* **Ajuste metálico**: -1 a 1\
  Controlar los valores metálicos de las instancias
* **Aleatorio metálico**: -1 a 1\
  Añada o reste valores aleatorios de los valores metálicos de cada instancia
* **Metálico desde el fondo**: 0-1\
  Ajuste el impacto que tienen los valores metálicos de fondo en cada instancia

**Máscara**

* **Usar máscara personalizada**: alternar\
  Active esta opción para utilizar una máscara personalizada y acceder a los controles de la máscara personalizada:
  * **Máscara personalizada**: imagen/pincel\
    Importa una imagen para usarla como máscara personalizada o pinta directamente en la **vista 2D**
  * **Desenfoque de máscara personalizado**: 0-1\
    Desenfocar los bordes de la máscara personalizada
  * **Inversión de máscara personalizada**: alternar
  * **Opacidad de máscara personalizada**: 0-1\
    Ajuste la intensidad de la máscara personalizada

Guía de uso

El filtro Salpicaduras es una forma útil de dispersión de recursos en el material, como hojas, piedras o basura.

Para utilizar el filtro Salpicadura:

1. Añadir el filtro Salpicadura a la pila de capas
1. En la capa de salpicaduras, aparecerán las ranuras de entrada
1. Si lo desea, cambie el número de ranuras de entrada disponibles con **Parámetros básicos > Entrada de material**
1. Arrastre los materiales a las ranuras de entrada de Splatter

Puede ajustar los parámetros de dispersión en el **panel Propiedades** seleccionando la capa de salpicaduras.

Puede ajustar los parámetros de los materiales de entrada en el **panel Propiedades** seleccionando el material en la ranura de entrada.
