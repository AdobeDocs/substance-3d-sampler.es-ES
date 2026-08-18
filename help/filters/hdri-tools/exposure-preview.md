---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/exposure-preview.html"
breadcrumb-title: ''
description: Utilice la herramienta Previsualización de exposición en Substance 3D Sampler para previsualizar los ajustes de exposición en imágenes HDRI antes de aplicar cambios.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Exposure Preview
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Previsualización de exposición
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 0%

---


# Previsualización de exposición

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-exposurepreview-18-n-d.png)

**En:** Herramientas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

La **vista previa de exposición** **filter** te permite obtener una vista previa rápida de un espectro de valores de exposición.

A continuación puedes ver lo que hace el **filtro de vista previa de exposición**.

![](../../assets/3d-2d-filters-cropped-0029-exposure-preview-in.jpg)

En la imagen anterior, se ha creado una luz de ambiente y los datos de la imagen HDR son visibles en la **vista 2D**.

![](../../assets/filters-cropped-0028-exposure-preview-out.jpg)

Con el **filtro de vista previa de exposición**&#x200B;**añadido a la pila de capas, un nuevo canal, Diagnóstico de entorno, estará disponible para mostrar la luz del entorno en diversas exposiciones.**

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Exposición Mínima (EV)**: -8 a 8\
  Establezca la exposición de la imagen menos expuesta.
* **Exposición máxima (VE)**: -8 a 8\
  Establezca la exposición de la imagen más expuesta.

## Guía de uso

El **filtro de vista previa de exposición** funciona de manera un poco diferente a otros filtros de Sampler. Se trata de una herramienta cuyo objetivo es ayudar a encontrar la exposición correcta de la luz de tu entorno, pero que en realidad no afecta en absoluto al canal de entorno. En su lugar, al añadir el **filtro de vista previa de exposición** a la pila de capas, se puede ver un canal adicional en la **vista 2D**: el canal de diagnóstico de entorno.

Si visualiza el canal de diagnóstico de entorno, debería poder ver algunas instancias de la imagen de entorno 2D con distintos valores de exposición. Ajuste los parámetros del **filtro de vista previa de exposición** para cambiar el intervalo de exposiciones visibles en el canal de diagnóstico de entorno.
