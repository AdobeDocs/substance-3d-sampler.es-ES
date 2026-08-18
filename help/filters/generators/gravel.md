---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/generators/gravel.html"
breadcrumb-title: ''
description: Utilice el generador de gravilla de Substance 3D Sampler para crear texturas de agregado de gravilla y piedra realistas para materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Gravel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Grava
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '457'
ht-degree: 0%

---


# Grava

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-gravel-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro Grava pone grava sobre el material de forma natural, llenando las grietas.

Estas imágenes muestran el **filtro de grava** que se está usando para llenar de grava las grietas de un material de barro.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0029-gravel-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0028-gravel-out.jpg)

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
* **Cantidad**: 0-1\
  Cambie la cantidad de grava esparcida por el material.
* **Color principal**: selección de color\
  Seleccione el color base de las piedras de grava
* **Color secundario**: selección de color\
  Seleccionar el color secundario de las piedras de grava
* **Coincidencia de color de material de fondo**: 0-1\
  Ajustar el grado de impacto del color de grava por el color del material subyacente
* **Habilitar máscara de cavidad**: alternar\
  Cuando está activada, la grava llenará las cavidades y no se extenderá en las partes más altas del material. Esto puede dar como resultado una dispersión más realista de grava.
* **Umbral de volumen de dispersión**: 0-50\
  Ajuste el volumen de dispersión según los valores de height
* **Enmascaramiento aleatorio**: 0-1\
  Ajuste el porcentaje de grava para enmascarar aleatoriamente
* **Tamaño de piedra**: 1-10\
  Controlar el tamaño de las piedras
* **Variación de tamaño de piedra**: 0-1\
  Controlar la aleatoriedad del tamaño de la piedra
* **Redondez de piedra**: 0-1\
  Hacer piedras más redondas o más angular
* **Rugosidad de la piedra**: 0-1\
  Modificar el valor de rugosidad de las piedras
* **Height de piedra**: 0-1\
  Modifique el height de las piedras. Esto afecta a la forma en que las piedras se mezclan con el material subyacente.
* **Elevación de piedra**: 0-1Modifique la elevación base de las piedras. La elevación fija el piso de donde se encuentran las piedras, mientras que el height fija el height de las piedras del piso.
* **Aleación de elevación de piedra**: 0-1\
  Añada un valor aleatorio a la elevación de cada piedra.
* **Smoothness de superficie**: 0-1\
  Suaviza la parte superior de las piedras
* **Usar máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada para pintar ubicaciones de piedra. Los siguientes parámetros solo estarán visibles si está habilitado **Usar máscara personalizada**.
  * **Desenfoque de máscara**: 0-1\
    Desenfocar los bordes de la máscara pintada
  * **Máscara personalizada**: imagen/pincel\
    Haga clic en el pincel para pintar una máscara personalizada en la que aparecerán las piedras. Haga clic en el cuadrado para importar una imagen y utilizarla como máscara.

**Parámetros avanzados**

* **Tamaño de superficie (cm)**: 0-1000\
  Modifique el tamaño de la superficie que representa el material. El aumento del tamaño de la superficie significa que el tamaño físico de piedras de grava es mayor, y se modificarán en consecuencia.
* **Profundidad de Height** **(cm)**: 0-100\
  Modifique la profundidad física representada por el mapa de height del material. Una mayor profundidad del height significa que el tamaño físico de las piedras es más alto de lo que sería de otra manera, por lo que la intensidad normal de las piedras se incrementa.
