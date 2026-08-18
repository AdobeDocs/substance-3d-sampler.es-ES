---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/getting-started/export/managing-custom-presets.html"
breadcrumb-title: ''
description: Aprende a crear y editar ajustes preestablecidos de exportación personalizados en Substance 3D Sampler con Substance Designer para la optimización del flujo de trabajo.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Managing custom presets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Creación y edición de ajustes preestablecidos personalizados
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 1%

---


# Creación y edición de ajustes preestablecidos personalizados

Los ajustes preestablecidos personalizados se pueden crear con Substance 3D Designer.

La creación de ajustes preestablecidos personalizados respeta las mismas reglas que la creación de un filtro personalizado para Sampler. La documentación está disponible [aquí](../../filters/custom-filters.md).

## Creación

## Crear el gráfico

Abra Substance Designer y cree un nuevo gráfico de Substance.

Abra las propiedades del gráfico y rellene la siguiente información obligatoria:

* Etiqueta: Introduzca el nombre del ajuste personalizado que se utilizará en la interfaz de Sampler
* Datos de usuario: <b>alchemist::type=filter</b>

## Definición de entradas y salidas

### Entradas

Las entradas representan los canales de materiales que desea transformar antes de la exportación.

Crea un nodo de color de entrada (o escala de grises) por canal de material y añade un <b>uso</b> en los atributos de cada nodo de entrada para asegurarte de que hay una conexión entre tus materiales y tu ajuste preestablecido personalizado.

Ejemplo: Definición de la entrada de color base

![](../../assets/custom-input.png){width="600px"}

### Salidas

Los resultados representan el resultado de la exportación de textura.

Cree un nodo de salida por textura y agregue <b>usage</b> y una <b>label</b> en los atributos a cada nodo de salida. La <b>etiqueta</b> se mostrará en la lista Canales de la ventana del exportador y en el nombre del archivo de textura.

Ejemplo: Definición de la textura personalizada Color Opacidad

![](../../assets/custom-output.png){width="600px"}

#### Ejemplo de empaquetado de canal y conversión de canal

Empaquetado de 3 canales en escala de grises en una textura RGB:

![](../../assets/channel-packing-example.png){width="600px"}

Conversión de canal de PBR Metallic/Roughness a PBR Specular/Glossiness:

![](../../assets/channel-conversion.png){width="600px"}

## Importar

Para importar el nuevo ajuste preestablecido:

1. Haga clic en el botón <b>Administrar ajustes preestablecidos </b>situado a la derecha de la lista desplegable <b>Ajustes preestablecidos</b>.
1. Usa el botón <b>Importar ajustes preestablecidos</b> situado en la parte inferior de la <b>lista de ajustes preestablecidos</b>.

![](../../assets/Managing-presets-Dropdown.png.img.png){width="400px"}
