---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/moss.html"
breadcrumb-title: ''
description: Usa el filtro Musgo en Substance 3D Sampler para añadir un crecimiento realista del musgo y efectos de superficie orgánica a tus materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Moss
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Musgo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '462'
ht-degree: 0%

---


# Musgo

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/moss-filter-icon.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el **filtro de musgo** para añadir musgo y liquen a tu material. **Moss** usa el mapa de oclusión de tu material para crecer naturalmente en grietas y grietas.

Las imágenes siguientes muestran el material de dirt antes y después de aplicar el filtro **Moss**.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0021-moss-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0020-moss-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  Semilla aleatoria en la que se basan todos los demás parámetros aleatorios de este filtro.
* **Difusión global de musgo**: 0-1\
  Ajusta la cobertura del musgo en tu material.
* **Color de musgo**: selección de color\
  Seleccione el color principal del musgo.
* **Color de musgo secundario**: selección de color\
  Seleccione el color secundario del musgo.
* **Repartición de musgo**:\
  Seleccione el método utilizado para aplicar el musgo. De forma predeterminada, **Oclusión** utiliza el mapa AO del material para aplicar el musgo, pero las demás opciones tendrán efectos diferentes. Si se selecciona **Máscara** **personalizada**, aparecerá la **sección** **Máscara**.

**Máscara**

Esta sección solo aparece si se ha elegido **Máscara personalizada** en **Parámetros básicos > Repartición de musgo**.

* **Máscara personalizada - Desenfocar**: 0-1\
  Desenfoca la máscara.
* **Máscara personalizada - Invertir**: alternar\
  Invierte la máscara.
* **Máscara personalizada**: imagen/pincel\
  Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D.

**Musgo**

Los parámetros disponibles en esta sección dependen de la opción seleccionada en **Parámetros básicos > Repartición de musgo**.

* **Oclusión**
  * **Propagación de Oclusión de musgo**: 0-1\
    Controlar la propagación del musgo en función de la oclusión.
  * **Máscara de Oclusión de musgo**: 0-1\
    Ajuste la cantidad de musgo con el mapa de oclusión como máscara.
* **General**
  * **Propagación global de musgo**: 0-1\
    Ajuste la cantidad de musgo que debe aparecer.
* **Superior**
  * **Umbral de musgo superior**: 0-1\
    Controle el umbral que determina si aparece o no musgo.
  * **Ángulo del musgo superior** Ajusta la forma en que el musgo se aplica al material en función del mapa normal.
* **Todos**
  * **Todos** incluye todos los parámetros anteriores para **Oclusión**, **General** y **Superior**.

Los siguientes parámetros están disponibles independientemente de qué opción está seleccionada en **Parámetros básicos > Repartición de musgo**.

* **Tamaño de flores de musgo**: 0-1\
  Cambiar la granularidad del musgo.
* **Intensidad de grano de musgo**: 0-1\
  Ajusta lo visible que es el grano del musgo.
* **Tamaño de grupos de musgo**: 0-1\
  Controlar la tendencia del musgo a agruparse.
* **Enfoque De Grupos De Musgo**: 0-1\
  Ajuste la suavidad de los bordes de los agrupamientos.
* **Intensidad de los grupos de musgo**: 0-1\
  Controlar la intensidad de los grupos de musgo.
* **Calado de musgo**: 0-1\
  Ajuste cómo se calan los bordes de la máscara de musgo.
* **Intensidad de la protuberancia del musgo**: 0-1\
  Cambia el desorden del musgo.
* **Umbral de musgo superior**: 0-1

**Parámetros técnicos**

* **Intensidad normal**: 0-1\
  Ajusta la fuerza de las normales del musgo.
* **Intensidad de Oclusión ambiente** Controla la intensidad de la oclusión ambiente del musgo.
