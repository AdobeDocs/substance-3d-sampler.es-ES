---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/adjustments/brightness-contrast.html"
breadcrumb-title: ''
description: Utilice el filtro Brillo/Contraste de Substance 3D Sampler para ajustar los niveles de brillo y contraste en las texturas y las capas de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Adjustments > BrightnessContrast
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: BrilloContraste
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---


# Brillo/contraste

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-brightnesscontrast-18-n-d.png)

**En:** Ajustes

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Como su nombre indica, el filtro Brillo/Contraste le permite ajustar el brillo y el contraste del material. Es importante tener en cuenta que puede utilizar el filtro Brillo/Contraste para dirigirse a canales específicos. Por ejemplo, puede aumentar el contraste del canal de rugosidad o el brillo del canal de emisión.

En las imágenes siguientes, se ha utilizado el filtro **Brillo/Contraste** para aumentar el brillo y el contraste de un material de azulejo.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0051-brightness-contrast-in.jpg)

</td>
<td style="border: 0;" valign="top">

![](../../assets/brightness-contrast-example.jpg.img.jpg)

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Selección de canal**:\
  Seleccione a qué canal afecta el filtro. Nota: No puede utilizar el filtro Brillo/Contraste para modificar el canal Normal, ya que se comporta de forma diferente a la mayoría de los canales.
* **Brillo**: -1 a 1\
  Modificar el brillo del canal seleccionado
* **Contraste**: -1 a 1\
  Modificar el contraste del canal seleccionado

**Máscara**

* **Usar máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfocar la máscara
  * **Máscara personalizada - Invertir**: alternar\
    Invertir la máscara
