---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/adjustments/blur.html"
breadcrumb-title: ''
description: Usa el filtro Desenfocar de Substance 3D Sampler para aplicar efectos de desenfoque y reducir el enfoque de la imagen en texturas y capas de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > Blur
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Desenfoque
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 2%

---


# Desenfoque

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-blur-18-n-d.png)

**En:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Desenfoca todo el material o selecciona canales específicos para desenfocar.

En las imágenes que aparecen debajo, el **filtro Desenfocar** se ha aplicado al canal de color base.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0055-blur-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0054-blur-out.jpg)

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Intensidad**: 0-1\
  Ajuste la cantidad de desenfoque aplicado a todos los canales

**Personalizado por canales**

Ajuste la cantidad de desenfoque de cada canal de forma independiente mediante estos controles. En primer lugar, activa el desenfoque específico del canal y aparecerá un regulador para controlar la cantidad de desenfoque aplicado a ese canal.

>[!NOTE]
>
> El desenfoque específico del canal anula el desenfoque de **parámetros básicos > Intensidad** para todo el material. Por lo tanto, si ajusta la intensidad de desenfoque del material en 1, pero habilita un canal y establece su intensidad de desenfoque en 0, el canal no se desenfocará en absoluto, mientras que todos los demás canales se desenfocarán.

* ***Canal*** **: Intensidad de desenfoque personalizada**: alternar\
  Activar el valor de desenfoque específico del canal.
* ***Canal*** ***-*** **Intensidad De Desenfoque**: 0-1\
  Ajuste el desenfoque para el canal especificado.
