---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/wear-and-finish/scratch.html"
breadcrumb-title: ''
description: Usa el filtro de rasguños de Substance 3D Sampler para añadir marcas de rasguño realistas y efectos de daño superficial a tus materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Scratch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Scratch
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '701'
ht-degree: 0%

---


# Scratch

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-scratches-18-n-d.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Añade arañazos y desgaste a tu material.

*Antes y después de aplicar el **filtro de memoria virtual**.*

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0001-scratch-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0000-scratch-out.jpg){width="200px"}

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
* **Scratch**: alternar\
  Activar o desactivar los arañazos. Si está habilitada, aparece la sección **Scratch**.
* **Chip**: alternar\
  Añada un efecto recortado a la superficie. Si está habilitada, aparece la sección **Chip**.
* **Micro-scratch**: alternar\
  Añade micro-arañazos a la superficie. Si está habilitada, aparece la sección **Micro-scratch**.

**Scratch**

**Parámetros básicos > Scratch** debe estar habilitado para que aparezca esta sección.

* **Importe**: 0-1\
  Controle el número de arañazos que aparecen.
* **Intensidad**: 0-1\
  Ajuste la profundidad y la intensidad de los arañazos.
* **Escala**: 1-4\
  Cambie el tamaño de los arañazos. Aumentar este regulador reduce el tamaño de borrador.

**Chip**

**Parámetros básicos > Scratch** debe estar habilitado para que aparezca esta sección.

* **Importe**: 0-1\
  Controle el número de fichas que aparecen.
* **Intensidad**: 0-1\
  Ajusta la profundidad y la resistencia de las astillas.
* **Escala**: 1-4\
  Cambiar el tamaño de las fichas. Aumentar este regulador disminuye el tamaño del chip.

**Micro-scratch**

* **Importe**: 0-1\
  Controle el número de micro-rasguños que aparecen.
* **Intensidad**: 0-1\
  Ajuste la profundidad y la intensidad de los micro-arañazos.
* **Rotación**: 0-1\
  Gire los micro-arañazos.
* **Aleatorio de rotación**: 0-1\
  Variar la rotación de los micro-rasguños aleatoriamente.
* **Escala**: 0-2\
  Ajuste el tamaño de los micro-arañazos. Aumente este regulador para aumentar el tamaño de micro-rasguño.
* **Escala aleatoria**: 0-1\
  Varía la escala de los micro-arañazos al azar.
* **Ancho**: 0-1\
  Controlar la anchura de los arañazos
* **Ancho aleatorio**: 0-1\
  Variar la anchura de los micro-rasguños aleatoriamente.
* **Distorsión**: 0-1\
  Añade distorsión a los arañazos para romper la uniformidad.
* **Aleatorio de Distorsión**: 0-1\
  Controlar la aleatoriedad del efecto de distorsión.
* **Frecuencia de Distorsión**: 0-1\
  Controlar la escala de frecuencia del efecto de distorsión.

**Máscara**

* **Máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D.
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfoca la máscara.
  * **Máscara personalizada - Invertir**: alternar\
    Invierte la máscara.

**Parámetros avanzados**

* **Opacidad global**: 0-1\
  Ajusta la opacidad del efecto **Filtro de memoria virtual**.
* **Color base**: alternar\
  Defina si el canal de color base se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Color base - Color**: selección de color\
    Seleccione el color base de los arañazos y las astillas.
* **Metálico**: alternar\
  Defina si el canal metálico se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Valor metálico**: 0-1\
    Ajuste el valor metálico de las áreas rayadas.
* **Rugosidad**: alternar\
  Defina si el canal de rugosidad se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Rugosidad - Valor**: 0-1\
    Ajuste el valor de rugosidad de las áreas rayadas.
* **Normal**: alternar\
  Establezca si el filtro afecta al canal normal. Si está activado, aparecen controles adicionales:
  * **Normal - Intensidad**: -1 a 1\
    Ajusta la intensidad de las normales.
  * **Normal -** **Acoplar**:\
    Reduzca este valor para acoplar las normales.
* **Height**: alternar\
  Establezca si el canal de height se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Height - Intensidad**: 0-1\
    Ajusta el contraste del mapa de height.
* **Emisor**: alternar\
  Establezca si el canal de emisión se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Emisor - Color**: selección de color\
    Defina el color del canal de emisión.
* **Specular level**: alternar\
  Controlar si el canal de specular level se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Specular level** **- Valor**: 0-1\
    Ajuste el valor del canal de specular.
* **Oclusión de ambiente**: alternar\
  Establezca si el canal de oclusión ambiente se ve afectado por el filtro. Si se habilita, aparecen los siguientes controles adicionales:
  * **Oclusión ambiente - Intensidad**: 0-1\
    Ajuste la intensidad del AO generado.
  * **Oclusión de ambiente** **- Radio**: 0-1\
    Ajuste el radio del efecto AO.
* **Opacidad**: alternar\
  Establezca si el filtro afecta al canal de opacidad. Si se habilita, aparece un control adicional:
  * **Opacidad - Valor**: 0-1\
    Cambiar la opacidad del material.
