---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/release-notes/old-versions/version-0-8-0.html"
breadcrumb-title: ''
description: Consulte las notas de la versión 0.8.0 de Substance 3D Sampler para obtener más información sobre las nuevas funciones, actualizaciones y mejoras.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Old Versions > Version 0.8.0
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 0.8.0
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '400'
ht-degree: 0%

---


# Versión 0.8.0

**Agregado:**

* [Resources] Conecta y duplica tus carpetas de materiales en tus discos locales
* [Recursos] Examine las carpetas de materiales y sus subcarpetas
* [Resources] Separa el panel de recursos materiales en una ventana independiente para ver los recursos a pantalla completa
* [Recursos] Nuevo diseño del panel Recursos para permitir la navegación por carpetas y subcarpetas
* [Resources] Use la ruta de exploración para navegar por sus carpetas
* [Resources] Fuerce la sincronización de su carpeta local con la opción de sincronización a la que se puede acceder haciendo clic con el botón derecho
* [Recursos] Desconectar la carpeta local con la opción Desconectar accesible haciendo clic con el botón derecho
* [Manage] Visualización de etiquetas incrustadas de archivos de Substance
* [Administrar] Agregar, editar y eliminar etiquetas de sus materiales
* [Administrar] Clasificar los materiales
* [Layers] Soporte de salida de panorama
* [Layers] Puede eliminar las entradas de imagen en la capa de importación de imágenes
* [Layers] Selección automática de la nueva capa añadida
* [Capas] Selección automática de la capa inferior después de eliminar una capa
* [UX] Mantenga la visibilidad de los paneles izquierdos al cambiar a otro laboratorio
* [UX] No cree una capa base ni abra la ventana emergente de flujo de trabajo de materiales al importar imágenes en una pila de capas no vacía
* [UI] Nuevo estilo de campo de texto
* [UI] Nuevo estilo de SearchBox
* [UI] Nuevo estilo de encabezado de panel
* [UI] Nuevo estilo de indicador de Ocupado
* [UI] Nuevo estilo de fondo de pila de capas
* [UI] Usar fuente de Adobe Clean
* [UI] Quitar el marcador de posición del icono de cuentagotas del parámetro de entrada de color
* [Rendimiento] Optimización del indicador Ocupado
* [Contenido] Nuevo filtro Generador de motivos
* [Contenido] Nuevo filtro Desenfocar

**Corregido:**

* [Inspire] Se ha solucionado el bloqueo al utilizar más de 10 colores
* [Vista 2D] Se ha corregido la barra de desplazamiento en la lista de canales de la vista 2D
* [Visualizador] Se ha solucionado el bloqueo al importar un mapa de entorno que no es de alimentación de 2.
* [Contenido] Se ha corregido la importación de PNG para el patrón personalizado de filtros de relieve y perforación
* [Exportar] Solución normal y exportación de height de 16 bits por canal
* Corrección de un bucle infinito al importar un material con dos ajustes preestablecidos con el mismo nombre
* Corregir la visualización de rutas de archivo largas en la capa de Material base

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* No se recomienda el cambio de visibilidad rápida de una etapa de Delighter
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a height puede bloquearse en MacOS
* Puede bloquearse aleatoriamente al salir de MacOS
