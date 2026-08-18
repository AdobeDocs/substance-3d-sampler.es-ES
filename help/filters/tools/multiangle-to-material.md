---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/tools/multiangle-to-material.html"
breadcrumb-title: ''
description: Utilice la herramienta Multiángulo a material de Substance 3D Sampler para crear materiales a partir de varias fotografías angulares de una superficie.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Multiangle To Material
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Multiángulo a material
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Multiángulo a material

![](../../assets/sat-multi-angle.png)

La plantilla **Multiángulo a material** crea un material de 2 a 8 imágenes de entrada tomadas en condiciones de luz específicas. Estas condiciones de luz pueden conseguirse con un escáner de materiales.

>[!NOTE]
>
> Puedes encontrar más información sobre cómo crear tu propio escáner de materiales [&#x200B; en este artículo](https://www.adobe.com/products/substance3d/magazine/your-smartphone-is-a-material-scanner-vol-ii.html).

## Ejemplo

A continuación se muestra un ejemplo de un material creado a partir de 8 imágenes de entrada:

* Las primeras 8 imágenes son las imágenes escaneadas tomadas bajo 8 ángulos de luz.
* Las imágenes inferiores son las salidas de la plantilla (color base, normal, height, metálico y rugosidad).

![](../../assets/scan-801x697.jpg){width="400px"}

## Configuración de Substance 3D Sampler

Hay 3 cosas que configurar para asegurarte de que los canales PBR se extraerán correctamente:

* Orden de las imágenes digitalizadas
* El primer ángulo de la luz de entrada
* el siguiente ángulo de la luz de entrada

![](../../assets/multiangles-1024x1024.jpg){width="450px"}

### Orden de las imágenes digitalizadas

Al importar las imágenes, compruebe en Capa de importación de imágenes que las 8 imágenes son consecutivas.

Por ejemplo, la primera imagen a 0° debe ser **scan1**, la imagen a 45° debe ser **scan2**... y la imagen a 315° debe ser **scan8**

![](../../assets/multiangle-image-import.png){width="450px"}

### Primer y siguiente ángulo de luz

En la capa Multiángulo a material:

* Defina El Ángulo De Luz De La Primera Entrada. Si tu **scan1** está a 180°, el primer ángulo de luz de entrada =0,5 o si tu **scan1** está a 0°, el primer ángulo de luz de entrada = 0
* Definir ángulo de luz de entrada siguiente: Define la dirección de la rotación de la imagen. Si scan1 es 0°, scan2 es 45°... el valor es **Counterclockwise**

![](../../assets/multiangle-multiangle-to-material.png){width="450px"}
