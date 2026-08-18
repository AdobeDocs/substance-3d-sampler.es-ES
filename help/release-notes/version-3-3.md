---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/release-notes/version-3-3.html"
breadcrumb-title: ''
description: Consulta las notas de la versión 3.3 de Substance 3D Sampler para obtener más información sobre las nuevas herramientas, contenido y funciones de creación de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Release Notes > Version 3.3
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Versión 3.3
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1108'
ht-degree: 0%

---


# Versión 3.3

**Substance 3D Sampler 3.3.0** presenta una serie de nuevas herramientas, contenido y funciones para crear y editar materiales y luces de ambiente con mayor facilidad.

*Fecha de publicación: 17 de mayo de 2022*

## Funciones principales

## Relleno según el contenido

El Relleno según el contenido es una tecnología popular en Adobe Photoshop que se utiliza para eliminar detalles de una imagen manteniendo la integridad del área circundante.

Substance 3D Sampler ahora utiliza la misma tecnología, lo que te permite limpiar los materiales de PBR y las luces del entorno. En los materiales PBR, el Relleno según el contenido se aplica en todos los canales. No es necesario procesar cada canal por separado.

El Relleno según el contenido puede ayudar a eliminar elementos grandes para evitar repeticiones al segmentar un material o eliminar pequeñas imperfecciones en el tejido escaneado.

Al capturar panoramas de 360 grados, es posible que no tenga el control de todos los elementos de la escena y, por lo tanto, tenga que quitar pequeños objetos del suelo, pinturas en una pared o una persona de pie en el fondo. El Relleno según el contenido ahora lo facilita.

## Creación de IBL

### Proyección esférica

La edición de luces de entorno e imágenes 360 puede resultar difícil cuando se muestran como imágenes normales. Todos los elementos están distorsionados, por lo que es casi imposible editarlos. Con la nueva proyección esférica, puedes navegar en 360° y editar con herramientas especializadas como el Nadir patch, el relleno según el contenido y todas las luces de procedimiento sin distorsión. Ahora es más fácil, por ejemplo, editar o limpiar líneas rectas, quitar el trípode de la cámara y colocar las luces de línea perfectamente.

