---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/release-notes/old-versions/version-0-7-0.html"
breadcrumb-title: ''
description: Consulte las notas de la versión 0.7.0 de Substance 3D Sampler para obtener información sobre actualizaciones, mejoras y correcciones de errores.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.7.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 0.7.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 0%

---


# Versión 0.7.0

Fecha de publicación: **2019/06/13**

Añadido:

* [Filters] Accede rápidamente a tus filtros pulsando la barra espaciadora
* [Filtros] Nuevo panel dedicado para administrar, examinar e importar sus filtros
* [Metadatos] Haga clic con el botón derecho en un material para ver sus metadatos.
* [Metadatos] Haga clic con el botón derecho en un material para ver su ubicación en el disco
* [Reguladores] Anime los reguladores al pasar el puntero sobre ellos pulsando Ctrl
* [Reguladores] Detenga y reinicie la animación de los reguladores presionando P
* [Exportar] La exportación SBSAR sigue las directrices del Substance Source
* [Licencia] Activar Substance Alchemist mediante una variable de entorno
* [UX] El cuadro de diálogo Archivo recuerda la última ruta de archivo seleccionada
* [UX] El cuadro de diálogo Carpeta recuerda la última ruta de carpeta seleccionada
* [UI] Actualizar IU del panel Recursos
* [UI] Actualizar IU de la barra de búsqueda
* [UI] Se actualiza el icono Crear material nuevo
* [Ayuda] Las direcciones URL se actualizan al dominio [substance3d.com](http://substance3d.com)
* [Malla] Ahora hay disponible una malla de tela
* [Contenido] Nuevo filtro de corrosión
* [Contenido] Nuevo filtro de oxidación
* [Contenido] Nuevo filtro de musgo
* [Contenido] Nuevo filtro de Dust
* [Contenido] Nuevo filtro de patrón Brickwall
* [Contenido] Nuevo filtro de patrón de Stonewall
* [Contenido] Nuevo filtro de acabado de madera
* [Contenido] Nuevo filtro de acabado metálico
* [Contenido] Nuevo filtro de Snow
* [Content] Nuevo filtro aleatorio
* [Contenido] Ahora puede importar sus texturas directamente en el filtro de Material base

Corregido:

* Solucionar un bloqueo al guardar la pila de capas
* Se puede añadir un valor por encima de 1 en el regulador de rotación de entorno
* No pierda parámetros de fusión cuando una capa de fusión se transforme de una capa de fusión a otra de una capa de material
* Corregir duplicados al generar variaciones de la misma pila de capas varias veces
* Al volver a abrir un material, Alchemist recuerda los rangos modificados (mínimo y máximo) de los reguladores

Problemas conocidos:

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* No se recomienda el cambio de visibilidad rápida de una etapa de Delighter
* La importación de entorno personalizado puede volverse negra
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a height puede bloquearse en MacOS
