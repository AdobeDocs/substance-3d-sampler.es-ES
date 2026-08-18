---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/hdr-merge.html"
breadcrumb-title: ''
description: Utiliza la herramienta Combinación HDR de Substance 3D Sampler para combinar varias imágenes de exposición en una sola imagen de alto rango dinámico.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > HDR Merge
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Combinación HDR
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---


# Combinación HDR

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/S_HDRMerge_18_N_D.png)

**En:** Herramientas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

La **combinación HDR** **filtro** te permite combinar una colección de imágenes SDR (rango dinámico estándar) para crear una imagen HDR.

Las imágenes siguientes muestran los resultados de la **combinación HDR**.

![](../../assets/3d-2d-filters-cropped-0027-hdr-merge-in.jpg)

Antes de que se realice la **combinación HDR**, la esfera de la **vista 3D** refleja la luz del entorno predeterminada. La **vista 2D** muestra los datos de imagen importados para la primera imagen digitalizada de forma predeterminada, que en este caso es la imagen con menor exposición.

![](../../assets/3d-2d-filters-cropped-0026-hdr-merge-out.jpg)

Después de agregar el **filtro** de combinación HDR **, la esfera refleja una nueva luz de entorno: la imagen HDR generada a partir de las imágenes de entrada.**

</td>
</tr>
</table>

## TParameos

**Parámetros básicos**

* **Diferencia de exposición de entrada (EV)**: 0-2\
  Establezca la diferencia de exposición entre las exposiciones de entrada más alta y más baja. Un delta de alta exposición aumentará el contraste resultante de la operación de combinación.
* **Exposición automática de salida**: alternar\
  Activar o desactivar el ajuste automático de exposición.
* **Desplazamiento de exposición de salida (EV)**: -5 a 5\
  Desplazar la exposición.

## Guía de uso

Mira esto para descubrir cómo usar el **filtro Combinación HDR**, así como otros filtros que pueden ayudar a convertir imágenes SDR en una luz de entorno HDR.

Los pasos básicos para usar el **filtro** de combinación HDR **son los siguientes:**

1. Importe el conjunto de imágenes que se van a combinar en la pila de capas.
1. Agregue el **filtro de combinación HDR** a la pila de capas.
1. Modifique los parámetros para asegurarse de que los valores de exposición son correctos.
