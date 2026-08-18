---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/features-and-workflows/export-parametric-assets.html"
breadcrumb-title: ''
description: Aprenda a exportar recursos paramétricos de Substance 3D Sampler para habilitar la modificación de parámetros en otras aplicaciones sin volver a Sampler.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > Export parametric assets
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Exportar recursos paramétricos
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 1%

---


# Exportar recursos paramétricos

Los parámetros expuestos se pueden modificar en otras aplicaciones sin volver a Sampler. Esto reduce el tiempo de iteración, por lo que puede centrarse en encontrar el mejor aspecto sin necesidad de moverse de una aplicación a otra.

## Exponer y desexponer parámetros

Para exponer parámetros, abra el **panel Propiedades**. Pase el ratón o haga clic con el botón derecho en el parámetro deseado y, a continuación, haga clic en el icono de pin o en &quot;exponer este parámetro&quot;.

![](../assets/ezgif-com-gif-maker-2.gif)

Hay dos formas de dejar de exponer un parámetro:

* En el **Panel Parámetros expuestos**, haz clic con el botón derecho en el parámetro y elige &quot;desexponer&quot;.

  ![](../assets/ezgif-com-gif-maker-3.gif)
* En el **panel Propiedades**, haz clic en el icono de chincheta cruzada o haz clic con el botón derecho en el parámetro y elige &quot;desexponer este parámetro&quot;.

  ![](../assets/ezgif-com-gif-maker-4.gif)

No se pueden exponer los parámetros de los siguientes filtros:

* De imagen a material (con tecnología de IA)
* Relleno según el contenido
* Normal al Height
* Ampliar

Si añade uno de los filtros encima de las capas que contienen parámetros expuestos, no se mostrarán en la exportación.\
Para evitarlo, quite el filtro o colóquelo donde no afecte a las capas con parámetros expuestos.

Si ha expuesto los parámetros de una fusión, se perderán si mueve la capa en la parte inferior de la pila.

![](../assets/ezgif-com-gif-maker-10.gif)

## Editar los parámetros

Edita la etiqueta de tu parámetro haciendo clic con el botón derecho en el **Panel Parámetros expuestos**, introduce el nuevo nombre y haz clic en &quot;Aplicar&quot;.

![](../assets/ezgif-com-gif-maker-5.gif)

![](../assets/ezgif-com-gif-maker-6.gif)

Puede usar el parámetro en el **Panel Parámetros expuestos** como en el **panel Propiedades**.

## Exportar el material

Para exportar el material con los parámetros expuestos

1. Abra el panel <b>Exportar.</b>
1. Haga clic en exportar.
1. Seleccione SBSAR o SBS.
1. Haz clic en &quot;exportar&quot;.

Ahora puede utilizar el material con los parámetros expuestos en cualquier software que admita el formato de archivo SBSAR.
