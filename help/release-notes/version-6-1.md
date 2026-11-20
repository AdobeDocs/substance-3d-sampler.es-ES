---
description: Consulte las notas de la versión 6.1 de Substance 3D Sampler para obtener más información sobre las nuevas funciones, mejoras y mejoras del flujo de trabajo.
title: Versión 6.1
hold: true
source-git-commit: 99bb504f8dd5c485bf0d208a85cc3825d186c55f
workflow-type: tm+mt
source-wordcount: '1167'
ht-degree: 0%
---

# Versión 6.1

**Kouign amann** (repostería en capas bretona)

![texto alt](../../help/assets/Sampler_splash_large.jpg)

Esta versión presenta el modo Rendimiento, que permite desactivar configuraciones que pueden ralentizar el flujo de trabajo, así como mejoras de estabilidad automáticas que protegen a los usuarios con hardware más ligero.

Las principales características nuevas incluyen:

## Modo de rendimiento

Obtén una experiencia más rápida y flexible en Sampler. El nuevo **modo de rendimiento** reúne todas las configuraciones que pueden ralentizar tu flujo de trabajo: límites de resolución, sombras, calidad de desplazamiento y trazado de trazado. Desactive las funciones que no necesite para mejorar el rendimiento y la capacidad de respuesta.

