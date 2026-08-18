---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/delight-ai-powered.html"
breadcrumb-title: ''
description: Utiliza el filtro de Deleite de Substance 3D Sampler, impulsado por IA, para eliminar la información de iluminación de las imágenes y crear materiales base neutros.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Delight (AI Powered)
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Deleite (con tecnología de IA)
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---


# Deleite (con tecnología de IA)

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-lightgeneric-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El Delighter le permite eliminar la información de iluminación del canal de color base. Esto es importante al convertir imágenes en materiales, ya que generalmente los materiales no deben incluir información de iluminación. Un material es una colección de información que explica cómo debe reaccionar la luz con una superficie, por lo que si ya hay información de luz horneada en un canal que no debe tener información de luz, puede romper la capacidad del material para representar la superficie de manera realista.

*A **Un ejemplo de una imagen antes y después de ser procesada por el filtro**Deleite (con IA)**. Observe que las sombras y las iluminaciones se han quitado, solo permanece el color base.*

![](../../assets/120-0-comparison.png)

Las imágenes siguientes muestran un material antes y después de ser procesado por un filtro **Deleite (impulsado por IA)**.

![](../../assets/3d-2d-filters-cropped-0043-delighter-in.jpg)

En la imagen anterior, el material todavía incluye una cantidad sustancial de información de iluminación en el canal de color base. Las sombras oscuras entre ladrillos no deben estar presentes en el canal de color base.

![](../../assets/3d-2d-filters-cropped-0042-delight-out.jpg)

Después del agradable pase, se han eliminado las sombras para crear un canal de color base más preciso físicamente. Si bien los resultados en este ejemplo pueden no parecer perceptibles, imágenes agradables es un paso importante de la conversión de imágenes en materiales.

En las imágenes de origen, la luz procede de fuentes estáticas, pero los materiales deben ser capaces de manejar la luz procedente de cualquier ángulo. Por ejemplo: si una imagen de origen con luz que brilla desde arriba hacia abajo se convierte en un material sin pasar por un paso agradable, podría mostrarse en un espacio 3D donde la luz brilla desde abajo hacia arriba. El material se verá rápidamente fuera de lugar porque al mismo tiempo parece estar proyectando sombras de múltiples luces cuando solo hay una única fuente de luz.

</td>
</tr>
</table>

## Parámetros

El deleitador no tiene parámetros - funciona automáticamente.

## Guía de uso

¿Cómo se usa?

Agregue el **filtro Delighter** a la parte superior de la pila de capas.

### ¿Cuándo usarlo?

Cuando uses **Imagen a material (B2M)**, una vez que hayas extraído todos los canales de tus imágenes y hayas convertido el material en mosaico, usa el encendedor para eliminar la información de iluminación del color base. **Imagen a material (con tecnología de inteligencia artificial)** incluye un pase agradable, por lo que no deberías usar el filtro **Delighter (con tecnología de inteligencia artificial)** con él.
