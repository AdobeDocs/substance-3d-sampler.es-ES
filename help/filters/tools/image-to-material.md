---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/tools/image-to-material.html"
breadcrumb-title: ''
description: Utiliza la herramienta Imagen a material de Substance 3D Sampler para convertir imágenes individuales en materiales PBR mediante el procesamiento impulsado por IA.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Image To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Imagen a material
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 1%

---


# Imagen a material

![](../../assets/sat-icon-image-to-material.png)

La plantilla **Imagen a material** permite generar un material PBR de alta calidad a partir de una sola imagen de entrada.

Esta plantilla tiene dos algoritmos principales:

* **Con tecnología de inteligencia artificial**
* **B2M**

Consulte a continuación para obtener una explicación detallada de cada algoritmo.

## Ejemplo

A continuación se muestra un ejemplo de canales de material generados a partir de una sola imagen de entrada:

![](../../assets/sat-image-to-material.jpg){width="500px"}

## Algoritmos

Para cambiar el algoritmo de la plantilla **Imagen a material**, haz clic en el menú desplegable debajo del nombre de la plantilla:

![](../../assets/image-to-material-algo-setting.png)

### Con tecnología de IA

El algoritmo <b>con tecnología de IA</b> usa el aprendizaje automático para reconocer formas y objetos, y generar mapas normales, de Height y de rugosidad con precisión, así como para eliminar el albedo de sombras o iluminaciones.

La red neuronal ha sido entrenada en una amplia gama de materiales como telas, orgánicos, interiores y exteriores.

>[!NOTE]
>
> El proceso de conversión de imágenes a material (con tecnología de IA) tardará más en calcularse en imágenes de alta resolución. Recomendamos usar el sistema de [resolución de capa](../../interface/preferences/layer-resolution.md) para optimizar tu flujo de trabajo mientras trabajas.

### B2M

El algoritmo **B2M** utiliza el método Bitmap to Material basado en Substance para generar varios canales, como el color base, normal, metálico, de rugosidad y de oclusión de ambiente, mediante técnicas de procedimiento.

Este algoritmo puede producir resultados menos precisos, pero funcionará en una gama más amplia de imágenes de entrada.

## Adobe Capture

Esta funcionalidad también está disponible en la aplicación móvil de Adobe Capture (Android y iOS). Puede hacer una foto sobre la marcha y obtener una vista previa del resultado directamente en su teléfono.

Envía fácilmente los resultados a Substance 3D Sampler para ediciones posteriores.

![](../../assets/capture-qr-code.gif)

>[!NOTE]
>
> Esta funcionalidad solo está disponible con una suscripción de Adobe a Substance 3D Collection.
