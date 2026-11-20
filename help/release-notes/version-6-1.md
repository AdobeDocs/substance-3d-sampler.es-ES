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

* &lbrack;Aplicación&rbrack; Nueva forma de notificar advertencias de requisitos mínimos de hardware
* &lbrack;Captis&rbrack; Añada una opción para elegir entre 4 y 8 ángulos de polarización
* &lbrack;Captis&rbrack; Nueva acción rápida Captis
* &lbrack;Exportar&rbrack; Informar correctamente de errores de exportación al usuario
* &lbrack;Exportar&rbrack; Actualizar el ajuste preestablecido de exportación de Unreal Engine 4 (denominado Unreal Engine 5)
* &lbrack;Rendimiento&rbrack; La creación de activos desde el archivo ahora es asincrónica
* &lbrack;Rendimiento&rbrack; Mover carga de trabajo del subproceso principal a los subprocesos de trabajo
* &lbrack;Rendimiento&rbrack; Nuevo modo de rendimiento
* &lbrack;Proyecto&rbrack; Avisar al usuario si falla la operación de guardar el proyecto
* &lbrack;Secuencias de comandos&rbrack; Nuevo método generate_thumbnail para activos y nueva propiedad de tipo para recursos
* &lbrack;Secuencias de comandos&rbrack; Procesamiento de una instantánea de vista 3D en un archivo desde el módulo Python
* &lbrack;UI&rbrack; Al hacer clic en cualquier lugar de una zona de colocación, se abre el cuadro de diálogo del archivo
* &lbrack;UI&rbrack; Accesos directos a herramientas de la barra de navegación izquierda (ecualizar, recortar, segmentar, transformar, reparar, color, ...)
* &lbrack;UI&rbrack; Actualice qt-spectre para obtener los iconos más recientes

## Fijo

