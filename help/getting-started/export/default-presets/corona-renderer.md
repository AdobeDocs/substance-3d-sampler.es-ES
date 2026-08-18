---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/getting-started/export/default-presets/corona-renderer.html"
breadcrumb-title: ''
description: Aprenda a exportar materiales de Substance 3D Sampler utilizando el ajuste preestablecido de Procesador Corona para flujos de trabajo de visualización de la arquitectura.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Default Presets > Corona Renderer
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Procesador Corona
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '91'
ht-degree: 2%

---


# Procesador Corona

| Ajuste preestablecido | Compatibilidad | Descripción de salida de empaquetado |
| --- | --- | --- |
| Procesador Corona | <ul data-preserve-html="true"><li data-preserve-html="true">PBR Metálico/Rugosidad</li><li data-preserve-html="true">SPECULAR/Brillo PBR</li></ul> | **BrilloReflejo****Difuso** (\*)**ColorReflejo** (\*\*)**FresnelIOR** (\*\*\*)**Desplazamiento ****Normal**** Emisor****Opacidad** |

>[!NOTE]
>
> **(\*)** Brillo de reflejo: Versión cuadrada del canal de brillo (Brillo \* Brillo)
> 
> **(\*\*)** Color de reflejo: Exportar un mapa donde el blanco indique un material dieléctrico y otros colores para materiales metálicos
> 
> **(\*\*\*)** Francés IOR: 1 dividido por el valor ior, ior se genera a partir del mapa metálico : 1,4 para dieléctricos, 100 para metales (color negro)
