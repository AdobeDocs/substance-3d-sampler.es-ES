---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/old-versions/version-3-1.html"
breadcrumb-title: ''
description: Consulte las notas de la versión 3.1 de Substance 3D Sampler para obtener más información sobre el selector de color, la compatibilidad con SVG y las mejoras en la interoperabilidad.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 3.1
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 3.1
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '791'
ht-degree: 0%

---


# Versión 3.1

Adobe Substance 3D Sampler 3.1 presenta un nuevo selector de color, compatibilidad con archivos de SVG y una interoperabilidad mejorada con Stager, Photoshop y Illustrator.

Fecha de publicación: *28 de septiembre de 2021*

## Funciones principales

### Selector de color

Esta versión agrega un nuevo [Selector de color](../../interface/tools-and-widgets/color-picker.md) que incluye un cuentagotas y compatibilidad con muestras.

El Selector de color aparece siempre que necesita seleccionar un color. Se puede mover a cualquier lugar de las pantallas.

![](../../assets/color-picker-raw.png){width="250px"}

### Compatibilidad con SVG

Sampler ahora admite archivos de SVG. Puede importarlos en sus activos, directamente en la pila de capas o en una entrada de imagen de capa.

![](../../assets/svg-support.jpg){width="500px"}

### Editar en Illustrator

Una nueva función de &quot;editar en&quot; aporta una gran flexibilidad a la actualización de imágenes importadas. Si quieres retocar tu archivo de SVG, puedes editarlo directamente en Illustrator. Sampler actualizará instantáneamente tu imagen con el nuevo SVG.

### Nueva interfaz de usuario y experiencia de usuario de recorte

Sampler ahora obtiene un widget de recorte adecuado y rediseñado para definir fácilmente el área recortada. También obtendrá resultados no ampliados al recortar imágenes no cuadradas en texturas cuadradas.

![](../../assets/crop-9.jpg){width="500px"}

### Formato de normales

Edita tus preferencias para establecer el [formato normal](../../interface/preferences/normal-format.md) que necesitas para tu flujo de trabajo. Las normales se importarán, mostrarán y exportarán en el formato seleccionado en las preferencias.

![](../../assets/7-normal-format-preferences.jpg){width="250px"}

### Exportación de propiedades de materiales en SBSAR

Todos los parámetros de material de los ajustes de sombreado (escala normal, escala de height, nivel de height, etc.) se exportará en el archivo SBSAR para leerlo en Substance 3D Stager y obtener una coincidencia de material perfecta.

![](../../assets/material-consistency-sa-sg.jpg){width="500px"}

## Notas de la versión

### 3.1.0 Xocoalt

*(Publicado El 28 De Septiembre De 2021)*

**Agregado:**

* [Selector de color] Nueva interfaz de usuario del selector de color
* [Selector de color] Previsualizar los colores actual y anterior en paralelo
* [Selector de color] Introducir el color en hexadecimal
* [Selector de color] Nuevo cuentagotas con previsualización de color
* [Selector de color] El cuentagotas puede seleccionar un color fuera de Sampler
* [Selector de color] Retoca el color en espacios de color de RGB o HSV
* [Selector de color] Guardar y administrar muestras
* [Interoperabilidad] Edición de imágenes en Illustrator desde la capa de importación de imágenes o desde los parámetros de imagen
* [Interoperabilidad] Edición de imágenes en Photoshop desde la capa de importación de imágenes o desde los parámetros de imagen
* [Widget] Nuevo widget de recorte
* [Widget] Pulse Intro para validar el recorte
* [Widget] El widget Recortar lee el tamaño de la imagen para que se ajuste al widget y mantiene la proporción al cambiar el tamaño
* [UI] Nueva interfaz de usuario del regulador de escala de grises
* [Aplicación] Añadir la selección de formato normal en las preferencias
* [Aplicación] El formato normal de las capas de importación de imágenes sigue el formato normal predeterminado establecido en las preferencias
* [Aplicación] En la vista 2D, la normal se muestra según el formato normal definido en las preferencias
* [Aplicación] La normal se exporta en el formato normal definido en las preferencias
* [Exportar] Añadir parámetros de formato normal a las exportaciones de archivos SBSAR y SBS
* [Exportar] Añadir configuración de sombreado a exportaciones de archivos SBSAR y SBS
* [Exportar] Establezca la resolución predeterminada de los gráficos SBS exportados
* [Filtros compuestos] Empaquetar filtros SSA con 7z
* [Filtros compuestos] Añadir metadatos de categoría en filtros compuestos
* [Filtros compuestos] Los filtros compuestos pueden tener una miniatura incrustada
* [Filtros compuestos] Se ha añadido la extensión Filtros compuestos (.ssafilter) al cuadro de diálogo Obtener archivo de contenido
* [Filtros compuestos] Importar filtros compuestos (.ssafilter) en el panel Activos
* [Motor] Actualice el motor de substance a la versión 8.2.0

**Corregido:**

* [Aplicación] Las carpetas locales conectadas pueden bloquearse
* [Application] Bloqueo al salir
* [Aplicación] Bloqueo al iniciar dos instancias de Sampler
* [Contenido] El filtro Recortar tiene un ajuste aleatorio de la velocidad
* [Contenido] A veces, algunos materiales de Substance no se actualizan
* [Export] Bloqueo al exportar con un ajuste preestablecido personalizado recién añadido
* [Exportar] Falta el tamaño estimado del paquete en la ventana emergente de exportación
* [Exportar] Se ha corregido la pérdida de memoria al exportar archivos SBS y SBSAR
* [Filtros compuestos] Los filtros compuestos pueden tener entradas duplicadas
* [Filtros compuestos] Bloqueo si un filtro tiene referencias no satisfechas
* [Filtros compuestos] Bloqueo al reordenar una pila de capas con un filtro compuesto
* [Filtros compuestos] El procesamiento a veces se bloquea
* [Importación de imágenes] Importar una imagen activa varias representaciones
* [Layers] Bloqueo al deshacer/rehacer
* [Layers] Bloqueo al añadir un Material base
* [Layers] Bloqueo al utilizar una imagen no válida como luz ambiental
* [Capas] Corrección de la importación duplicada al insertar un filtro con varios gráficos
* [Capas] Reordenar capas no siempre funciona
* [Project] Bloqueo al cargar un archivo de proyecto incompleto
* [Project] Bloqueo al abrir un proyecto dañado
* [Project] Algunos recursos pueden desaparecer de un proyecto
* [Propiedades] Corregir los ajustes preestablecidos de filtros que faltan
* [UI] No se pueden establecer parámetros de ángulo
* [UI] Visualización de metadatos de filtros en el panel Activos
* [UI] Agrupar por categoría oculta filtros
* [IU] Problema de desplazamiento en el panel Activos
* [UI] El panel Exportar ahora tiene una barra de desplazamiento
* [UI] La miniatura no se muestra para algunos formatos de imagen en el selector de imágenes

**Problemas conocidos:**

* [Realtime Engine 2021] El cálculo intenso puede bloquear la aplicación
* [Realtime Engine 2021] Realtime Engine 2021 se bloquea en un equipo Windows con CPU AMD y GPU NVIDIA instaladas
* [Selector de color] Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