Echa un vistazo al nuevo tutorial para [crear luces de entorno](https://www.youtube.com/watch?v=cfW9IyoTXQ8) con este nuevo modo.

### Regulador de exposición

En la vista 2D, puede modificar temporalmente la exposición para ayudarle a ver mejor los detalles u objetos de las partes subexpuestas o sobreexpuestas del entorno que está editando.

### Ajustes del visor dedicados

La configuración del visor es persistente por tipo de activo (material o luz ambiental). Puede definir la malla, las texturas predeterminadas o el campo de visión de la cámara para cada tipo de recurso, de modo que sea más fácil cambiar de uno a otro para trabajar en el contexto adecuado.

## Widgets mejorados

### Tampón de clonar

Con esta actualización del Tampón de clonar, puede pintar varios trazos de sello con varios orígenes en una sola capa y acceder al historial de sellos en la pila de capas. Además, ahora puede ver el resultado de la marca directamente en la vista previa del pincel antes de pintar. Esto facilita la limpieza de materiales y evita muchas idas y venidas entre vistas.

### Recortar y transformar

Esta actualización introduce nuevos métodos abreviados para la manipulación de los widgets Recortar y Transformar .

### Barra de herramientas Pincel

La nueva interfaz de usuario, similar a los productos de Adobe más recientes como Fresco, le permite mover la barra de herramientas a cualquier lugar de la vista 2D, que se muestra vertical u horizontalmente. Mientras pinta, cambie entre el pincel y el borrador con la tecla E y utilice las nuevas opciones de mosaico para controlar mejor lo que pinta.

## De imagen a material (con tecnología de IA)

### Conservar mosaico

Imagen a material (con tecnología de IA) obtiene una nueva opción: Ahora puede conservar el mosaico de la imagen en mosaico, lo que reduce el tiempo de mosaico del material posterior.

## Interoperabilidad

Enviar materiales a Stager

Ya era posible enviar luces de ambiente a Stager. Ahora puedes enviar tus materiales a Stager en un solo clic, al igual que con Designer y Painter. Gracias a esta función, ya no tendrás que publicar tus materiales y cargarlos en Stager como archivos individuales (se requiere la versión 1.2.0 de Stager con el nuevo gestor de materiales).

## Notas de la versión

### 3.3.0 Calabacín

*(Lanzamiento 17 De Mayo De 2022)*

**Agregado:**

* [Contenido] Nuevo filtro Relleno según el contenido (Windows y Mac)
* [Contenido] El Relleno según el contenido (Content Aware Fill) está trabajando en imágenes, materiales PBR y luces de entorno
* [Contenido] Añada el parámetro &quot;Conservar segmentación&quot; a Imagen a material (con tecnología de IA)
* [Contenido] El filtro Transformación de perspectiva puede mostrar una cuadrícula entre sus cuatro puntos
* [Interoperabilidad] Enviar materiales a Adobe Substance 3D Stager
* [Herramientas] Centrar la transformación pulsando Ctrl al cambiar el tamaño de las herramientas Transformar o Recortar
* [Herramientas] Para bloquear la proporción a un cuadrado, presione Mayús al cambiar el tamaño de las herramientas Transformar o Recortar
* [Herramientas] El cursor del tampón de clonar ofrece una vista previa de lo que se sellará
* [Herramientas] Previsualizar el contenido original en el cursor del Borrador cuando se usa Tampón de clonar
* [Herramientas] Al pulsar Ctrl y hacer clic se crea un nuevo sello en la capa Tampón de clonar
* [Herramientas] Los sucesivos sellos de clonar ahora se agrupan en una sola capa
* [Herramientas] Barra de herramientas de pincel
* [Herramientas] La posición de la barra de herramientas del pincel es persistente durante una sesión
* [Herramientas] Nuevas opciones de mosaico de pinceles por eje
* [Herramientas] Ocultar/mostrar la superposición sobre la vista 2D al pintar
* [Herramientas] Nuevo método abreviado, tecla &quot;X&quot;, para alternar entre Pincel y Borrador
* [Herramientas] Nuevo método abreviado, &quot;[&quot; &quot;]&quot; para cambiar el tamaño del pincel
* [Herramientas] Nuevo método abreviado, tecla &quot;E&quot;, para cambiar el Borrador
* [Vista 2D] Nuevo modo de Proyección esférica al crear luz ambiental
* [Vista 2D] La herramienta Pincel es compatible con el modo de proyección esférica
* La herramienta Posición [2D View] es compatible con el modo de proyección esférica
* [Vista 2D] Se admite la función Deshacer/Rehacer con el modo de proyección esférica.
* [Vista 2D] En Proyección esférica, defina la posición predeterminada para que mire al centro del entorno
* [Vista 2D] Nuevo control de exposición
* [UI] En el panel Propiedades, el ajuste de imagen muestra el origen del contenido (imagen o de una capa)
* [UI] Se ha mejorado el fondo de la lista desplegable de salidas de capa/material
* [UI] Nueva posición de la información de resolución en la vista 2D
* [UI] Nueva información sobre herramientas con métodos abreviados de los controles de navegación de la vista 3D
* [UI] Nueva información sobre herramientas con controles de pincel
* [UI] Nueva información sobre herramientas con métodos abreviados de controles de navegación de proyección
* [Filtros compuestos] Los filtros compuestos controlan las variaciones para trabajar en imágenes, materiales PBR y luces de entorno
* [Filtros compuestos] El orden de los ajustes coincide con el orden de lista de nodos del filtro compuesto
* [Filtros compuestos] Las modificaciones de nodos diferentes con el mismo grupo se combinarán en un solo grupo en el panel Propiedades
* [Aplicación] Tiene una configuración de visor dedicada por tipo de activo

**Corregido:**

* [Aplicación] La aplicación puede bloquearse al cambiar a la vista 2D
* [Aplicación] Solucionar un posible interbloqueo o bloqueo al exportar varias veces
* [Aplicación] Establecer valores predeterminados para los canales coherentes con Substance 3D Designer
* [Aplicación] Al cargar un proyecto no se activa el nuevo cálculo de material
* [Aplicación] Se ha actualizado la dirección URL de la documentación de importación de texturas.
* [Contenido] Al utilizar un filtro compuesto, solicita que se actualice cuando no debería, al volver a cargar
* [Contenido] Los detalles del mapa de height desaparecen al utilizar la fusión de opacidad
* [UI] En el cuadro de diálogo Color, es posible salir del rango utilizando los campos de texto del regulador
* [UI] La lista de uso tiene una barra de desplazamiento vertical inútil

**Problemas conocidos:**

* [Selector de color] Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* [Contenido] El widget de luz de forma no funciona en modo de proyección esférica
* [Interoperabilidad] El material con desplazamiento enviado a Stager perderá los controles de desplazamiento
