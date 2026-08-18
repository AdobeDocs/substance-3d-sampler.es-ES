---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/wear-and-finish/dirt.html"
breadcrumb-title: ''
description: Usa el filtro de Dirt de Substance 3D Sampler para añadir una acumulación de dirt realista y efectos de suciedad a tus materiales y texturas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Dirt
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Tierra
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '289'
ht-degree: 1%

---


# Tierra

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-dirt-18-n-d.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el **filtro de Dirt** para añadir dirt sobre un material. El **filtro de Dirt** es ideal para hacer que los materiales parezcan antiguos y poco cuidados.

![](../../assets/dirt-filter-ceramic-mozaic-tiles-before-tra.png)

Compare los azulejos limpios de arriba con el filtro de dirt aplicado a ellos a continuación.

![](../../assets/dirt-filter-ceramic-mozaic-tiles-after-tra.png)

</td>
</tr>
</table>

## Parámetros

<b>Parámetros básicos</b>

* <b>Raíz aleatoria</b>: \
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.

* <b>Difusión de Dirt</b>: 0-1 \
  Controla la extensión de la superficie cubierta por el dirt

* <b>Difusión de Dirt superior</b>: 0-1\
  Controla la superficie superior cubierta por el dirt, sin centrarse en los pliegues del material

* <b>Contraste de Dirt</b>: 0-1 \
  Ajuste el nivel de contraste entre las distintas partículas de dirt para controlar cómo se fusiona el dirt con el material subyacente.

* <b>Opacidad del Dirt</b>: 0-1 \
  Controla el nivel de transparencia del dirt en el canal de color base. 1 es completamente opaco.

* <b>Color de Dirt</b>: 0-1 \
  Seleccione el color del dirt.

* <b>Rugosidad del Dirt</b>: 0-1 \
  Ajuste la forma en que la luz dispersión a través de la superficie del material

* <b>Dirt metálico</b>: 0-1 \
  Define qué tan reflectante es la superficie del dirt

* <b>Height de Dirt</b>: 0-1 \
  Controla el impacto del dirt en el mapa de Height

* <b>Intensidad normal del Dirt</b>: 0-1 \
  Controla en qué medida el nivel de dirt afecta al mapa Normal

* <b>Usar imperfecciones de superficie</b>: alternar \
  Activar o desactivar el uso de una imperfección de superficie. Si se habilita, aparece un control adicional:

  <b>Imperfecciones superficiales</b>: image \
  Importe una imagen para utilizarla como una imperfección de superficie o utilice uno de los generadores de texturas disponibles de forma predeterminada en la biblioteca de recursos de Sampler, como &quot;Mancha&quot; o &quot;Manchas negras&quot;
