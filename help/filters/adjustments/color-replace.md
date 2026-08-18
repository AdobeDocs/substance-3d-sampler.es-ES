---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/adjustments/color-replace.html"
breadcrumb-title: ''
description: Utilice el filtro Sustitución de color de Substance 3D Sampler para sustituir colores específicos de texturas por nuevos valores de color.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Color Replace
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Sustitución de color
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '570'
ht-degree: 0%

---


# Sustitución de color

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-replacecolor-18-n-d.png)

**En:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Reemplace el color o valor elegido en un canal.

Las imágenes siguientes muestran **Reemplazo de color** en acción. Observe cómo las áreas entre los azulejos siguen siendo del mismo color, solo se cambian los propios azulejos.

![](../../assets/3d-2d-filters-cropped-0051-color-replace-in.jpg)![](../../assets/3d-2d-filters-cropped-0050-color-replace-out.jpg)

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Segmentación avanzada**: alternar\
  Cuando está activado, el filtro puede utilizar un canal independiente para generar información de máscara del canal afectado por la sustitución de color.
  * **Máscara** **De**:\
    Seleccione un canal para que actúe como origen para la generación de máscaras. Por ejemplo, la máscara del valor metálico reemplaza el color base de las áreas metálicas del material
* **Reemplazar en**:\
  Seleccione el canal afectado por el reemplazo de color.
* **Color de destino**: selección de color\
  Seleccione el color que sustituirá a los colores del canal actual.
* **Variación de luminosidad**: 0-1\
  Ajuste en qué medida se ven afectados los valores de luminosidad originales por la luminosidad del nuevo color.
* **Intervalo de máscara**\
  La máscara se crea en función de la combinación de los siguientes valores
  * ****** De luminosidad **: 0-1\
    Intervalo de luminosidad utilizado para crear la máscara ****
  * **De color**: 0-1\
    Rango de color utilizado para crear la máscara
* **Smoothness de máscara**: 0-1\
  Ajustar la granularidad de la máscara
* **Desenfoque de máscara**: 0-1\
  Desenfocar la máscara

**Máscara**

Esta máscara es independiente de la máscara creada en **Parámetros básicos**: puedes usar una máscara personalizada para pintar o usar una imagen para especificar las áreas que se verán afectadas por el filtro **Reemplazo de color** en su conjunto.

* **Usar máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfocar la máscara
  * **Máscara personalizada - Invertir**: alternar\
    Invertir la máscara

## Guía de uso

El filtro **Reemplazo de color** es una poderosa forma de modificar el aspecto de tus materiales; por ejemplo, úsalo para convertir el óxido de hierro en cobre oxidado

El filtro funciona creando primero una máscara basada en los valores de luminosidad y color de un punto elegido y, a continuación, reemplazando el color del área definida por esa máscara. Por lo tanto, para utilizar el filtro:

1. Agregue el **filtro Reemplazar color** a la pila de capas
1. Determine qué canal desea utilizar para crear la máscara y qué canal desea reemplazar el color de
   1. Si desea basar la máscara en un canal pero reemplazar el color de otro, habilite **Segmentación avanzada** y seleccione los canales respectivos.
   1. Si desea basar la máscara en un canal y reemplazar el color del mismo canal, deje **Segmentación avanzada** deshabilitada.
1. Mueva el control en la **vista 2D** sobre el color que desea reemplazar.
1. Ajuste las áreas que cubre la máscara con los controles **Rango de máscara**, **Smoothness de máscara** y **Desenfoque de máscara**.
1. Selecciona un **color de destino** y ajusta la **variación de luminosidad** hasta que estés satisfecho con el efecto.
1. Si lo desea, puede añadir una máscara personalizada para aplicar solo los efectos del filtro en las áreas elegidas. La máscara personalizada no afecta a la máscara creada en el paso 1, sino que es una máscara adicional que puede utilizar para ajustar aún más el lugar en el que se aplica el efecto.

A veces puede resultar útil usar varios **filtros de reemplazo de color** uno encima del otro para crear efectos más avanzados.
