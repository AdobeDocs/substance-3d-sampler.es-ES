---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-4substance-3d-sampler.html"
breadcrumb-title: ''
description: Consulte las notas de la versión 4.4 de Substance 3D Sampler para obtener más información sobre los flujos de trabajo generativos, incluidas las funciones de texto a textura y de imagen a textura.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 4.4
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---


# Versión 4.4

<b>Substance 3D Sampler 4.4</b> presenta tres nuevos flujos de trabajo generativos como versión beta: Texto a textura, Texto a motivo e Imagen a textura.

<b>Las características de IA generativa solo están disponibles en la versión de Adobe</b>, ya que requiere una cuenta de Adobe. Por lo tanto, estas características <b>no están disponibles en Steam</b>.

*Fecha de publicación: 23 de mayo de 2024*

## Text-to-texture

![](../assets/textToTexture_whatNewPanel.png)

La conversión de texto a textura te permite explorar una nueva forma de crear materiales con un <b>mensaje de texto</b>. Puedes crear una textura en mosaico a partir de una descripción de texto detallada y seguir creando a partir del resultado mediante Imagen a material o cualquier filtro de Sampler para que sea exclusivamente tuyo.

## Imagen a textura

![imagen a textura](../assets/imagetoText_whatNewPanel.png "Imagen a textura")

Con Image-to-texture puedes crear texturas cuadradas en mosaico a partir de <b>tu propia imagen de referencia</b>, sin importar si no es cuadrada o no es de mosaico. De este modo, se acerca a los resultados deseados sin necesidad de escribir el mensaje perfecto.\
La conversión de imagen a textura también puede ayudarte a ahorrar tiempo creando variaciones a partir del contenido que ya has creado.

## Texto a patrón

![imagen de ilustración de texto a patrón](../assets/patterns_whatNewPanel.png)

La función Texto a patrón usará el símbolo del sistema de texto <b></b> para generar un patrón de mosaico cuadrado. A continuación, puede utilizarlo como el color base con un filtro de tejido de tela para crear un material de tela original, utilizarlo como entrada de un filtro de patrón y más!

## Nota de la versión

*(Lanzado: 23 de mayo de 2024)*

<b>Agregado</b>:

* La caché de captura 3D de [aplicación] ahora se almacena en una subcarpeta independiente
* [IA generativa] Imagen a textura (beta)
* [Generative AI] Conversión de texto a patrón (Beta)
* [IA generativa] Conversión de texto a textura (beta)
* [Scripting] Los recursos ahora tienen una propiedad &#39;resource&#39;
* [Scripting] Las capas ahora tienen la propiedad &#39;output\_usages&#39;

<b>Corregido:</b>

* [Aplicación] Bloqueo al abrir un archivo de proyecto dañado
* [Aplicación] Bloqueo cuando el proyecto contiene recursos dañados
* [Aplicación] Bloqueo al desconectar un monitor en Windows
* [Aplicación] Icono de aplicación incorrecto en la barra de tareas de Windows
* [Aplicación] La corrupción del archivo de configuración principal puede provocar la eliminación de archivos
* [Aplicación] Los paneles aparecen delante de las ventanas emergentes
* [Contenido] Los generadores de texturas tienen miniaturas borrosas
* [Exportar] El canal de opacidad generado a partir de una imagen importada se rompe al exportar un archivo .sbs/.sbsar
* [Filters] El aumento de escala puede bloquearse en función de las capas de entrada
* [IA generativa] Posibles bloqueos al recibir resultados inesperados del servicio
* [Scripting] Bloqueo al cargar automáticamente un complemento desde una variable de entorno
* [Scripting] Posible bloqueo al asignar el uso de salida con la API
