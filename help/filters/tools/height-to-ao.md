---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/height-to-ao.html"
breadcrumb-title: ''
description: Utilice la herramienta Height a AO de Substance 3D Sampler para convertir los mapas de altura en mapas de oclusión ambiental para la creación de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Height to AO
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: HEIGHT a AO
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 1%

---


# HEIGHT a AO

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-hbao-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Generar un mapa de Oclusión ambiental a partir de datos normales y de height.

Consulte los resultados del **Height a filtro AO** en las imágenes siguientes.

![](../../assets/3d-2d-filters-cropped-0025-height-to-ao-in.jpg)

En la imagen anterior, **Vista 2D** muestra el mapa de altura. El material no incluye ninguna información de Oclusión ambiental en esta imagen.

![](../../assets/3d-2d-filters-cropped-0024-height-to-ao-out.jpg)

En esta imagen, el mapa de Oclusión ambiental ha sido creado por el Height **filtro AO** y es visible en el Vista 2D **AO**. La oclusión ambiental suele ser un efecto sutil, por lo que no es muy fácil de ver en este material. Prueba a usar el filtro de **Height a AO** en tus materiales para aumentar la intensidad de AO y tener una idea de cómo es trabajar con la Oclusión ambiental.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Modo**:\
  Seleccione si desea generar datos del canal de height, del canal normal o de ambos canales a la vez.
* **Oclusión ambiental - Intensidad**: 0-1\
  Ajustar la intensidad de los datos de AO generados
* **Oclusión ambiental - Difusión**: 0-1\
  Ajuste del radio de los datos de AO generados