Más información [*aquí*](https://www.adobe.com/go/substance-3d-sampler-6.1-performance-mode)

![](../assets/v6.1/6_1-Performance_Mode.png)

## Compatibilidad mejorada con máquinas con especificaciones mínimas

Si tu hardware está por debajo de las [especificaciones mínimas](../getting-started/system-requirements.md), Sampler ahora se ajusta automáticamente para mantener las cosas estables. Las funciones que probablemente ralentizan el proceso o provocan un bloqueo se desactivan automáticamente.

Más información [*aquí*](https://www.adobe.com/go/substance-3d-sampler-6.1-low-specs-mode)

![](../assets/v6.1/6_1-Checked.png)

## Notas de la versión 6.1

*(Lanzado: 19 de noviembre de 2026)*

## Añadido

* &amp;lbrack;Aplicación&amp;rbrack; Nueva forma de notificar advertencias de requisitos mínimos de hardware
* &amp;lbrack;Captis&amp;rbrack; Añada una opción para elegir entre 4 y 8 ángulos de polarización
* &amp;lbrack;Captis&amp;rbrack; Nueva acción rápida Captis
* &amp;lbrack;Exportar&amp;rbrack; Informar correctamente de errores de exportación al usuario
* &amp;lbrack;Exportar&amp;rbrack; Actualizar el ajuste preestablecido de exportación de Unreal Engine 4 (denominado Unreal Engine 5)
* &amp;lbrack;Rendimiento&amp;rbrack; La creación de activos desde el archivo ahora es asincrónica
* &amp;lbrack;Rendimiento&amp;rbrack; Mover carga de trabajo del subproceso principal a los subprocesos de trabajo
* &amp;lbrack;Rendimiento&amp;rbrack; Nuevo modo de rendimiento
* &amp;lbrack;Proyecto&amp;rbrack; Avisar al usuario si falla la operación de guardar el proyecto
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nuevo método generate_thumbnail para activos y nueva propiedad de tipo para recursos
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Procesamiento de una instantánea de vista 3D en un archivo desde el módulo Python
* &amp;lbrack;UI&amp;rbrack; Al hacer clic en cualquier lugar de una zona de colocación, se abre el cuadro de diálogo del archivo
* &amp;lbrack;UI&amp;rbrack; Accesos directos a herramientas de la barra de navegación izquierda (ecualizar, recortar, segmentar, transformar, reparar, color, ...)
* &amp;lbrack;UI&amp;rbrack; Actualice qt-spectre para obtener los iconos más recientes

## Fijo

* &amp;lbrack;Vista 3D&amp;rbrack; Fijar Desplazamiento de UV y rotación inmediata, eliminar la escala normal para el OpenPBR
* &amp;lbrack;Vista 3D&amp;rbrack; Evite un bloqueo asegurándose de que no se realice ninguna edición del escenario mientras se elimina la ventana gráfica
* &amp;lbrack;Vista 3D&amp;rbrack; Quitar correctamente la información del desplazamiento (height) al cambiar el recurso mostrado
* &amp;lbrack;Vista 3D&amp;rbrack; Actualización correcta del documento al eliminar malla
* &amp;lbrack;Aplicación&amp;rbrack; Garantizar que la superficie siga activa al calcular la información de depuración del filtro dinámico
* &amp;lbrack;Aplicación&amp;rbrack; Corregir bloqueo al salir de Escena
* &amp;lbrack;Aplicación&amp;rbrack; Corregir posibles bloqueos al eliminar un recurso mientras el servicio de base de datos de recursos se cierra
* &amp;lbrack;Aplicación&amp;rbrack; Hacer seguro el subproceso de información de depuración de caché para evitar un bloqueo
* &amp;lbrack;Aplicación&amp;rbrack; Evitar un bloqueo probando que el nodo no es nulo antes de acceder a él
* &amp;lbrack;Aplicación&amp;rbrack; Evitar un bloqueo causado por el acceso al primer elemento de un vector vacío
* &amp;lbrack;Aplicación&amp;rbrack; Evitar un bloqueo en invalidateVisibleIfs
* &amp;lbrack;Aplicación&amp;rbrack; Evitar un bloqueo al crear recursos mientras el servicio de base de datos está cerrado
* &amp;lbrack;Aplicación&amp;rbrack; Evitar condiciones de carrera al salir
* &amp;lbrack;Assets&amp;rbrack; Asegurarse de que los recursos estén correctamente protegidos tras el bloqueo correcto
* &amp;lbrack;Captis&amp;rbrack; Error con valor de intensidad en modo manual
* &amp;lbrack;Captis&amp;rbrack; Impedir que el usuario seleccione una zona más grande de lo que permite el motor
* &amp;lbrack;Configuración de canal&amp;rbrack; Doble aparición de SpecularColor en ASM
* &amp;lbrack;Configuración de canal&amp;rbrack; Corregir el identificador de un uso creado a partir de una cadena
* &amp;lbrack;Contenido&amp;rbrack; problema de opacidad del atlas scatter
* &amp;lbrack;Contenido&amp;rbrack; Falta la función metálica en el filtro de bordado
* &amp;lbrack;Contenido&amp;rbrack; Corregir filtro de perforación
* &amp;lbrack;Contenido&amp;rbrack; Corregir categoría de filtro de estilización y algunas correcciones en el panel de recursos
* &amp;lbrack;Contenido&amp;rbrack; Actualizar filtro de relleno
* &amp;lbrack;Creative Cloud&amp;rbrack; Corregir la ruta de los recursos 3D en Creative Cloud
* &amp;lbrack;Motor&amp;rbrack; Evitar un bloqueo al acceder a los datos del motor mientras se ha cancelado el trabajo
* &amp;lbrack;Exportar&amp;rbrack; Agregar código defensivo para comprobar que el árbol de la estructura no es nulo
* &amp;lbrack;Exportar&amp;rbrack; Código defensivo para evitar bloqueos en SBS generación
* &amp;lbrack;Exportar&amp;rbrack; Activar la salida de usos personalizados, incluso si el motor los conoce
* &amp;lbrack;Exportar&amp;rbrack; Corregir ajustes preestablecidos de exportación
* &amp;lbrack;Exportar&amp;rbrack; Los mapas de normales se exportan como RAW en USD
* &amp;lbrack;Exportar&amp;rbrack; Uso de etiquetas de salida en lugar de usos al exportar con un ajuste preestablecido
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Corregir parámetros expuestos en filtros dinámicos
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Corregir la actualización del parámetro expuesto cuando cambia su nombre
* &amp;lbrack;Filters&amp;rbrack; Asegúrate de que los identificadores de ajustes de los filtros dinámicos sean idénticos en todas las ejecuciones en todas las plataformas
* &amp;lbrack;Filters&amp;rbrack; Ocultar usos no admitidos en la selección de mapa de segmentación automática
* &amp;lbrack;Capas&amp;rbrack; Cambiar la visibilidad de las capas siempre recrea estructuras
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al acoplar un sello de Clonar sobre algo
* &amp;lbrack;Capas&amp;rbrack; Al insertar un generador directamente en la pila, ahora se definen correctamente los ajustes y el nombre del nodo
* &amp;lbrack;Capas&amp;rbrack; Al insertar un generador con Rellenar correctamente, se muestra la textura en el selector
* &amp;lbrack;Localización&amp;rbrack; Corrección del cumplimiento del conjunto de caracteres chino en GB18030
* &amp;lbrack;Proyecto&amp;rbrack; Bloqueo al guardar después de pintar en un sello de Clonar
* &amp;lbrack;Proyecto&amp;rbrack; Asegurarse de que los nombres de sesión y proyecto se guardan realmente
* &amp;lbrack;Proyecto&amp;rbrack; Evitar un bloqueo al guardar un árbol
* &amp;lbrack;Proyecto&amp;rbrack; Ha vuelto a restaurarse un proyecto dañado de la base de datos
* &amp;lbrack;Acciones rápidas&amp;rbrack; Mostrar la selección de imagen emergente cuando no hay ninguna imagen en la pila
* &amp;lbrack;Acciones rápidas&amp;rbrack; Solucionar problemas de acciones rápidas; cancelar una acción rápida ya no cierra el inicio rápido
* &amp;lbrack;Acciones rápidas&amp;rbrack; La importación de texturas pide activar algunos canales y no debería
* &amp;lbrack;Acciones rápidas&amp;rbrack; Evitar un bloqueo si una acción rápida no se carga
* &amp;lbrack;Acciones rápidas&amp;rbrack; Actualizar contenido de acciones rápidas
* &amp;lbrack;Procesando&amp;rbrack; Corregir combineNormalAndHeight para materiales de ASM
* &amp;lbrack;Procesando&amp;rbrack; Corrección de los usos de las texturas mostrables con Vulkan
* &amp;lbrack;Procesando&amp;rbrack; Marcar el árbol como sucio cuando se cambia la salida de uso único
* &amp;lbrack;Procesando&amp;rbrack; Utilice la estructura de referencia correcta para calcular los nodos de árbol que se van a calcular
* &amp;lbrack;Secuencias de comandos&amp;rbrack; No se detenga si se produce un error durante una exportación
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Asegúrese de que import_images() devuelve la capa importada
* &amp;lbrack;Secuencias de comandos&amp;rbrack; La configuración de un ajuste de imagen en una referencia de recurso de imagen falla
* &amp;lbrack;Secuencias de comandos&amp;rbrack; get_filters() no devuelve filtros dinámicos
* &amp;lbrack;Miniatura&amp;rbrack; Corrección de posibles bloqueos al generar miniaturas
* &amp;lbrack;Miniatura&amp;rbrack; Vuelva a crear el generador de miniaturas cuando cambie el diseño
* &amp;lbrack;UI&amp;rbrack; Al cambiar el recurso, se puede establecer la escala de height en el valor máximo del regulador
* &amp;lbrack;UI&amp;rbrack; El dibujo de una textura actualiza el selector de textura en tiempo real
* &amp;lbrack;UI&amp;rbrack; Al entrar en el modo de pantalla completa cuando no está maximizado, ahora se llena toda la ventana
* &amp;lbrack;UI&amp;rbrack; Corregir vínculo roto a la revista Substance
* &amp;lbrack;UI&amp;rbrack; Corregir márgenes emergentes de exportación
* &amp;lbrack;UI&amp;rbrack; Fijar tamaño del título de sección
* &amp;lbrack;UI&amp;rbrack; Corregir error tipográfico en una cadena
* &amp;lbrack;UI&amp;rbrack; El cuadro de diálogo del archivo Linux ahora utiliza el plugin GTK
* &amp;lbrack;UI&amp;rbrack; Evitar el bloqueo al mostrar un emoji
* &amp;lbrack;UI&amp;rbrack; Cambie el nombre de los archivos .ssa por &quot;Archivo de Adobe Substance 3D Sampler&quot; (sin versión ni versión beta)
* &amp;lbrack;UI&amp;rbrack; Restaurar la desaceleración parpadeante al utilizar el ratón
* &amp;lbrack;UI&amp;rbrack; Pequeñas correcciones en el cuadro de diálogo Crear material nuevo
