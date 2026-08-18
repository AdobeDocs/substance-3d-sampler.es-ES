---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/release-notes/version-4-1.html"
breadcrumb-title: ''
description: Consulte las notas de la versión 4.1 de Substance 3D Sampler para obtener más información sobre las actualizaciones del filtro Deformación de pintura, el filtro Bordado y las mejoras en la captura 3D.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 4.1
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 4.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '812'
ht-degree: 0%

---


# Versión 4.1

<b>Substance 3D Sampler 4.1.0 </b>presenta nuevo contenido con el filtro <b>Deformación de pintura </b>y una versión mejorada del filtro <b>Bordado </b>. Esta actualización incluye algunas mejoras de captura 3D.

*Fecha de publicación: 28 de marzo de 2023*

## Deformación de pintura

El filtro Deformación de pintura permite deformar materiales dibujando curvas en la vista 2D.\
La opción Enderezar le permite realinear materiales para un flujo de trabajo de mosaico sencillo y sin problemas.

## Bordado

El nuevo generador de bordados le permite crear parches de bordado a partir de un único archivo vectorial de imagen o un dibujo.\
Puede bordar hasta 6 colores y combina varias técnicas de costura.

## Tutoriales

## Nota de la versión

<b>4.1.2 CANNOLI</b>

*(Lanzado: 20 de junio de 2023)*

<b>Corregido:</b>

* [Capas] Pérdida de memoria al ajustar materiales y filtros del Substance que provocan bloqueos

<b>4.1.1 CANNOLI</b>

*(Lanzado: 06 de junio de 2023)*

<b>Agregado</b>:

* [Motor] Actualice Substance Engine a la versión 9.0
* [Interoperabilidad] Enviar objetos 3D a Stager y Painter

<b>Corregido:</b>

* [captura 3D] Las aplicaciones se bloquean cuando falla el procesador del captura 3D
* [captura 3D] Bloqueo cuando no se puede cargar una imagen
* [captura 3D] Bloqueo al alcanzar el paso de reconstrucción de malla
* [captura 3D] Bloqueo al cambiar el tamaño del cuadro delimitador
* [captura 3D] La importación de máscaras siguiendo la convención no asigna la máscara correctamente
* [captura 3D] El procesamiento falla al ajustar el cuadro delimitador
* [captura 3D] El cambio entre la versión y la alternancia de opciones de procesamiento durante el posproceso de Captura 3D es lento
* [captura 3D] El cambio entre versiones durante el paso captura 3D posterior al proceso a veces se interrumpe
* [Aplicación] Bloqueo al inicio
* [Aplicación] Bloqueo al duplicar un material cuyo nombre se ha cambiado
* [Aplicación] Bloqueo al abrir un proyecto .alch heredado sin su carpeta de dependencias
* [Aplicación] Bloqueo al conectar o desconectar una pantalla, el equipo pasa a la suspensión o se accede de forma remota
* [Aplicación] Bloqueos y pérdidas de memoria relacionados con la administración de activos no persistentes
* [Exportar] La selección del formato de material para los tipos de archivos de objetos 3D que incrustan o hacen referencia a texturas debe estar desactivada
* [Exportar] Bloqueo si se produce un error durante la exportación de objetos 3D
* [Export] Bloqueo al exportar un archivo .sbs/.sbsar
* [Export] Bloqueo al importar un ajuste preestablecido personalizado que tiene la misma etiqueta pero no el mismo nombre de archivo
* [Exportar] En ocasiones, la exportación de una luz ambiental a un archivo .sbs/.sbsar no funciona
* [Export] La exportación Gltf/Glb codifica texturas en base64
* El campo de texto de nombre de [Export] no funciona al reenfocar
* [Exportar] Conservar el mosaico no funciona al exportar una capa de imagen a material (con IA) a un archivo .sbs/.sbsar
* [Exportar] Al exportar gltf y reemplazar archivos, la lista de archivos que se van a reemplazar no es correcta
* [Parámetros expuestos] La velocidad aleatoria no funciona en archivos .sbs/.sbsar exportados
* [Capas] El Relleno según el contenido a veces se bloquea cuando se añade por segunda vez
* [Layers] Bloqueo al calcular una pila de capas
* [Capas] La caché de disco de imagen a material (AI) no funciona
* [Layers] Posible bloqueo al ajustar una capa
* [Rendimiento] Pérdidas de memoria
* [Project] Bloqueo al guardar un proyecto
* [Project] Importar el mismo proyecto dos veces seguidas duplica activos
* [UI] Los botones redondeados con solo un icono no se representan correctamente

### 4.1.0 Cannoli

*(Lanzado: 28 de marzo de 2023)*

<b>Agregado:</b>

* [Contenido] Nuevo filtro de bordado
* [Contenido] Nuevo filtro Deformación de pintura
* [UI] Opción Añadir exportación en el menú Archivo
* [captura 3D] El botón Atrás ahora está disponible en el paso de alineación
* [captura 3D] Imágenes Manejar JPEG Orientación EXIF
* [captura 3D] Scripting: nueva propiedad dataset\_info.camera
* [captura 3D] Añada compatibilidad con Linux (consulte la documentación)
* [captura 3D] Verificar el acceso de lectura de las imágenes importadas
* [Onboarding] Learn - 2 nuevos tutoriales (Bordado y Deformación de pintura)
* [Incorporación] Contenido actualizado de novedades

<b>Corregido:</b>

* [captura 3D] Mantener la posición de la cámara al cambiar de versión
* [captura 3D] Fusionar todos los grupos de un objeto en uno solo
* [captura 3D] Se han cambiado las mallas generadas a Original
* [Aplicación] Bloqueo al intentar generar una miniatura de una imagen inexistente
* El icono de papelera de [Assets] no hace nada en el panel Activos
* [Contenido] La actualización de filtros con ranuras de material no funciona del modo esperado
* [Exportar] Posible bloqueo al exportar un recurso con filtros específicos
* [Exportar] Exportación SBS/SBSAR: las capas de importación de imágenes tenían prioridad sobre los parámetros de la imagen
* [Export] El ajuste preestablecido de exportación UE4 no funciona con PNG
* [Layers] Bloqueo al soltar un material y un filtro al mismo tiempo desde el explorador de OS
* [Layers] Bloqueo al arrastrar cualquier archivo SBSAR con cualquier archivo de imagen
* El canal de opacidad del bordado puede ser completamente blanco
* [Localización] El idioma chino se puede mostrar de forma predeterminada en Linux
* [Rendimiento] Se ha corregido un problema de memoria al eliminar una capa de un recurso
* [Project] Posible bloqueo al guardar
* [UI] Añada el espaciado que falta en el botón de menú de la versión
* [UI] El botón Cancelar no se muestra correctamente
* [UI] Desactivación de la animación de los reguladores para los parámetros de posprocesamiento de captura 3D
* [UI] La ventana Plantilla de creación de material no se cierra al hacer clic fuera
* [UI] El descriptor de acceso rápido de filtro se cierra al hacer clic fuera

<b>Problemas conocidos:</b>

* [Selector de color] Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* [Contenido] El widget de luz de forma no funciona en modo de proyección esférica
* [Interoperabilidad] El material con desplazamiento enviado a Stager perderá los controles de desplazamiento