* &lbrack;Vista 3D&rbrack; Fijar Desplazamiento de UV y rotación inmediata, eliminar la escala normal para el OpenPBR
* &lbrack;Vista 3D&rbrack; Evite un bloqueo asegurándose de que no se realice ninguna edición del escenario mientras se elimina la ventana gráfica
* &lbrack;Vista 3D&rbrack; Quitar correctamente la información del desplazamiento (height) al cambiar el recurso mostrado
* &lbrack;Vista 3D&rbrack; Actualización correcta del documento al eliminar malla
* &lbrack;Aplicación&rbrack; Garantizar que la superficie siga activa al calcular la información de depuración del filtro dinámico
* &lbrack;Aplicación&rbrack; Corregir bloqueo al salir de Escena
* &lbrack;Aplicación&rbrack; Corregir posibles bloqueos al eliminar un recurso mientras el servicio de base de datos de recursos se cierra
* &lbrack;Aplicación&rbrack; Hacer seguro el subproceso de información de depuración de caché para evitar un bloqueo
* &lbrack;Aplicación&rbrack; Evitar un bloqueo probando que el nodo no es nulo antes de acceder a él
* &lbrack;Aplicación&rbrack; Evitar un bloqueo causado por el acceso al primer elemento de un vector vacío
* &lbrack;Aplicación&rbrack; Evitar un bloqueo en invalidateVisibleIfs
* &lbrack;Aplicación&rbrack; Evitar un bloqueo al crear recursos mientras el servicio de base de datos está cerrado
* &lbrack;Aplicación&rbrack; Evitar condiciones de carrera al salir
* &lbrack;Assets&rbrack; Asegurarse de que los recursos estén correctamente protegidos tras el bloqueo correcto
* &lbrack;Captis&rbrack; Error con valor de intensidad en modo manual
* &lbrack;Captis&rbrack; Impedir que el usuario seleccione una zona más grande de lo que permite el motor
* &lbrack;Configuración de canal&rbrack; Doble aparición de SpecularColor en ASM
* &lbrack;Configuración de canal&rbrack; Corregir el identificador de un uso creado a partir de una cadena
* &lbrack;Contenido&rbrack; problema de opacidad del atlas scatter
* &lbrack;Contenido&rbrack; Falta la función metálica en el filtro de bordado
* &lbrack;Contenido&rbrack; Corregir filtro de perforación
* &lbrack;Contenido&rbrack; Corregir categoría de filtro de estilización y algunas correcciones en el panel de recursos
* &lbrack;Contenido&rbrack; Actualizar filtro de relleno
* &lbrack;Creative Cloud&rbrack; Corregir la ruta de los recursos 3D en Creative Cloud
* &lbrack;Motor&rbrack; Evitar un bloqueo al acceder a los datos del motor mientras se ha cancelado el trabajo
* &lbrack;Exportar&rbrack; Agregar código defensivo para comprobar que el árbol de la estructura no es nulo
* &lbrack;Exportar&rbrack; Código defensivo para evitar bloqueos en SBS generación
* &lbrack;Exportar&rbrack; Activar la salida de usos personalizados, incluso si el motor los conoce
* &lbrack;Exportar&rbrack; Corregir ajustes preestablecidos de exportación
* &lbrack;Exportar&rbrack; Los mapas de normales se exportan como RAW en USD
* &lbrack;Exportar&rbrack; Uso de etiquetas de salida en lugar de usos al exportar con un ajuste preestablecido
* &lbrack;Parámetros expuestos&rbrack; Corregir parámetros expuestos en filtros dinámicos
* &lbrack;Parámetros expuestos&rbrack; Corregir la actualización del parámetro expuesto cuando cambia su nombre
* &lbrack;Filters&rbrack; Asegúrate de que los identificadores de ajustes de los filtros dinámicos sean idénticos en todas las ejecuciones en todas las plataformas
* &lbrack;Filters&rbrack; Ocultar usos no admitidos en la selección de mapa de segmentación automática
* &lbrack;Capas&rbrack; Cambiar la visibilidad de las capas siempre recrea estructuras
* &lbrack;Capas&rbrack; Bloqueo al acoplar un sello de Clonar sobre algo
* &lbrack;Capas&rbrack; Al insertar un generador directamente en la pila, ahora se definen correctamente los ajustes y el nombre del nodo
* &lbrack;Capas&rbrack; Al insertar un generador con Rellenar correctamente, se muestra la textura en el selector
* &lbrack;Localización&rbrack; Corrección del cumplimiento del conjunto de caracteres chino en GB18030
* &lbrack;Proyecto&rbrack; Bloqueo al guardar después de pintar en un sello de Clonar
* &lbrack;Proyecto&rbrack; Asegurarse de que los nombres de sesión y proyecto se guardan realmente
* &lbrack;Proyecto&rbrack; Evitar un bloqueo al guardar un árbol
* &lbrack;Proyecto&rbrack; Ha vuelto a restaurarse un proyecto dañado de la base de datos
* &lbrack;Acciones rápidas&rbrack; Mostrar la selección de imagen emergente cuando no hay ninguna imagen en la pila
* &lbrack;Acciones rápidas&rbrack; Solucionar problemas de acciones rápidas; cancelar una acción rápida ya no cierra el inicio rápido
* &lbrack;Acciones rápidas&rbrack; La importación de texturas pide activar algunos canales y no debería
* &lbrack;Acciones rápidas&rbrack; Evitar un bloqueo si una acción rápida no se carga
* &lbrack;Acciones rápidas&rbrack; Actualizar contenido de acciones rápidas
* &lbrack;Procesando&rbrack; Corregir combineNormalAndHeight para materiales de ASM
* &lbrack;Procesando&rbrack; Corrección de los usos de las texturas mostrables con Vulkan
* &lbrack;Procesando&rbrack; Marcar el árbol como sucio cuando se cambia la salida de uso único
* &lbrack;Procesando&rbrack; Utilice la estructura de referencia correcta para calcular los nodos de árbol que se van a calcular
* &lbrack;Secuencias de comandos&rbrack; No se detenga si se produce un error durante una exportación
* &lbrack;Secuencias de comandos&rbrack; Asegúrese de que import_images() devuelve la capa importada
* &lbrack;Secuencias de comandos&rbrack; La configuración de un ajuste de imagen en una referencia de recurso de imagen falla
* &lbrack;Secuencias de comandos&rbrack; get_filters() no devuelve filtros dinámicos
* &lbrack;Miniatura&rbrack; Corrección de posibles bloqueos al generar miniaturas
* &lbrack;Miniatura&rbrack; Vuelva a crear el generador de miniaturas cuando cambie el diseño
* &lbrack;UI&rbrack; Al cambiar el recurso, se puede establecer la escala de height en el valor máximo del regulador
* &lbrack;UI&rbrack; El dibujo de una textura actualiza el selector de textura en tiempo real
* &lbrack;UI&rbrack; Al entrar en el modo de pantalla completa cuando no está maximizado, ahora se llena toda la ventana
* &lbrack;UI&rbrack; Corregir vínculo roto a la revista Substance
* &lbrack;UI&rbrack; Corregir márgenes emergentes de exportación
* &lbrack;UI&rbrack; Fijar tamaño del título de sección
* &lbrack;UI&rbrack; Corregir error tipográfico en una cadena
* &lbrack;UI&rbrack; El cuadro de diálogo del archivo Linux ahora utiliza el plugin GTK
* &lbrack;UI&rbrack; Evitar el bloqueo al mostrar un emoji
* &lbrack;UI&rbrack; Cambie el nombre de los archivos .ssa por &quot;Archivo de Adobe Substance 3D Sampler&quot; (sin versión ni versión beta)
* &lbrack;UI&rbrack; Restaurar la desaceleración parpadeante al utilizar el ratón
* &lbrack;UI&rbrack; Pequeñas correcciones en el cuadro de diálogo Crear material nuevo
