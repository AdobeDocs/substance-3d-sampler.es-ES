---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/texture-import.html"
breadcrumb-title: ''
description: Aprenda a importar texturas en Substance 3D Sampler para utilizar archivos de imagen existentes en sus flujos de trabajo de creación de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Texture Import
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Importación de textura
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 4%

---


# Importación de textura

![](../assets/Capture-decran-2025-02-19-162128.png.img.png)

La plantilla **Importación de textura** carga varias imágenes y las conecta automáticamente a los canales de salida correctos en función de sus nombres de archivo.

La coincidencia de canales se basa en las convenciones de nomenclatura específicas que se detallan a continuación. En el caso de duplicados o texturas sin coincidencia, las imágenes se marcarán como tales en la interfaz.

## OpenPBR

Sampler hará coincidir los archivos con los siguientes identificadores de OpenPBR con el canal equivalente en el material.

>[!NOTE]
>
> Los identificadores de canal de height son los mismos que se utilizan para ASM.


| Identificador de OpenPBR | Uso de SBSAR |
| --- | --- |
| base_weight | baseWeight |
| base_color | baseColor |
| base_metalness | metálico/metálico |
| base_diffuse_roughness | baseDiffuseRoughness |
| specular_weight | specularWeight |
| specular_color | specularColor |
| specular_roughness | rugosidad/rugosidad especular |
| specular_roughness_anisotropía | specularRoughnessAnisotropy/anisotropyLevel |
| specular_ior | especularIOR/IOR |
| transmision_weight | transmisiónPeso |
| transmission_color | transmisiónColor/absorciónColor |
| transmisión_profundidad | transmisiónProfundidad/absorciónDistancia |
| transmisión_dispersión | transmisiónDispersión |
| transmisión_dispersión_anisotropía | transmisiónDispersiónAnisotropía |
| transmisión_dispersion_scale | transmisiónEscalaDeDispersión |
| transmisión_dispersion_abbe_number | transmisiónDispersiónAbbeNumber |
| subsurface_weight | subsuperficialPeso/translucidez |
| subsurface_color | subsurfaceColor/scatteringColor |
| subsurface_radius | subsurfaceRadius/scatteringDistance |
| subsurface_radius_scale | subsurfaceRadiusScale/scatteringDistanceScale |
| subsurface_dispersión_anisotropía | subsurfaceScatterAnisotropy |
| coat_weight | coatPeso/coatOpacidad |
| coat_color | coatColor |
| coat_roughness | coatRoughness |
| coat_roughness_anisotropía | coatRoughnessAnisotropy |
| coat_ior | coatIOR |
| coat_darkening | coatDarkening |
| fuzz_weight | fuzzWeight/sheenOpacidad |
| fuzz_color | fuzzColor/sheenColor |
| fuzz_roughness | fuzzRoughness/sheenRoughness |
| issue_weight | pesoDeEmisión |
| issue_luminance | emisiónLuminancia |
| issue_color | issueColor/emisive |
| thin_film_weight | thinFilmWeight |
| thin_film_thickness | thinFilmThickness |
| thin_film_ior | thinFilmIOR |
| opacidad | opacidad |
| thin_walled | thinWalled |
| normal | normal |
| tangente | tangente |
| coat_normal | coatNormal |
| coat_tangent | coatTangent |

## Adobe Standard Material

A continuación se muestra una lista de las convenciones de nomenclatura de archivos admitidas para cada canal:

| **Canal** | **Material estándar de Adobe** |
| --- | --- |
| **Oclusión de ambiente** | <ul><li>oclusión ambiental</li><li>ao</li><li>oclusión</li><li>ambient_occlusion</li></ul> |
| **Color base** | <ul><li>color base</li><li>color</li><li>albedo</li><li>base_color</li><li>base</li><li>frío</li><li>color</li><li>base_color</li><li>color base</li></ul> |
| **Difusión** | <ul><li>difundir</li><li>diff</li></ul> |
| **Emissive** | <ul><li>emisivo</li></ul> |
| **Brillo** | <ul><li>brillo</li><li>brillo</li></ul> |
| **Height** | <ul><li>height</li><li>mapa de alturas</li><li>desplazamiento</li><li>disp</li></ul> |
| **Metálico** | <ul><li>metálico</li><li>mtl</li><li>metalidad</li></ul> |
| **Normal** | <ul><li>normal</li><li>nrm</li></ul> |
| **Opacidad** | <ul><li>opacidad</li><li>alfa</li></ul> |
| **Rugosidad** | <ul><li>rugosidad</li><li>irregular</li></ul> |
| **Specular** | <ul><li>specular</li><li>especificación</li></ul> |
| **Specular level** | <ul><li>nivel especular</li><li>specular_level</li></ul> |

