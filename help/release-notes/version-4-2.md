---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-4-2.html"
breadcrumb-title: ''
description: Consulta las notas de la versión 4.2 de Substance 3D Sampler para obtener más información sobre la conversión de imágenes a material con tecnología de IA, la función Mejora de IA y los controles de resolución.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 4.2
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '861'
ht-degree: 0%

---


# Versión 4.2

<b>Substance 3D Sampler 4.2</b> presenta una nueva versión con tecnología de IA de <b>Image to Material</b> y una nueva característica de <b>ampliación de IA</b>. Esta versión incluye el control completo de la resolución por capa.

*Fecha de publicación: 5 de septiembre de 2023*

## Imagen a material - Nueva versión

![](../assets/sa_whats-new-screen_v4-2-0_image_to_material.png)

Imagen a material genera canales de material (color base, rugosidad, normal, desplazamiento y metálico) para usted a partir de una sola imagen.

La versión actualizada de Imagen a material mejora la generación de materiales y la gama de materiales admitidos.

Ahora, Image to Material ha sido entrenado en todos los tipos de materiales, generando mejores resultados para Tela, plástico, madera, etc.

La versión actualizada tiene un nuevo parámetro para seleccionar el tipo de material para generar con precisión todos los canales y ajustar automáticamente el rango.

![Substance 3D Sampler con el nuevo filtro de Imagen a material (con tecnología de inteligencia artificial)](../assets/Materia_ScreenShot.png "Imagen a material - Nueva versión")

## Ampliación de IA

![](../assets/F5W_vAHaYAQLsz7.jpg)

Gracias a la nueva capa de ampliación, Sampler mejora las funciones del material o imagen multiplicando por 2 o por 4 la resolución del contenido (material o imagen).

Esto permite aumentar la calidad y el nivel de detalles de las texturas de baja resolución y mantener la coherencia de funciones entre los mapas durante la ampliación de las texturas.

El filtro Ampliación mejora el color base, los canales normales, de height, la rugosidad y los canales metálicos del material.

Para maximizar la calidad de los resultados, se debe utilizar el filtro Upscale en los datos (materiales e imágenes) con su resolución original, sin cambios de resolución previos.

![Filtro de aumento de escala agregado al proyecto de Substance 3D Sampler](../assets/Upscale_Highlighted.png "Filtro de aumento de escala")

## Resolución de capas

![](../assets/sa_whats-new-screen_v4-2-0_layer-resolution.png)

El nuevo sistema de Resolución de capa le permite tener un control total sobre la resolución de cada capa. Una capa toma la resolución del tamaño del documento o las resoluciones de la capa inferior.

La resolución se muestra en cada capa para visualizar fácilmente el impacto de su trabajo en la resolución de su material.

Esto le permite aumentar la calidad de sus materiales, así como el rendimiento mientras trabaja en sus activos.

## Tutoriales

## Nota de la versión

<b>4.2 DORAYAKI</b>

*(Lanzado: 5 de septiembre de 2023)*

<b>Agregado</b>:

* [Contenido] Se han mejorado considerablemente los filtros de Imagen a material (IA) y Delighter
* [Contenido] Nuevo filtro de ampliación
* [Contenido] El filtro Recortar ahora tiene una resolución de salida dinámica.
* [Plantilla de creación de material] Añadir ajuste de tamaño de documento.
* [Plantilla de creación de material] Nuevo botón de alternancia &quot;Añadir un recorte&quot;.
* [Plantilla de creación de material] Nuevo selector &quot;Mejorar material&quot;
* [Plantilla de creación de material] Mostrar tamaño de imagen importado
* [Plantilla de creación de material] Proporcionar comentarios cuando no se pueden utilizar algunas imágenes importadas
* [Plantilla de creación de material] Avisar cuando los tamaños de imagen no sean coherentes
* [Plantilla de creación de materiales] Nuevas advertencias e información sobre herramientas
* [Capas] Muestra la resolución de las capas de la pila de capas
* [Capas] La resolución de cálculo de capa ahora se puede establecer en Tamaño de documento o Tamaño de entrada
* [Capas] Mostrar la resolución de las capas en la pila de capas
* [Capas] Cambie una directiva de resolución de capa a Documento o Entrada de capa cuando corresponda
* [Layers] Advierte al usuario cuando se añade manualmente un filtro Upscale y proporciona cierta documentación
* [Layers] Advierte al usuario al realizar una ampliación lineal y ofrece utilizar el filtro de ampliación
* [Capas] El cálculo de una capa de imagen a material (AI) ahora se puede cancelar más rápido, para mejorar los tiempos de procesamiento al ajustar la pila de capas
* [Capas] El cálculo de una capa de ampliación ahora se puede cancelar más rápido, para mejorar los tiempos de procesamiento al ajustar la pila de capas
* [Exportar] Permite anular la resolución de texturas exportadas
* [Exportar] La lista Canales para exportar ahora está ordenada
* [Exportar] Muestra la resolución del canal en la lista de canales que exportar
* [Aplicación] Nueva preferencia para activar o desactivar las redes neuronales aceleradas por GPU
* [UI] Mejoras en los menús desplegables de resolución
* [UI] Nuevos iconos para los filtros Transformación de malla, Posprocesamiento de malla y Tejido
* [UI] Cambie el nombre del panel &quot;Compartir&quot; a &quot;Exportar&quot;
* [Scripting] Añadir compatibilidad con la resolución de salida de capa a la API de exportación
* [Scripts] Se ha añadido Recortar, Aumentar y Tamaño de documento a la API de importación de imágenes.
* [Onboarding] Nuevos tutoriales
* [Onboarding] Actualización Bienvenida y contenido de las pantallas Novedades
* [Motor] Actualice Substance Engine a la versión 9.0.1

<b>Corregido:</b>

* [captura 3D] Mejorar las opciones de Precisión nombrar en Parámetros de configuración de alineación
* [Aplicación] Importar imágenes con no múltiplo de 16 dimensiones puede producir un bloqueo
* [Aplicación] Bloqueo al duplicar un recurso en el panel Proyecto
* [Aplicación] Bloqueo al cambiar de recursos en el panel Proyecto
* [Contenido] Pintar una máscara personalizada para el filtro Snow no funciona correctamente
* [Parámetros expuestos] Los cambios de parámetros expuestos pueden perderse al cambiar materiales
* [Interoperabilidad] Enviar un material desde el panel Exportar puede producir un bloqueo
* [Capas] El Relleno según el contenido deja de computar al pasar de una entrada de imagen única a una entrada de material
* [Layers] Bloqueo después de duplicar una luz de ambiente que contiene un material
* [Capas] La capa de importación de imágenes muestra un nombre de imagen incorrecto en el panel Propiedades si se ha cambiado el nombre del archivo de imagen
* [Capas] En ocasiones, se muestra un control de número en una capa inactiva
* [Capas] En ocasiones, cambiar el uso de salida de una imagen en una capa de importación de imágenes no funciona
* [Layers] Escrituras en la ventana Plantilla de Creación
* [UI] La información sobre herramientas de incorporación de la ventana gráfica 3D tiene problemas de enfoque
* [UI] El nombre de imagen puede desbordarse si el nombre de archivo es demasiado largo
* [UI] Problemas menores de diseño de la barra de herramientas del pincel al usar el borrador
* [UI] Las cadenas se truncan en algunos idiomas en el panel Ajustes del visor
* [UI] Mientras se muestra la ventana emergente de información sobre herramientas de la ventana, al pulsar &quot;espacio&quot; se crea un nuevo proyecto
