---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/release-notes/all-changes.html'
breadcrumb-title: ''
description: Revisa todos los cambios y actualizaciones en las versiones de Substance 3D Sampler para realizar un seguimiento de la evolución y las mejoras de las funciones a lo largo del tiempo.
helpx_description: Sampler > Release Notes > All Changes
title: Todos los cambios
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '24926'
ht-degree: 0%

---


# Todos los cambios

Esta página reagrupa todos los cambios que se han producido en Substance 3D Sampler, desde las nuevas funciones hasta las correcciones de errores.

## Versión 6

### **6.0.2**

*(Lanzado: 25 de junio de 2026)*

**Agregado:**

* &amp;lbrack;Assets&amp;rbrack; Comprobar la versión sbsar y avisar a los usuarios si el motor es demasiado antiguo para leerlo
* &amp;lbrack;Captis&amp;rbrack; Opción Añadir atrás para guardar los pies de ilustración de la fotometría en las preferencias

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; No mostrar con proporción física si el tamaño físico está desactivado
* &amp;lbrack;Análisis&amp;rbrack; Faltan eventos de análisis
* &amp;lbrack;Análisis&amp;rbrack; Evitar que crashpad informe de un bloqueo en el dispositivo vk perdido
* &amp;lbrack;Aplicación&amp;rbrack; No destruya los dispositivos vk al salir para evitar un bloqueo en el controlador nvidia
* &amp;lbrack;Aplicación&amp;rbrack; Corregir salida del Observador de colecciones vinculadas + Administrador de canales
* &amp;lbrack;Aplicación&amp;rbrack; Evitar un bloqueo al salir
* &amp;lbrack;Contenido&amp;rbrack; El filtro de &quot;acabado metálico&quot; no afecta al metal
* &amp;lbrack;Contenido&amp;rbrack; Añadir tamaño físico a los filtros dinámicos en los que falta
* &amp;lbrack;Filters&amp;rbrack; Quitar el relleno según el contenido de la lista de activos ocultos
* &amp;lbrack;Capas&amp;rbrack; Al hacer clic en Restablecer todos los ajustes, no se restablece el menú desplegable &quot;Se aplica a&quot;
* &amp;lbrack;Capas&amp;rbrack; Corrección de los ajustes mínimo y máximo para el widget de posición
* &amp;lbrack;Capas&amp;rbrack; Actualizar correctamente el filtro
* &amp;lbrack;Tamaño físico&amp;rbrack; Asegúrate de que la escala física funciona en todas partes + haz que el tamaño físico sea adecuado con filtros dinámicos
* &amp;lbrack;Proyecto&amp;rbrack; Asegúrese de que la resolución del recurso sea la predeterminada (2k x 2k) al crear un recurso nuevo
* &amp;lbrack;Proyecto&amp;rbrack; Volver a abrir el proyecto actual utilizado para abrir la versión anterior
* &amp;lbrack;Proyecto&amp;rbrack; Sampler ya no ofrece la restauración de una copia de seguridad de los proyectos dañados
* &amp;lbrack;Procesando&amp;rbrack; Procesamiento de miniaturas de material con una resolución máxima de 2k
* &amp;lbrack;UI&amp;rbrack; Código defensivo para evitar el bloqueo si el usuario es más rápido que la IU

### **6.0.1**

*(Lanzado: 21 de mayo de 2026)*

**Agregado:**

* &amp;lbrack;Aplicación&amp;rbrack; Advertir al usuario al abrir un proyecto con objetos 3D o luces de entorno
* &amp;lbrack;Captis&amp;rbrack; Haz que la interfaz de usuario se adapte a pantallas pequeñas
* &amp;lbrack;Captis&amp;rbrack; Actualizar IU de mayúsculas
* &amp;lbrack;Configuración de canal&amp;rbrack; Activar automáticamente SSS al utilizar el canal de SSS en ASM
* &amp;lbrack;Motor&amp;rbrack; Actualizar Substance Engine a la versión 9.4.3
* &amp;lbrack;Preset&amp;rbrack; Active &#39;Aplicar valores de miniatura preestablecidos&#39; de forma predeterminada
* &amp;lbrack;Resources&amp;rbrack; Mostrar &quot;todas las bibliotecas&quot; de forma predeterminada en lugar de &quot;activos de inicio&quot; en el panel de recursos
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Adición de funciones de Python para gestionar la aplicación a una capa
* &amp;lbrack;UI&amp;rbrack; La lista de activos ahora es interactiva: el tamaño del activo se adapta al contenedor
* &amp;lbrack;UI&amp;rbrack; Mostrar vista 3D/2D de forma predeterminada
* &amp;lbrack;UI&amp;rbrack; Mostrar la optimización de materiales emergente al soltar un material del explorador
* &amp;lbrack;UI&amp;rbrack; Activar la inversión de botones de la barra del dispositivo

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; Solucionar problemas de espacio de color
* &amp;lbrack;Aplicación&amp;rbrack; Fijar actualizador de configuración
* &amp;lbrack;Aplicación&amp;rbrack; Activar los canales de digitalización cuando están configurados en automático
* &amp;lbrack;Aplicación&amp;rbrack; El botón Nuevo proyecto de la pantalla de inicio ya no borra el proyecto anterior con el mismo nombre
* &amp;lbrack;Aplicación&amp;rbrack; Evitar un bloqueo al salir de macOS
* &amp;lbrack;Aplicación&amp;rbrack; Impedir el acceso al recurso de referencias de recursos no válidas
* &amp;lbrack;Aplicación&amp;rbrack; Evitar el bloqueo al acceder a la superficie desde VersionedImage en un ajuste
* &amp;lbrack;Aplicación&amp;rbrack; Evitar el bloqueo al eliminar un escenario cuando no hay ninguno
* &amp;lbrack;Captis&amp;rbrack; Asegúrese de que Captis esté desconectado antes de cerrar Sampler
* &amp;lbrack;Captis&amp;rbrack; Evitar que se muestre dos veces la advertencia de USB-2
* &amp;lbrack;Configuración de canal&amp;rbrack; Corregir nombres de canal de OpenPBR
* &amp;lbrack;Configuración de canal&amp;rbrack; Actualización de etiquetas largas para canales de OpenPBR
* &amp;lbrack;Contenido&amp;rbrack; Actualizar todas las unidades de malla de metros a centímetros para los valores de SSS
* &amp;lbrack;Exportar&amp;rbrack; Asegúrese de que los valores predeterminados estén conectados a filtros dinámicos
* &amp;lbrack;Exportar&amp;rbrack; Las imágenes ahora se guardan en un subproceso de trabajo para mejorar el rendimiento
* &amp;lbrack;Filters&amp;rbrack; El Relleno según el contenido se bloquea al activar la escala
* &amp;lbrack;Filters&amp;rbrack; No se pudo abrir la ubicación de un filtro dinámico desde el panel de recursos
* &amp;lbrack;Filters&amp;rbrack; Corregir restablecimiento de todo en el paso de ajuste de segmentación automática
* &amp;lbrack;Filters&amp;rbrack; Restaurar y deshabilitar el procesamiento de uso en la creación de estructuras de árbol
* &amp;lbrack;Filters&amp;rbrack; Establecer el valor predeterminado correcto para el parámetro de aumento de escala
* &amp;lbrack;Filters&amp;rbrack; Actualizar generadores aunque estén en una capa de relleno
* &amp;lbrack;Capas&amp;rbrack; Prohibir cambiar el nombre de las capas de encabezado o marcador de posición de capa de entrada
* &amp;lbrack;Capas&amp;rbrack; Evitar el bloqueo durante la inserción de capas debido a un puntero que cuelga
* &amp;lbrack;Capas&amp;rbrack; Número incorrecto de imágenes en el nombre de la capa de acoplado
* &amp;lbrack;Localización&amp;rbrack; Asegúrese de que los nombres de los ajustes preestablecidos se actualicen al cambiar de idioma
* &amp;lbrack;Localización&amp;rbrack; Varios problemas de traducción en el panel de recursos
* &amp;lbrack;Localización&amp;rbrack; Acciones rápidas categorías problemas de localización
* &amp;lbrack;Rendimiento&amp;rbrack; Cargar ajustes solo en la sección abierta
* &amp;lbrack;Preferencias&amp;rbrack; Al borrar la ruta de caché de preferencias se restablece el valor anterior
* &amp;lbrack;Procesando&amp;rbrack; Pérdida de memoria al utilizar el rastreador de trazado
* &amp;lbrack;Procesando&amp;rbrack; Evita eliminar texturas mientras Vulkan todavía pueda acceder a ellas
* &amp;lbrack;Procesando&amp;rbrack; La rotación de textura no se convirtió de 0-1 a 0-360
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Quitar clases no existentes de la documentación de Python
* &amp;lbrack;Secuencias de comandos&amp;rbrack; selectedAsset devuelve None si no hay ningún activo seleccionado
* &amp;lbrack;Herramientas&amp;rbrack; Al restablecer un valor de textura, ahora se deja de pintar y se borra la vista de parches
* &amp;lbrack;UI&amp;rbrack; No cierre las secciones del panel Propiedades siempre que se modifique algo
* &amp;lbrack;UI&amp;rbrack; Etiqueta de ajuste de color expuesta invisible al pasar el cursor
* &amp;lbrack;UI&amp;rbrack; Corregir el comportamiento interactivo de la lista de activos
* &amp;lbrack;UI&amp;rbrack; Corregir el bucle de enlace en la información sobre herramientas de AssetItem
* &amp;lbrack;UI&amp;rbrack; Corregir doble clic en el grupo de ajustes preestablecidos seleccionado
* &amp;lbrack;UI&amp;rbrack; Corregir área de colocación en el presentador de imágenes
* &amp;lbrack;UI&amp;rbrack; Corregir etiqueta con un botón para todos los idiomas
* &amp;lbrack;UI&amp;rbrack; Corregir height de línea para japonés en la ventana emergente de lista de canales
* &amp;lbrack;UI&amp;rbrack; Corregir el campo de la señal de longitud Aceptada
* &amp;lbrack;UI&amp;rbrack; Corregir ancho emergente con elemento de control izquierdo largo
* &amp;lbrack;UI&amp;rbrack; Corregir la ventana emergente de previsualización en elementos de activo
* &amp;lbrack;UI&amp;rbrack; Corrección de un selector rugoso/reflectante
* &amp;lbrack;UI&amp;rbrack; Corregir puntos suspensivos de cadena
* &amp;lbrack;UI&amp;rbrack; Solucionar problema de truncamiento de cadena
* &amp;lbrack;UI&amp;rbrack; Botón de restablecimiento del ajuste del interruptor de reparación
* &amp;lbrack;UI&amp;rbrack; Ocultar la lista desplegable de Modelos de material cuando se selecciona un ajuste preestablecido de exportación personalizado
* &amp;lbrack;UI&amp;rbrack; Eliminar resolución en la lista de canales de la ventana emergente de exportación
* &amp;lbrack;UI&amp;rbrack; El restablecimiento del diseño predeterminado mantiene la configuración del visor de proyección
* &amp;lbrack;UI&amp;rbrack; Restaurar los elementos de menú &quot;Editar en Photoshop&quot; y &quot;Editar en Illustrator&quot;

**Eliminado:**

* &amp;lbrack;UI&amp;rbrack; Quitar la sección &quot;Aplicado a&quot; de las capas de importación de imágenes
* &amp;lbrack;UI&amp;rbrack; Quitar la información sobre herramientas de acción rápida de apertura automática la primera vez que se inicia

## Versión 5

### **5.1.3 ÎLE FLOTTANTE**

*(Lanzado: 6 de enero de 2026)*

**Agregado:**

* &amp;lbrack;Captis&amp;rbrack; Mostrar una advertencia si el firewall ha desactivado el protocolo FTP

**Corregido:**

* &amp;lbrack;Captis&amp;rbrack; Abortar durante una captura puede producir errores
* &amp;lbrack;Captis&amp;rbrack; Al descargar los resultados al final de una captura, se utiliza mucha RAM
* &amp;lbrack;Captis&amp;rbrack; Ejecutar un enfoque automático inmediatamente después de una intensidad automática puede producir errores
* &amp;lbrack;Captis&amp;rbrack; Visualización de resultados HDR en el panel Resumen
* &amp;lbrack;UI&amp;rbrack; En algunos casos, el cuadro de diálogo de carpetas en MacOS no selecciona la carpeta correcta

### **5.1.2 ÎLE FLOTTANTE**

*(Lanzado: 20 de noviembre de 2025)*

**Agregado:**

* &amp;lbrack;Aplicación&amp;rbrack; Detectar la pérdida del dispositivo gráfico, avisar al usuario y salir correctamente
* &amp;lbrack;Capas&amp;rbrack; Se han mejorado los mensajes al acoplar capas
* &amp;lbrack;Capas&amp;rbrack; Miniaturas mejoradas para las capas de importación de imágenes y capas acopladas
* &amp;lbrack;Incorporación&amp;rbrack; Contenido de aprendizaje actualizado en la pantalla de inicio
* &amp;lbrack;Proyecto&amp;rbrack; Recuperar el último estado guardado de la sesión antes del bloqueo
* &amp;lbrack;UI&amp;rbrack; Actualización del icono de aplicación

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; Insertar un material en la pila de capas puede producir un bloqueo en macOS
* &amp;lbrack;Aplicación&amp;rbrack; Posible bloqueo con carga pesada en macOS
* &amp;lbrack;Aplicación&amp;rbrack; Posible bloqueo al añadir capas cuando la memoria de vídeo está llena
* &amp;lbrack;Aplicación&amp;rbrack; Posible bloqueo al abrir un proyecto
* &amp;lbrack;Captis&amp;rbrack; Error si el enfoque automático se ejecuta poco después de la calibración de intensidad automática
* &amp;lbrack;Captis&amp;rbrack; Problemas de fiabilidad y rendimiento tras la primera captura
* &amp;lbrack;Captis&amp;rbrack; Ralentizaciones y errores al copiar archivos al final de una captura
* &amp;lbrack;Captis&amp;rbrack; Pérdida de memoria pequeña al consultar información del dispositivo Captis
* &amp;lbrack;Exportar&amp;rbrack; Los parámetros expuestos de varios reguladores producen archivos .sbsar dañados
* &amp;lbrack;Capas&amp;rbrack; El patrón de mosaico automático se restablece a los valores predeterminados al cambiar los recursos
* &amp;lbrack;Capas&amp;rbrack; El color base personalizado predeterminado se muestra en rojo
* &amp;lbrack;Capas&amp;rbrack; Es posible el acoplado parcial de las capas secundarias del Tampón de clonar, lo que provoca problemas de procesamiento
* &amp;lbrack;Capas&amp;rbrack; Posible bloqueo al ajustar una pila de capas mientras el procesamiento está en curso
* &amp;lbrack;Capas&amp;rbrack; Error inesperado en el paso de región de interés de segmentación automática al cambiar los canales de origen
* &amp;lbrack;Proyecto&amp;rbrack; En ocasiones, al crear un material, se crea una miniatura incorrecta
* &amp;lbrack;Acciones rápidas&amp;rbrack; Algunas acciones rápidas tienen un recuento de entradas incorrecto
* &amp;lbrack;UI&amp;rbrack; El botón Grupo de acciones tiene anchos diferentes
* &amp;lbrack;UI&amp;rbrack; El botón Borrar de los campos de texto a veces activa la pérdida de enfoque
* &amp;lbrack;UI&amp;rbrack; Los cuadros combinados y los campos de texto son demasiado grandes
* &amp;lbrack;UI&amp;rbrack; Los iconos y las etiquetas no están alineados correctamente
* &amp;lbrack;UI&amp;rbrack; La etiqueta del campo de nombre está colocada incorrectamente
* &amp;lbrack;UI&amp;rbrack; Las etiquetas de botón Acciones rápidas están alineadas incorrectamente
* &amp;lbrack;UI&amp;rbrack; Los reguladores muestran también los ceros finales

**Eliminado:**

* &amp;lbrack;Inteligencia artificial generativa&amp;rbrack; Eliminación de funciones de IA generativa. *Esta característica se ha quitado de la aplicación y el servicio dejará de funcionar en versiones anteriores de Sampler el 5 de marzo.*

### **5.1.1 ÎLE FLOTTANTE**

*(Lanzado: 18 de septiembre de 2025)*

**Agregado:**

* &amp;lbrack;2D View&amp;rbrack; Ser capaz de alejar más la vista 2D para texturas de alta resolución
* &amp;lbrack;Captis&amp;rbrack; Advertencia a los usuarios sobre problemas al copiar archivos
* &amp;lbrack;Capas&amp;rbrack; Al duplicar una capa, use un número incremental en el nuevo nombre de capa

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; Al pintar trazos después de restablecer todas las propiedades del Tampón de clonar, los trazos creados anteriormente vuelven a aparecer
* &amp;lbrack;Aplicación&amp;rbrack; &quot;¿Desea guardar el proyecto actual?&quot; popup utiliza un nombre de proyecto incorrecto
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir
* &amp;lbrack;Aplicación&amp;rbrack; Posible bloqueo
* &amp;lbrack;Aplicación&amp;rbrack; A veces, se genera una miniatura con un material incorrecto
* &amp;lbrack;Captis&amp;rbrack; En algunos dispositivos, al realizar una digitalización en alta resolución, el mapa de height aparece en negro
* &amp;lbrack;Captis&amp;rbrack; El botón &quot;Iniciar captura&quot; ya no se desactiva cuando no se ha definido ningún nombre de captura y cuando se está ejecutando una calibración
* &amp;lbrack;Exportar&amp;rbrack; Al exportar un archivo .sbsar, la exportación puede fallar sin notificar al usuario
* &amp;lbrack;Filters&amp;rbrack; La pantalla de parámetros avanzados para el filtro Mosaico automático a veces parpadea al ajustar los parámetros
* &amp;lbrack;Filters&amp;rbrack; Los parámetros predeterminados para el filtro Mosaico producen artefactos grises en la salida
* &amp;lbrack;Filters&amp;rbrack; A veces, con entradas de alta resolución, los ajustes avanzados del filtro Mosaico automático no muestran los puntos de patrón individuales
* &amp;lbrack;Filters&amp;rbrack; El tamaño del patrón del parámetro Mosaico automático de tamaño personalizado tiene un valor predeterminado incorrecto
* &amp;lbrack;Capas&amp;rbrack; Problema ocasional de color con el filtro Mosaico automático visible principalmente en materiales rojos
* &amp;lbrack;Capas&amp;rbrack; A veces, añadir capas restablece algunos ajustes a su valor predeterminado
* &amp;lbrack;Tamaño físico&amp;rbrack; La miniatura de los recursos con un tamaño físico tiene una escala de height incorrecta
* &amp;lbrack;UI&amp;rbrack; No se pueden renombrar los parámetros expuestos
* &amp;lbrack;UI&amp;rbrack; Los botones de activación de canal no son cuadrados
* &amp;lbrack;UI&amp;rbrack; Si la etiqueta del regulador es demasiado larga, no se puede acceder al botón Restablecer
* &amp;lbrack;UI&amp;rbrack; Pulsar la tecla de retorno o hacer clic en él no elimina el enfoque de los campos de texto
* &amp;lbrack;UI&amp;rbrack; A veces aparece información sobre herramientas no deseada en el panel Tamaño físico
* &amp;lbrack;UI&amp;rbrack; La vista 3D muestra una malla incorrecta al crear un proyecto vacío
* &amp;lbrack;UI&amp;rbrack; Al exponer una entrada del selector de color, su etiqueta desaparece al pasar el puntero
* &amp;lbrack;UI&amp;rbrack; Al exponer parámetros, el punto de color a veces se coloca incorrectamente

### **5.1.0 ÎLE FLOTTANTE**

*(Lanzado: 7 de agosto de 2025)*

**Agregado:**

* &amp;lbrack;2D View&amp;rbrack; El tamaño del pincel ahora se adapta a la resolución de textura actual
* &amp;lbrack;Vista&amp;rbrack 3D; Alternar la escala de visualización nativa para el procesamiento 3D en las preferencias
* &amp;lbrack;Aplicación&amp;rbrack; Actualización del motor de procesamiento
* &amp;lbrack;Captis&amp;rbrack; Añadir la posibilidad de &quot;hacer cuadrado&quot; durante la previsualización
* &amp;lbrack;Captis&amp;rbrack; Detección automática de tamaños físicos
* &amp;lbrack;Captis&amp;rbrack; La captura de un nuevo material creará un nuevo activo
* &amp;lbrack;Captis&amp;rbrack; Cambiar la selección de resolución en el menú desplegable a píxeles por pulgada o centímetro en lugar de la resolución de píxeles del área máxima
* &amp;lbrack;Captis&amp;rbrack; Ayuda contextual sobre calibración de alineación
* &amp;lbrack;Captis&amp;rbrack; Generar mapa de rugosidad
* &amp;lbrack;Captis&amp;rbrack; Avisar al usuario si faltan los archivos de calibración predeterminados
* &amp;lbrack;Filters&amp;rbrack; Filtro de segmentación automática para escaneos y materiales estructurados
* &amp;lbrack;Filters&amp;rbrack; Nuevo filtro Eliminador de pliegues
* &amp;lbrack;Filters&amp;rbrack; Nuevas funciones del filtro Tampón de clonar
* &amp;lbrack;Filters&amp;rbrack; Nuevas funciones del filtro Ecualizar
* &amp;lbrack;Capas&amp;rbrack; Capacidad para acoplar capas
* &amp;lbrack;Capas&amp;rbrack; Menú contextual al hacer clic con el botón derecho en una capa para cambiar el nombre, duplicar, eliminar o acoplar la capa
* &amp;lbrack;Incorporación&amp;rbrack; Actualizar el contenido de la bienvenida y de las pantallas Novedades
* &amp;lbrack;Rendimiento&amp;rbrack; Mejor rendimiento al utilizar el filtro Recortar
* &amp;lbrack;Rendimiento&amp;rbrack; Mejorar el uso de memoria para la vista 3D
* &amp;lbrack;Rendimiento&amp;rbrack; La actualización de la vista 3D es más rápida
* &amp;lbrack;Tamaño físico&amp;rbrack; Habilitar &quot;visualización con proporción física&quot; al trabajar con filtros de Substance cuando el Tamaño físico está activado
* &amp;lbrack;Tamaño físico&amp;rbrack; Al importar imágenes en una pila vacía, proponga una resolución más coherente con la proporción de imágenes
* &amp;lbrack;Acciones rápidas&amp;rbrack; 3 nuevas acciones rápidas para el procesamiento de digitalizaciones
* &amp;lbrack;Secuencias de comandos&amp;rbrack; API para acoplar capas
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Obtenga el nombre de archivo de cada imagen de una capa de importación de imágenes
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nueva función para activar/desactivar un canal determinado de un activo
* &amp;lbrack;UI&amp;rbrack; Rehacer los iconos y botones del panel Capas para adaptarlos a las nuevas funciones
* &amp;lbrack;UI&amp;rbrack; Advertencia sobre la degradación de la creación de luz ambiental

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; Es posible que la selección de &quot;Mostrar con proporción física&quot; no funcione al utilizar filtros de Substance
* &amp;lbrack;captura 3D&amp;rbrack; Los archivos SVG se muestran en el selector de archivos, pero no son compatibles
* &amp;lbrack;Vista&amp;rbrack 3D; El parámetro de intensidad de emisión de la configuración del sombreado no funciona
* &amp;lbrack;Vista&amp;rbrack 3D; A veces, la posición de la malla es incorrecta al crear un activo nuevo
* &amp;lbrack;Vista&amp;rbrack 3D; El cambio al procesamiento de Path Tracing se bloquea en el hardware no compatible
* &amp;lbrack;Aplicación&amp;rbrack; La aplicación se bloquea al cerrar la ventana emergente de medida manual sin establecer un tamaño
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo en Windows al mostrar el escritorio (tecla Windows + método abreviado de teclado D)
* &amp;lbrack;Aplicación&amp;rbrack; Posible bloqueo al cambiar de idioma
* &amp;lbrack;Captis&amp;rbrack; Bloqueo cuando los datos de la vista previa no son válidos
* &amp;lbrack;Captis&amp;rbrack; No es posible reducir completamente después de aumentar la imagen
* &amp;lbrack;Captis&amp;rbrack; Falta la localización en algunos pasos del asistente
* &amp;lbrack;Captis&amp;rbrack; Posible bloqueo al salir al utilizar Captis
* &amp;lbrack;Captis&amp;rbrack; El análisis no funciona si el dispositivo no tiene archivos de calibración
* &amp;lbrack;Filters&amp;rbrack; La vista previa del pincel al utilizar el filtro Tampón de clonar puede ser incorrecta según la textura y los tamaños de pincel
* &amp;lbrack;Filters&amp;rbrack; Tamaño de salida incorrecto después de utilizar el filtro de aumento de escala
* &amp;lbrack;Filters&amp;rbrack; Faltan iconos para los filtros de rotación de entorno y estilización
* &amp;lbrack;Filters&amp;rbrack; La actualización de algunos filtros puede provocar una representación incorrecta
* &amp;lbrack;Capas&amp;rbrack; Primer procesamiento incorrecto al mezclar dos materiales
* &amp;lbrack;Capas&amp;rbrack; El botón para actualizar capas muestra &quot;Actualizar todo&quot; incluso cuando solo hay una actualización
* &amp;lbrack;Capas&amp;rbrack; Cálculos innecesarios al importar imágenes en la pila de capas
* &amp;lbrack;Rendimiento&amp;rbrack; Mejorar la gestión de formatos de mapa de normales para reducir los tiempos de procesamiento
* &amp;lbrack;Tamaño físico&amp;rbrack; La ventana emergente de medición manual solo funciona después de realizar una medición automática
* &amp;lbrack;Tamaño físico&amp;rbrack; Resolución de exportación incorrecta en el elemento emergente Exportar cuando está activado el Tamaño físico
* &amp;lbrack;Acciones rápidas&amp;rbrack; Falta la localización en los nombres de recursos generados
* &amp;lbrack;UI&amp;rbrack; Es posible que la vista previa del activo al pasar el puntero no se muestre
* &amp;lbrack;UI&amp;rbrack; Al hacer clic en el botón Restablecer el valor predeterminado, se pueden romper algunos de los controles
* &amp;lbrack;UI&amp;rbrack; Los mensajes de error no se borran al cambiar de proyecto
* &amp;lbrack;UI&amp;rbrack; Asegúrese de que el nombre del material en el panel Ventana gráfica y propiedades esté vacío cuando no haya ningún recurso
* &amp;lbrack;UI&amp;rbrack; El botón Restablecer el valor predeterminado para el parámetro de punto de vista no funciona
* &amp;lbrack;UI&amp;rbrack; Superposición del botón Restablecer al valor predeterminado
* &amp;lbrack;UI&amp;rbrack; No se puede hacer clic en algunos botones cuando un panel está desacoplado
* &amp;lbrack;UI&amp;rbrack; Parámetro V de segmentación de texturas parcialmente oculto en Ajustes del visualizador y Vista 3D

**Eliminado:**

* &amp;lbrack;captura 3D&amp;rbrack; Quitar compatibilidad con captura 3D
* &amp;lbrack;Aplicación&amp;rbrack; Quitar la compatibilidad con macOS x86

### **5.0.3 AVELLANA**

*(Lanzado: 3 de junio de 2025)*

**Agregado:**

* &amp;lbrack;Captis&amp;rbrack; Permitir dar a un material el mismo nombre que a uno ya existente
* &amp;lbrack;Captis&amp;rbrack; Mover mensajes de error a ventanas emergentes en lugar de tostadas
* &amp;lbrack;Filters&amp;rbrack; Actualizar bordado
* &amp;lbrack;Preferencias&amp;rbrack; Añadir restablecimiento en la configuración del visualizador y en la configuración de sombreadores
* &amp;lbrack;UI&amp;rbrack; No presente el elemento de menú &quot;Mostrar ubicación&quot; en los recursos del proyecto

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; El filtro tras el proceso de malla no genera los mapas esperados
* &amp;lbrack;Vista&amp;rbrack 3D; La vista 3D no funciona debido a la corrupción de la caché de sombreado
* &amp;lbrack;Vista&amp;rbrack 3D; El plano de tierra y la cuadrícula son verticales cuando la escena es Z arriba
* &amp;lbrack;Vista&amp;rbrack 3D; La malla a veces desaparece
* &amp;lbrack;Aplicación&amp;rbrack; Cerrar la ventana de inicio de sesión al iniciarse sin iniciar sesión a veces bloquea la aplicación
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al denegar el acceso al archivo de configuración de complementos
* &amp;lbrack;Aplicación&amp;rbrack; El material actual no se selecciona al guardar el proyecto
* &amp;lbrack;Aplicación&amp;rbrack; Al restablecer el diseño predeterminado, la resolución se establece en 64x64
* &amp;lbrack;Aplicación&amp;rbrack; Sampler a veces se bloquea al procesar una pila de capas
* &amp;lbrack;Exportar&amp;rbrack; La resolución de exportación se restablece a veces a 64x64
* &amp;lbrack;Exportar&amp;rbrack; A veces no es posible exportar archivos .sbs/.sbsar
* &amp;lbrack;Capas&amp;rbrack; El botón Añadir material base no hace nada cuando el material está vacío
* &amp;lbrack;Capas&amp;rbrack; El mosaico de textura se cambia al duplicar un material
* &amp;lbrack;Tamaño físico&amp;rbrack; La medición automática no funciona si el panel Tamaño físico se ha acoplado antes de importar la imagen
* &amp;lbrack;Secuencias de comandos&amp;rbrack; El complemento de guardado automático está dañado
* &amp;lbrack;UI&amp;rbrack; Espaciado incorrecto en el cuadro de diálogo Exportar
* &amp;lbrack;UI&amp;rbrack; La animación del regulador de los ajustes ya no funciona
* &amp;lbrack;UI&amp;rbrack; Los reguladores no se ajustan a valores enteros cuando es necesario
* &amp;lbrack;UI&amp;rbrack; Se recortan algunos menús desplegables

### **5.0.2 AVELLANA**

*(Lanzado: 22 de abril de 2025)*

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; El botón Atrás de la página de inicio está roto
* &amp;lbrack;Aplicación&amp;rbrack; Sampler a veces no se inicia si hay datos dañados de versiones anteriores en el disco
* &amp;lbrack;Aplicación&amp;rbrack; La imagen importada no aparece en la ventana gráfica ni en la pila de capas
* &amp;lbrack;Captis&amp;rbrack; El campo de dirección IP Captis permanece vacío incluso después de reiniciar Sampler
* &amp;lbrack;Captis&amp;rbrack; La vista previa de cámara interactiva solo funciona cuando el idioma de la aplicación está establecido en inglés
* &amp;lbrack;Exportar&amp;rbrack; Bloqueo durante la exportación &amp;lbrack;Layers&amp;rbrack; A veces, la pintura no funciona en proyectos guardados anteriormente
* &amp;lbrack;Capas&amp;rbrack; Sampler a veces actualiza todas las texturas cuando solo se actualiza un canal
* &amp;lbrack;Capas&amp;rbrack; No es posible utilizar mezclas de materiales en la pila de capas después de actualizar a 5.0.x
* &amp;lbrack;Capas&amp;rbrack; La actualización de un proyecto con una versión anterior de Image to Material (AI) vuelve negro todo el material
* &amp;lbrack;Capas&amp;rbrack; Al intentar importar una imagen no compatible, Sampler crea una capa rota
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Parte de la API de Python no funciona con un proyecto vacío
* &amp;lbrack;UI&amp;rbrack; Los elementos de menú a veces se desbordan en el menú Archivo

### **5.0.1 AVELLANA**

*(Lanzado: 20 de marzo de 2025)*

**Agregado**

* &amp;lbrack;Aplicación&amp;rbrack; Lista actualizada de compatibilidad de controladores gráficos
* &amp;lbrack;Captis&amp;rbrack; Mostrar una ventana emergente cuando las directivas del sistema operativo bloqueen el uso de HP Z Captis
* &amp;lbrack;Acciones rápidas&amp;rbrack; Explicar por qué una acción rápida está desactivada en una información sobre herramientas
* &amp;lbrack;UI&amp;rbrack; Estilo de IU de ventana de informe de bloqueos
* &amp;lbrack;UI&amp;rbrack; Al copiar en el portapapeles, mostrar un brindis para decir que se ha hecho

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; El regulador Exposición no tiene efecto cuando la proyección esférica está desactivada
* &amp;lbrack;2D View&amp;rbrack; Pintar fuera de la textura crea un trazo interrumpido
* &amp;lbrack;2D View&amp;rbrack; El botón de exposición no tiene información sobre herramientas.
* &amp;lbrack;2D View&amp;rbrack; El zoom en el lateral de una imagen no cuadrada no sigue al ratón
* &amp;lbrack;captura 3D&amp;rbrack; captura 3D no funciona en Windows 11 24H2
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al salir de Sampler durante el paso de reconstrucción de la malla
* &amp;lbrack;Vista&amp;rbrack 3D; El tiempo de cálculo a veces se muestra como 0 ms
* &amp;lbrack;Vista&amp;rbrack 3D; Al cambiar la proyección de ortográfica a perspectiva, la ventana gráfica se vuelve gris
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al iniciarse al comprobar las capacidades de la GPU
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo durante la instalación
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir tras hacer clic con el botón derecho en un campo de metadatos
* &amp;lbrack;Aplicación&amp;rbrack; Falta la luz del entorno al abrir un SBSAR desde el explorador de archivos del sistema operativo
* &amp;lbrack;Aplicación&amp;rbrack; Al abrir un archivo .sbsar mientras se ejecuta Sampler, se cambia la configuración de Mosaico de texturas
* &amp;lbrack;Captis&amp;rbrack; Algunos metadatos pueden no transferirse entre los pasos de captura
* &amp;lbrack;Captis&amp;rbrack; El nombre del activo creado no es el introducido en el campo de metadatos
* &amp;lbrack;Contenido&amp;rbrack; En el proyecto de ejemplo se solicita una actualización del filtro, pero ya está actualizado
* &amp;lbrack;Filters&amp;rbrack; Filtro de ajuste normal/height sin icono
* &amp;lbrack;Capas&amp;rbrack; No se pueden cambiar imágenes en una capa de importación de imágenes
* &amp;lbrack;Capas&amp;rbrack; Se bloquea al utilizar el filtro de ampliación
* &amp;lbrack;Capas&amp;rbrack; La actualización de un proyecto con una imagen antigua a Material vuelve negro el material
* &amp;lbrack;Procesando&amp;rbrack; La modificación de una pila de capas inmediatamente después de crear un activo interrumpe el procesamiento
* &amp;lbrack;Secuencias de comandos&amp;rbrack; El plugin de guardado automático se bloquea cuando no hay ningún recurso en el proyecto
* &amp;lbrack;Herramientas&amp;rbrack; Falta el valor de tamaño de pincel en la barra de herramientas Pincel
* &amp;lbrack;UI&amp;rbrack; Al cambiar el idioma de la aplicación no se actualizan algunas de las etiquetas de la pantalla de inicio
* &amp;lbrack;UI&amp;rbrack; Pulsar Escape o Intro en los campos de texto del regulador no perderá el enfoque
* &amp;lbrack;UI&amp;rbrack; En el panel Propiedades, el botón Restablecer todo y la etiqueta de nombre de recurso se superponen
* &amp;lbrack;UI&amp;rbrack; Problemas al acoplar y desacoplar paneles
* &amp;lbrack;UI&amp;rbrack; El desplazamiento en un panel superpuesto también se desplazará en la ventana subyacente
* &amp;lbrack;UI&amp;rbrack; El cambio a la vista de lista en la sección Proyectos recientes de la pantalla de inicio no funciona
* &amp;lbrack;UI&amp;rbrack; El icono del botón del modo de visualización de la ventana siempre muestra 2D/3D

### **5.0.0 AVELLANA**

*(Lanzado: 20 de febrero de 2025)*

**Agregado**

* &amp;lbrack;Incorporación&amp;rbrack; Nueva página de inicio con acceso rápido a contenido de aprendizaje, proyectos de muestra, acciones rápidas y proyectos recientes.
* &amp;lbrack;Incorporación&amp;rbrack; Comenzar rápidamente con las nuevas acciones rápidas, accesibles desde la página de inicio y desde el panel dedicado
* &amp;lbrack;Incorporación&amp;rbrack; &amp;lbrack;Contenido&amp;rbrack; Las acciones rápidas son flujos de trabajo predefinidos que rellenan la pila de capas con la mayoría de las capas utilizadas
* &amp;lbrack;Incorporación&amp;rbrack; Posibilidad de crear un nuevo proyecto mediante un nuevo menú Inicio rápido, acciones rápidas o Proyecto personalizado
* &amp;lbrack;Incorporación&amp;rbrack; Posibilidad de crear un proyecto vacío directamente desde la página de inicio a través del botón dedicado
* &amp;lbrack;Vista&amp;rbrack 3D; Nuevo rasterizador y trazador de trazadores avanzados que aportan nuevas capacidades de representación (propiedades como el revestimiento, el brillo, la translucidez, la dispersión subsuperficial) y coherencia visual en todo el ecosistema Substance
* &amp;lbrack;Vista&amp;rbrack 3D; Ahora se puede acceder directamente a la configuración del visor en la vista 3D
* &amp;lbrack;Vista&amp;rbrack 3D; Posibilidad de guardar una instantánea de procesamiento en el portapapeles o en archivos
* &amp;lbrack;Vista&amp;rbrack 3D; Visualización de una cuadrícula para visualizar el origen de la escena
* &amp;lbrack;Vista&amp;rbrack 3D; Activar el plano de tierra para capturar sombras y reflejos
* &amp;lbrack;Vista&amp;rbrack 3D; Controla lo reflectante y opaco que es tu plano del suelo
* &amp;lbrack;captura 3D&amp;rbrack; Posición de la malla sobre el suelo
* &amp;lbrack;Aplicación&amp;rbrack; Comprobar la compatibilidad del hardware al iniciar la aplicación
* &amp;lbrack;Aplicación&amp;rbrack; Ahora se abre la ventana Informes de fallos justo después de que se produzca un bloqueo
* &amp;lbrack;Contenido&amp;rbrack; Abra un proyecto de muestra para comenzar fácilmente
* &amp;lbrack;Exportar&amp;rbrack; Exportación del sombreador de Adobe Standard Material en archivos USD
* &amp;lbrack;Inteligencia artificial generativa&amp;rbrack; Marque la etiqueta &quot;No inferir&quot; cuando utilice image como entrada en los flujos de trabajo de Imagen a textura
* &amp;lbrack;Proyecto&amp;rbrack; Las miniaturas se almacenan en el archivo de proyecto para abrir los proyectos más rápido
* &amp;lbrack;Proyecto&amp;rbrack; Configuración en las preferencias para almacenar datos de caché dentro del archivo de proyecto, con diferentes modos (sin caché, caché ligera, caché completa)
* &amp;lbrack;Secuencias de comandos&amp;rbrack; &amp;lbrack;Interrumpir cambio&amp;rbrack; Migración de Qt a Qt6.15: compatibilidad de efectos de los plugins existentes
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Los complementos predeterminados y la carpeta de secuencias de comandos ahora se encuentran en la carpeta Documentos
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nueva interfaz de usuario para plugins por coherencia visual con los paneles principales de Sampler
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Acceda a 2 ejemplos de plugins para descubrir las funciones de los plugins de Sampler
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nueva función open_3d_capture()
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Al insertar una capa, controle si se inserta encima o debajo de la posición de destino

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo si no se puede iniciar la captura de objetos en macOS
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir
* &amp;lbrack;Aplicación&amp;rbrack; Colgar al salir al añadir recursos al panel Proyecto
* &amp;lbrack;Aplicación&amp;rbrack; El cambio de nombre de un recurso de proyecto no funciona a menos que pulse Intro
* &amp;lbrack;Aplicación&amp;rbrack; Las entradas de menú Deshacer y Rehacer no se desactivan cuando deberían
* &amp;lbrack;Assets&amp;rbrack; No se pueden eliminar activos de la sección Todas las bibliotecas del panel Activos
* &amp;lbrack;Contenido&amp;rbrack; Atlas creator - Usar mapa de opacidad existente si existe
* &amp;lbrack;Contenido&amp;rbrack; Fusión de ID de color: corrija la selección de color en el color base
* &amp;lbrack;Capas&amp;rbrack; Evite cálculos inútiles al utilizar generadores
* &amp;lbrack;Capas&amp;rbrack; La modificación de un generador puede provocar la activación de demasiados equipos
* &amp;lbrack;Rendimiento&amp;rbrack; Mejorar la administración de memoria de GPU
* &amp;lbrack;Rendimiento&amp;rbrack; La caché de procesamiento no se puede usar al reiniciar la aplicación
* &amp;lbrack;Resources&amp;rbrack; Los archivos de solo lectura no están visibles en el panel Activos
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Permitir reutilizar una capa después de añadir otra
* &amp;lbrack;Secuencias de comandos&amp;rbrack; El cambio de la estructura de la pila de capas varias veces en una secuencia de comandos puede fallar

**Eliminado:**

* &amp;lbrack;Aplicación&amp;rbrack; Quitar la compatibilidad con archivos de imagen .dng y .nef

## Versión 4

### **4.5.2 GRUYERE**

*(Lanzado: 7 de noviembre de 2024)*

**Corregido:**

* &amp;lbrack;Contenido&amp;rbrack; Filtros de mezclas de recortes, bordados y Heightes

### **4.5.1 GRUYERE**

*(Lanzado: 30 de julio de 2024)*

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; La pintura de máscaras de escala de grises no funciona, lo que afecta a herramientas como Tampón de clonar, Deformación de pintura y Relleno según el contenido

### **4.5.0 GRUYERE**

*(Lanzado: 18 de julio de 2024)*

**Agregado**

* &amp;lbrack;Interoperabilidad&amp;rbrack; Enviar materiales a UE5, Blender, Maya, 3DsMax Unity
* &amp;lbrack;Contenido&amp;rbrack; Nueva categoría del generador de texturas - Degradados
* &amp;lbrack;Contenido&amp;rbrack; Herramientas HDRI: nuevo filtro de rotación de entorno

**Corregido:**

* &amp;lbrack;Parámetros expuestos&amp;rbrack; La exposición de valores de entrada .sbsar no funciona
* &amp;lbrack;Capas&amp;rbrack; El color base se vuelve rojo con imágenes en escala de grises
* &amp;lbrack;Procesando&amp;rbrack; Las imágenes en escala de grises utilizadas en canales de color tienen un espacio de color incorrecto
* &amp;lbrack;Secuencias de comandos&amp;rbrack; El uso de un ajuste preestablecido de exportación a veces no exporta los canales esperados
* &amp;lbrack;Contenido&amp;rbrack; Dirt : La aplicación de un filtro de Dirt encima de la imagen al material genera una normal de negro
* &amp;lbrack;Contenido&amp;rbrack; Relieve: la escala de un motivo en el filtro de relieve no es lineal entre 0 y 1
* &amp;lbrack;Contenido&amp;rbrack; Hacer mosaico: Mejora la coherencia normal y de height

### **4.4.1 FONDUE**

*(Lanzado: 6 de junio de 2024)*

**Corregido:**

* &amp;lbrack;Contenido&amp;rbrack; Falta el filtro de dirt
* &amp;lbrack;Inteligencia artificial generativa&amp;rbrack; En ocasiones, se producen errores de red al utilizar Imagen para texturizar

### **FUENTE 4.4.0**

*(Lanzado: 23 de mayo de 2024)*

**Agregado:**

* &amp;lbrack;Aplicación&amp;rbrack; La caché de captura 3D ahora se almacena en una subcarpeta independiente
* &amp;lbrack;Inteligencia artificial generativa&amp;rbrack; Imagen a textura (beta)
* &amp;lbrack;Inteligencia artificial generativa&amp;rbrack; Texto a motivo (beta)
* &amp;lbrack;Inteligencia artificial generativa&amp;rbrack; Texto a textura (beta)
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Los activos ahora tienen una propiedad de recurso
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Las capas ahora tienen la propiedad &#39;output_usages&#39;

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al abrir un archivo de proyecto dañado
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo cuando el proyecto contiene recursos dañados
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al desconectar un monitor en Windows
* &amp;lbrack;Aplicación&amp;rbrack; Icono de aplicación incorrecto en la barra de tareas de Windows
* &amp;lbrack;Aplicación&amp;rbrack; La corrupción del archivo de configuración principal puede provocar la eliminación de archivos
* &amp;lbrack;Aplicación&amp;rbrack; Los paneles aparecen delante de las ventanas emergentes
* &amp;lbrack;Contenido&amp;rbrack; Los generadores de texturas tienen miniaturas borrosas
* &amp;lbrack;Exportar&amp;rbrack; El canal de opacidad generado a partir de una imagen importada se rompe al exportar un archivo .sbs/.sbsar
* &amp;lbrack;Filters&amp;rbrack; La ampliación puede bloquearse en función de las capas de entrada
* &amp;lbrack;Inteligencia artificial generativa&amp;rbrack; Posibles bloqueos al recibir resultados inesperados del servicio
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Bloqueo al cargar automáticamente un complemento desde la variable de entorno
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Posible bloqueo al asignar el uso de salida con la API

### **4.3.3 EMPANADA**

*(Lanzado: 26 de marzo de 2024)*

**Agregado:**

* &amp;lbrack;captura 3D&amp;rbrack; Nuevos parámetros avanzados de UV automático durante el proceso de postproducción
* &amp;lbrack;Filters&amp;rbrack; Filtro de perforación: posibilidad de invertir y cambiar el tamaño del motivo personalizado

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; El color base puede ser incorrecto en macOS
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al procesar una nueva versión
* &amp;lbrack;captura 3D&amp;rbrack; El paso posterior al proceso puede bloquearse en macOS
* &amp;lbrack;captura 3D&amp;rbrack; La capa Transformación de malla puede provocar un procesamiento incorrecto
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al iniciar Sampler mientras una instancia anterior aún se está exportando
* &amp;lbrack;Aplicación&amp;rbrack; Sampler no responde durante un momento cuando se inicia por primera vez
* &amp;lbrack;Exportar&amp;rbrack; El mapa de ángulo de anisotropía no se exporta
* &amp;lbrack;Filters&amp;rbrack; Añadir tejido de tela a la pila de capas puede producir un bloqueo
* &amp;lbrack;Filters&amp;rbrack; Añadir Relieve a la pila de capas puede producir un bloqueo
* &amp;lbrack;Filters&amp;rbrack; El Relleno según el contenido se bloquea al utilizar imágenes de 32 bits
* &amp;lbrack;Filters&amp;rbrack; Relieve: La opacidad de las capas inferiores no se sobrescribe por completo
* &amp;lbrack;Filters&amp;rbrack; Relleno: El modo de fusión no funciona en Designer y Painter
* &amp;lbrack;Filters&amp;rbrack; Bordado: la selección automática de color está rota
* &amp;lbrack;Preferencias&amp;rbrack; Impedir la configuración de una ruta no compatible para la caché de captura 3D
* &amp;lbrack;Preferencias&amp;rbrack; La preferencia Formato normal no funciona
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Los parámetros de los canales de Asset.export_material distinguen entre mayúsculas y minúsculas

### **4.3.2 EMPANADA**

*(Lanzado: 22 de febrero de 2024)*

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; Guardar un proyecto en un recurso compartido de red en Windows daña el archivo del proyecto

### **4.3.1 EMPANADA**

*(Lanzado: 15 de febrero de 2024)*

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo cuando no se puede acceder a los archivos de imagen al generar máscaras por lotes
* &amp;lbrack;Exportar&amp;rbrack; La exportación de un material con Recortar o relativo a la capa de directiva de entrada produce resultados no válidos
* &amp;lbrack;Capas&amp;rbrack; Bloqueo raro al procesar una pila de capas
* &amp;lbrack;Filters&amp;rbrack; Bordado: Se ha solucionado el problema al utilizar la entrada de material en MacOS.
* &amp;lbrack;Filters&amp;rbrack; Estilización - Soporte de los generadores de texturas
* &amp;lbrack;Filters&amp;rbrack; Patrón: corregir nombres de parámetros
* &amp;lbrack;Localización&amp;rbrack; &quot;Guardar como...&quot; en la ventana información de hardware, en el menú ayuda, aparece sin localizar

### **4.3.0 EMPANADA**

*(Lanzado: 25 de enero de 2024)*

**Agregado**

* &amp;lbrack;Assets&amp;rbrack; Nuevo tipo de activo: Generadores de texturas
* &amp;lbrack;Assets&amp;rbrack; Nuevos materiales incluidos en los Activos iniciales
* &amp;lbrack;Assets&amp;rbrack; Nuevo selector de recursos para parámetros de imagen en el panel Propiedades
* &amp;lbrack;Assets&amp;rbrack; Arrastre y suelte los Generadores de texturas del panel Activos en los selectores de imagen del panel Propiedades
* &amp;lbrack;Assets&amp;rbrack; Arrastre y suelte los generadores de texturas desde el explorador de archivos del sistema operativo
* &amp;lbrack;Assets&amp;rbrack; Los filtros pueden sugerir el montaje de generadores mediante una etiqueta de usuario en la entrada de la imagen
* &amp;lbrack;Assets&amp;rbrack; Los generadores de texturas pueden definir qué filtro debe sugerirlas mediante una etiqueta de usuario
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Recorte con perspectiva
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de estilización
* &amp;lbrack;Contenido&amp;rbrack; Modo de fusión en Filtro de relleno
* &amp;lbrack;Contenido&amp;rbrack; Filtro de bordado actualizado
* &amp;lbrack;Contenido&amp;rbrack; Filtro de Ajuste de pintura actualizado
* &amp;lbrack;Contenido&amp;rbrack; Se han actualizado todos los filtros para admitir los generadores de texturas
* &amp;lbrack;Capas&amp;rbrack; Posibilidad de elegir un canal de salida del generador de texturas al añadirlo a la pila de capas
* &amp;lbrack;Capas&amp;rbrack; Posibilidad de enumerar y aplicar fácilmente ajustes preestablecidos en los generadores de texturas
* &amp;lbrack;Capas&amp;rbrack; Visualización de una vista previa del generador de texturas en los selectores de imágenes
* &amp;lbrack;Capas&amp;rbrack; Los parámetros del generador de texturas se pueden exponer y exportar
* &amp;lbrack;Capas&amp;rbrack; Asignar el uso de color base al importar una sola imagen con la plantilla de creación de importación de textura
* &amp;lbrack;Capas&amp;rbrack; Comentarios al intentar arrastrar y soltar archivos incompatibles en los selectores de imágenes del panel Propiedades
* &amp;lbrack;Capas&amp;rbrack; Generar un canal de opacidad a partir del canal alfa de una imagen importada
* &amp;lbrack;Capas&amp;rbrack; La conversión de imagen a material (IA) es más rápida de calcular al cambiar su categoría
* &amp;lbrack;Capas&amp;rbrack; Seleccione la capa más relevante después de utilizar una plantilla de creación
* &amp;lbrack;Capas&amp;rbrack; Los widgets de posición ahora se pueden retocar con un regulador en el grupo Parámetros avanzados
* &amp;lbrack;Exportar&amp;rbrack; Mostrar un porcentaje en la cola en lugar de números RAW
* &amp;lbrack;Interoperabilidad&amp;rbrack; El canal de opacidad ahora se reconoce como canal alfa al enviar a Painter
* &amp;lbrack;Aplicación&amp;rbrack; Nuevo cuadro de diálogo para mostrar y guardar información de hardware
* &amp;lbrack;Aplicación&amp;rbrack; Nueva preferencia para cambiar la escala de height predeterminada de cada proyecto
* &amp;lbrack;Aplicación&amp;rbrack; Mejorar la forma en que se muestran los activos obsoletos
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nuevas funciones asset.documentResolution() y asset.setDocumentResolution()
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nueva función select_asset()
* &amp;lbrack;Secuencias de comandos&amp;rbrack; API de Python para generadores de texturas
* &amp;lbrack;Secuencias de comandos&amp;rbrack; get_project_assets() ahora devuelve objetos 3D
* &amp;lbrack;UI&amp;rbrack; El tamaño de la miniatura del activo se puede cambiar en el panel Activos
* &amp;lbrack;UI&amp;rbrack; Iconos de visualización de ventanilla actualizados

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; El zoom con la rueda del ratón está bloqueado en un 244 %
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al inicio al inicializar la API de gráficos
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo si el nombre del proyecto contiene el carácter #
* &amp;lbrack;Aplicación&amp;rbrack; Posible bloqueo al abrir un proyecto antiguo
* &amp;lbrack;Aplicación&amp;rbrack; Volver a abrir el proyecto actual puede producir un bloqueo
* &amp;lbrack;Aplicación&amp;rbrack; Algunos cambios de proyecto no se registran y se pierden sin avisar al cerrar el proyecto si no se guardan
* &amp;lbrack;Exportar&amp;rbrack; .sbs/.sbsar problemas de exportación al utilizar varios archivos con el mismo nombre
* &amp;lbrack;Exportar&amp;rbrack; Espacio de color incorrecto para el archivo .sbs/.sbsar de imágenes en escala de grises exportado
* &amp;lbrack;Filters&amp;rbrack; Problemas de comportamiento de fusión de opacidad
* &amp;lbrack;Capas&amp;rbrack; En ocasiones, los archivos .svg no se procesan con la resolución correcta
* &amp;lbrack;Rendimiento&amp;rbrack; No es necesario guardar algunos proyectos en disco
* &amp;lbrack;Proyecto&amp;rbrack; La importación de un proyecto antiguo no carga los ajustes preestablecidos asociados
* &amp;lbrack;Secuencias de comandos&amp;rbrack; No se pueden obtener los parámetros de la primera capa insertada
* &amp;lbrack;UI&amp;rbrack; La ventana emergente de vista previa al pasar el cursor sobre un activo puede aparecer en una ubicación o pantalla equivocadas
* &amp;lbrack;UI&amp;rbrack; Los paneles no acoplados son visibles y se pueden utilizar en la parte superior de la pantalla de bienvenida

### **4.2.2 DORAYAKI**

*(Lanzado: 5 de diciembre de 2023)*

**Agregado:**

* &amp;lbrack;captura 3D&amp;rbrack; Ahora captura 3D es entre un 5 % y un 10 % más rápido en Windows
* &amp;lbrack;captura 3D&amp;rbrack; Mejorar la limpieza de la malla antes de la diezmación
* &amp;lbrack;Motor&amp;rbrack; Actualizar Substance Engine a la versión 9.0.3
* &amp;lbrack;Capas&amp;rbrack; Relleno según el contenido: actualización ascendente, varias correcciones de casos de uso y compatibilidad con Linux

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Al hacer clic en &quot;Atrás&quot; después de la alineación, &quot;Siguiente&quot; no se actualiza la nube de puntos
* &amp;lbrack;captura 3D&amp;rbrack; Malla mostrada con taladros después de agregarla al proyecto
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir del modo de pantalla completa después de un Captura 3D
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo con archivos de imagen creados
* &amp;lbrack;Aplicación&amp;rbrack; Si en &quot;Todas las bibliotecas&quot; al salir de Sampler, el panel Activos se vacía al reiniciar
* &amp;lbrack;Aplicación&amp;rbrack; Pérdida de memoria al exportar material
* &amp;lbrack;Aplicación&amp;rbrack; Abrir un proyecto guardado con versiones anteriores de Sampler puede producir un bloqueo
* &amp;lbrack;Aplicación&amp;rbrack; Posibles bloqueos al no convertir mallas 3D
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo silencioso al abrir un archivo .sbsar mientras se ejecuta Sampler
* &amp;lbrack;Exportar&amp;rbrack; Bloqueo al exportar un archivo .sbs/.sbsar con un uso personalizado
* &amp;lbrack;Exportar&amp;rbrack; Los mapas normales exportados siempre son DirectX, independientemente de la configuración del usuario
* &amp;lbrack;Exportar&amp;rbrack; La exportación de un objeto 3D a un archivo FBX en macos no funciona
* &amp;lbrack;Exportar&amp;rbrack; Incoherencias al exportar una pila de capas con un filtro de bordado como archivo .sbs/.sbsar
* &amp;lbrack;Exportar&amp;rbrack; En ocasiones, la exportación de archivos .sbs/.sbsar no funciona
* &amp;lbrack;Exportar&amp;rbrack; A veces, al exportar un archivo .sbs/.sbsar, las imágenes no tienen la profundidad de bits correcta
* &amp;lbrack;Capas&amp;rbrack;  Al hacer invisible una capa de salpicaduras, se procesa su primer secundario
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al cargar la máscara en la capa Brillo/Contraste
* &amp;lbrack;Capas&amp;rbrack; Se muestran mensajes de error engañosos después de eliminar la capa
* &amp;lbrack;Capas&amp;rbrack; Posible bloqueo al degradar un activo
* &amp;lbrack;Capas&amp;rbrack; Algunas salidas no están conectadas a las entradas a menos que el uso sea forzado en el panel Configuración de canal
* &amp;lbrack;Tamaño físico&amp;rbrack; El menú desplegable de capas de referencia se puede restablecer por error
* &amp;lbrack;UI&amp;rbrack; Es necesario actualizar los iconos de importación de información de plantilla
* &amp;lbrack;UI&amp;rbrack; La sugerencia de método abreviado de ventana aparece cada vez que cambia el diseño de la ventana gráfica

### **4.2.1 DORAYAKI**

*(Lanzado: 21 de septiembre de 2023)*

**Agregado :**

* &amp;lbrack;Contenido&amp;rbrack; Imagen a material - Mejorar la generación de microdetalles en mapas normales
* &amp;lbrack;Contenido&amp;rbrack; Imagen a material - Nuevo parámetro de intensidad de iluminación
* &amp;lbrack;Capas&amp;rbrack; Se pueden añadir imágenes en las capas de importación de imágenes
* &amp;lbrack;Capas&amp;rbrack; Las imágenes se pueden eliminar en las capas de importación de imágenes
* &amp;lbrack;Capas&amp;rbrack; Ahora se pueden eliminar capas no válidas
* &amp;lbrack;2D View&amp;rbrack; Mayús + C para retroceder por los canales
* &amp;lbrack;captura 3D&amp;rbrack; Mostrar un aviso cuando el usuario importe menos de 20 imágenes
* &amp;lbrack;Aplicación&amp;rbrack; Nuevas preferencias para definir el valor de mosaico de textura de material por defecto
* &amp;lbrack;Incorporación&amp;rbrack; Interfaz de usuario del tutorial actualizada para Imagen a material (IA) y Ampliación de escala
* &amp;lbrack;Secuencias de comandos&amp;rbrack; API de captura 3D: DatasetInfo tiene más datos cuando Capture3dState está establecido en align
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nuevo argumento select_asset para create_asset(). Nuevas funciones: wait_for_computation() y clear_render_cache()

**Solucionado :**

* &amp;lbrack;Capas&amp;rbrack; Bloqueo cuando la región de recorte es muy pequeña
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al añadir o ajustar el filtro Recortar
* &amp;lbrack;Capas&amp;rbrack; La cuadratura de la región de recorte genera una resolución de salida de material incorrecta
* &amp;lbrack;Capas&amp;rbrack; Las salidas a veces desaparecen cuando varias capas están desactivadas
* &amp;lbrack;Capas&amp;rbrack; Es posible que la caché de procesamiento no se invalide correctamente con los filtros de Imagen a material (AI) y Mejora de escala
* &amp;lbrack;Capas&amp;rbrack; No se puede añadir un filtro de ampliación al seleccionar &quot;No volver a mostrar este mensaje&quot; en la ventana emergente de advertencia
* &amp;lbrack;Capas&amp;rbrack; No se puede restaurar la imagen en el filtro Bordado una vez modificado
* &amp;lbrack;Exportar&amp;rbrack; La resolución de mapa normal exportada cambia al cambiar el formato normal
* &amp;lbrack;Exportar&amp;rbrack; Quitar el sufijo de nombre de archivo &quot;\_environment&quot; al exportar un entorno
* &amp;lbrack;Exportar&amp;rbrack; No se puede exportar un archivo .sbsar cuando hay una capa de transformación de deformación en la pila de capas
* &amp;lbrack;2D View&amp;rbrack; &quot;Ajustar a la pantalla&quot; no funciona cuando cambia la resolución
* &amp;lbrack;Aplicación&amp;rbrack; Después de cerrar la ventana de la aplicación mientras se realiza el cálculo, el proceso de la aplicación podría seguir ejecutándose
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir
* &amp;lbrack;Aplicación&amp;rbrack; Invalidar la caché de procesamiento al alternar redes neuronales aceleradas por GPU
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Asignar un nombre a un complemento como nombre de panel existente provoca comportamientos inesperados
* &amp;lbrack;UI&amp;rbrack; Al hacer clic en un elemento con información sobre herramientas, esta desaparecerá hasta que se reinicie
* &amp;lbrack;UI&amp;rbrack; El valor de escala de heightes puede cambiar al cambiar de recursos
* &amp;lbrack;UI&amp;rbrack; Margen incorrecto en las combinaciones

### **4.2 DORAYAKI**

*(Lanzado: 5 de septiembre de 2023)*

**Agregado:**

* &amp;lbrack;Contenido&amp;rbrack; Se han mejorado enormemente los filtros de imagen a material (IA) y Delighter
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de ampliación
* &amp;lbrack;Contenido&amp;rbrack; El filtro Recortar ahora tiene una resolución de salida dinámica.
* &amp;lbrack;Plantilla de creación de material&amp;rbrack; Agregar configuración de tamaño de documento.
* &amp;lbrack;Plantilla de creación de material&amp;rbrack; Nuevo botón de alternancia &quot;Añadir un recorte&quot;.
* &amp;lbrack;Plantilla de creación de material&amp;rbrack; Nuevo botón deslizante &quot;Mejorar material&quot;
* &amp;lbrack;Plantilla de creación de material&amp;rbrack; Mostrar tamaño de imagen importado
* &amp;lbrack;Plantilla de creación de material&amp;rbrack; Proporcionar comentarios cuando no se puedan utilizar algunas imágenes importadas
* &amp;lbrack;Plantilla de creación de material&amp;rbrack; Avisar cuando los tamaños de imagen no sean coherentes
* &amp;lbrack;Plantilla de creación de material&amp;rbrack; Nuevas advertencias e información sobre herramientas
* &amp;lbrack;Capas&amp;rbrack; Mostrar la resolución de las capas de la pila de capas
* &amp;lbrack;Capas&amp;rbrack; La resolución de cálculo de capa ahora se puede establecer en Tamaño de documento o Tamaño de entrada
* &amp;lbrack;Capas&amp;rbrack; Mostrar la resolución de las capas en la pila de capas
* &amp;lbrack;Capas&amp;rbrack; Cambiar una directiva de resolución de capa a Documento o Entrada de capa cuando corresponda
* &amp;lbrack;Capas&amp;rbrack; Avisar al usuario cuando se añada manualmente un filtro de ampliación y proporcionar documentación
* &amp;lbrack;Capas&amp;rbrack; Advertencia al usuario al realizar una ampliación lineal y oferta utilizar el filtro Ampliación en su lugar
* &amp;lbrack;Capas&amp;rbrack; El cálculo de una capa de imagen a material (AI) ahora se puede cancelar más rápido, para mejorar los tiempos de procesamiento al ajustar la pila de capas
* &amp;lbrack;Capas&amp;rbrack; El cálculo de una capa de ampliación ahora se puede cancelar más rápido, para mejorar los tiempos de procesamiento al ajustar la pila de capas
* &amp;lbrack;Exportar&amp;rbrack; Permitir resolución de sustitución de texturas exportadas
* &amp;lbrack;Exportar&amp;rbrack; La lista Canales para exportar ahora está ordenada
* &amp;lbrack;Exportar&amp;rbrack; Mostrar la resolución del canal en la lista de canales que exportar
* &amp;lbrack;Aplicación&amp;rbrack; Nueva preferencia para activar o desactivar las redes neuronales aceleradas por GPU
* &amp;lbrack;UI&amp;rbrack; Lista desplegable de resolución mejorada
* &amp;lbrack;UI&amp;rbrack; Nuevos iconos para los filtros Transformación de malla, Posprocesamiento de malla y Tejido
* &amp;lbrack;UI&amp;rbrack; Cambiar el nombre del panel &quot;Compartir&quot; a &quot;Exportar&quot;
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Añadir compatibilidad con la resolución de salida de capa a la API de exportación
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Se ha añadido Recortar, Aumentar y Tamaño de documento a la API de importación de imágenes
* &amp;lbrack;Incorporación&amp;rbrack; Nuevos tutoriales
* &amp;lbrack;Incorporación&amp;rbrack; Actualizar el contenido de la bienvenida y de las pantallas Novedades
* &amp;lbrack;Motor&amp;rbrack; Actualizar Substance Engine a la versión 9.0.1

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Mejorar opciones de Precisión Nombrar en Parámetros de ajustes de Alineación
* &amp;lbrack;Aplicación&amp;rbrack; La importación de imágenes con no múltiplo de 16 dimensiones puede producir un bloqueo
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al duplicar un recurso en el panel Proyecto
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al cambiar de recursos en el panel Proyecto
* &amp;lbrack;Contenido&amp;rbrack; Pintar una máscara personalizada para el Snow no funciona correctamente
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Los cambios de parámetros expuestos se pueden perder al cambiar de material
* &amp;lbrack;Interoperabilidad&amp;rbrack; Enviar un material desde el panel Exportar puede producir un bloqueo
* &amp;lbrack;Capas&amp;rbrack; El Relleno según el contenido detiene la informática al cambiar de una entrada de imagen única a una entrada de material
* &amp;lbrack;Capas&amp;rbrack; Bloqueo después de duplicar una luz de entorno que contiene un material
* &amp;lbrack;Capas&amp;rbrack; La capa de importación de imágenes muestra un nombre de imagen incorrecto en el panel Propiedades si se ha cambiado el nombre del archivo de imagen
* &amp;lbrack;Capas&amp;rbrack; En ocasiones, se muestra un control de número en una capa inactiva
* &amp;lbrack;Capas&amp;rbrack; En ocasiones, cambiar el uso de salida de una imagen en una capa de importación de imágenes no funciona
* &amp;lbrack;Capas&amp;rbrack; Tipos de caracteres en la ventana Plantilla de Creación
* &amp;lbrack;UI&amp;rbrack; La información sobre herramientas de incorporación de la ventana gráfica 3D tiene problemas de enfoque
* &amp;lbrack;UI&amp;rbrack; El nombre de imagen puede desbordarse si el nombre de archivo es demasiado largo
* &amp;lbrack;UI&amp;rbrack; Problemas menores de diseño de la barra de herramientas del pincel al utilizar el borrador
* &amp;lbrack;UI&amp;rbrack; Las cadenas se truncan en algunos idiomas en el panel Ajustes del visor
* &amp;lbrack;UI&amp;rbrack; Mientras se muestra la ventana emergente de información sobre herramientas de la ventana gráfica, al pulsar &quot;espacio&quot; se crea un nuevo proyecto

### **4.1.2 CANNOLI**

*(Lanzado: 20 de junio de 2023)*

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Pérdida de memoria al ajustar los materiales y filtros del Substance que provocan bloqueos

### **4.1.1 CANNOLI**

*(Lanzado: 06 de junio de 2023)*

**Agregado**

* &amp;lbrack;Motor&amp;rbrack; Actualizar Substance Engine a la versión 9.0
* &amp;lbrack;Interoperabilidad&amp;rbrack; Enviar objetos 3D a Stager y Painter

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Las aplicaciones se bloquean cuando falla el procesador de captura 3D
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo cuando no se puede cargar una imagen
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al alcanzar el paso de reconstrucción de malla
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al cambiar el tamaño del cuadro delimitador
* &amp;lbrack;captura 3D&amp;rbrack; Importar máscaras siguiendo la convención no asigna la máscara correctamente
* &amp;lbrack;captura 3D&amp;rbrack; El procesamiento falla al ajustar el cuadro delimitador
* &amp;lbrack;captura 3D&amp;rbrack; El cambio entre las opciones de procesamiento de la versión y de alternancia durante el posproceso de Captura 3D es lento
* &amp;lbrack;captura 3D&amp;rbrack; El cambio entre versiones durante el paso captura 3D posterior al proceso a veces se interrumpe
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al inicio
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al duplicar un material cuyo nombre se ha cambiado
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al abrir un proyecto .alch heredado sin su carpeta de dependencias
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al conectar o desconectar una pantalla, el equipo pasa a la suspensión o se accede de forma remota
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueos y pérdidas de memoria relacionados con la administración de activos no persistentes
* &amp;lbrack;Exportar&amp;rbrack; La selección del formato de material para los tipos de archivo de objeto 3D que incrustan o hacen referencia a texturas debe estar desactivada
* &amp;lbrack;Exportar&amp;rbrack; Bloqueo si se produce un error durante la exportación de objetos 3D
* &amp;lbrack;Exportar&amp;rbrack; Bloqueo al exportar un archivo .sbs/.sbsar
* &amp;lbrack;Exportar&amp;rbrack; Se produce un bloqueo al importar un ajuste preestablecido personalizado que tiene la misma etiqueta pero no el mismo nombre de archivo
* &amp;lbrack;Exportar&amp;rbrack; La exportación de una luz ambiental a un archivo .sbs/.sbsar a veces no funciona
* &amp;lbrack;Exportar&amp;rbrack; La exportación de Gltf/Glb codifica texturas en base64
* &amp;lbrack;Exportar&amp;rbrack; El campo de texto de nombre no funciona al reenfocar
* &amp;lbrack;Exportar&amp;rbrack; Conservar el mosaico no funciona al exportar una capa de imagen a material (con IA) a un archivo .sbs/.sbsar
* &amp;lbrack;Exportar&amp;rbrack; Al exportar gltf y reemplazar archivos, la lista de archivos que se van a reemplazar no es correcta
* &amp;lbrack;Parámetros expuestos&amp;rbrack; La velocidad aleatoria no funciona en archivos .sbs/.sbsar exportados
* &amp;lbrack;Capas&amp;rbrack; El Relleno según el contenido a veces se bloquea cuando se añade por segunda vez
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al calcular una pila de capas
* &amp;lbrack;Capas&amp;rbrack; La caché de disco de imagen a material (AI) no funciona
* &amp;lbrack;Capas&amp;rbrack; Posible bloqueo al ajustar una capa
* &amp;lbrack;Rendimiento&amp;rbrack; Pérdidas de memoria
* &amp;lbrack;Proyecto&amp;rbrack; Bloqueo al guardar un proyecto
* &amp;lbrack;Proyecto&amp;rbrack; Importar el mismo proyecto dos veces seguidas duplica activos
* &amp;lbrack;UI&amp;rbrack; Los botones redondeados con solo un icono no se representan correctamente

### 4.1.0 Cannoli

*(Lanzado: 28 de marzo de 2023)*

**Agregado:**

* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de bordado
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Deformación de pintura
* &amp;lbrack;UI&amp;rbrack; Opción Añadir exportación en el menú Archivo
* &amp;lbrack;captura 3D&amp;rbrack; El botón Atrás ahora está disponible en el paso de alineación
* &amp;lbrack;captura 3D&amp;rbrack; Imágenes Manejar JPEG Orientación EXIF
* &amp;lbrack;captura 3D&amp;rbrack; Scripting: nueva propiedad dataset_info.camera
* &amp;lbrack;captura 3D&amp;rbrack; Añadir compatibilidad con Linux (consulte la documentación)
* &amp;lbrack;captura 3D&amp;rbrack; Comprobar el acceso de lectura de las imágenes importadas
* &amp;lbrack;Incorporación&amp;rbrack; Formación - 2 nuevos tutoriales (Bordado y Deformación de pintura)
* &amp;lbrack;Incorporación&amp;rbrack; Contenido actualizado de novedades

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Mantener la posición de la cámara al cambiar la versión
* &amp;lbrack;captura 3D&amp;rbrack; Fusionar todos los grupos de un objeto en uno
* &amp;lbrack;captura 3D&amp;rbrack; Mallas generadas cuyo nombre ha cambiado a Original
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al intentar generar una miniatura de una imagen que no existe
* &amp;lbrack;Assets&amp;rbrack; El icono de papelera no hace nada en el panel Activos
* &amp;lbrack;Contenido&amp;rbrack; La actualización de filtros con ranuras de material no funciona del modo esperado
* &amp;lbrack;Exportar&amp;rbrack; Posible bloqueo al exportar un recurso con filtros específicos
* &amp;lbrack;Exportar&amp;rbrack; Exportación SBS/SBSAR: las capas de importación de imágenes tenían prioridad sobre los parámetros de la imagen
* &amp;lbrack;Exportar&amp;rbrack; El ajuste preestablecido de exportación UE4 no funciona con PNG
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al soltar un material y un filtro al mismo tiempo desde el explorador del sistema operativo
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al arrastrar cualquier archivo SBSAR con cualquier archivo de imagen
* &amp;lbrack;Capas&amp;rbrack; El canal de opacidad del bordado puede ser completamente blanco
* &amp;lbrack;Localización&amp;rbrack; El idioma chino se puede mostrar de forma predeterminada en Linux
* &amp;lbrack;Rendimiento&amp;rbrack; Se ha corregido un problema de memoria al eliminar una capa de un recurso
* &amp;lbrack;Proyecto&amp;rbrack; Posible bloqueo al guardar
* &amp;lbrack;UI&amp;rbrack; Añadir el espaciado que falta en el botón de menú de la versión
* &amp;lbrack;UI&amp;rbrack; El botón Cancelar no se muestra correctamente
* &amp;lbrack;UI&amp;rbrack; Desactivación de la animación de los reguladores para los parámetros de posprocesamiento de captura 3D
* &amp;lbrack;UI&amp;rbrack; La ventana Plantilla de Creación de Materiales no se cierra al pulsar fuera
* &amp;lbrack;UI&amp;rbrack; El descriptor de acceso rápido de filtro se cierra al hacer clic fuera

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 4.0.2 Plátano

*(Lanzado: 9 de marzo de 2023)*

**Agregado:**

* &amp;lbrack;captura 3D&amp;rbrack; Uso del disco muestra la cantidad utilizada
* &amp;lbrack;captura 3D&amp;rbrack; La importación de fotografías es asincrónica y más rápida
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nuevas clases y funciones para crear scripts de la función de captura 3D
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nueva clase ExportController para realizar acciones cuando la exportación finaliza, falla o se cancela
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Pase argumentos a los scripts de python ejecutados con —run-script
* &amp;lbrack;UI&amp;rbrack; Comentarios de la interfaz de usuario al arrastrar un recurso sobre el panel Capas
* &amp;lbrack;Contenido&amp;rbrack; El filtro de temperatura de color ahora está trabajando en materiales
* &amp;lbrack;Contenido&amp;rbrack; Normal a los filtros de Height tiene una nueva opción para conservar el mosaico

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Tamaño de imagen corregido en el paso de alineación del conjunto de datos
* &amp;lbrack;captura 3D&amp;rbrack; Eliminar vértices duplicados después de desajustar UV
* &amp;lbrack;captura 3D&amp;rbrack; MacOS: mejor detección si hay captura 3D disponibles
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al cerrar la ventana de Captura 3D al importar imágenes
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al generar una nueva versión
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al intentar cargar el objeto 3D en el visor
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo al utilizar una ruta con caracteres que no son UTF8
* &amp;lbrack;captura 3D&amp;rbrack; Errores tipográficos de aciertos y sugerencias
* &amp;lbrack;captura 3D&amp;rbrack; Las mallas ya no se escalan para ajustarse al cubo de unidades
* &amp;lbrack;captura 3D&amp;rbrack; Evitar un bloqueo al cerrar Captura 3D durante el procesamiento
* &amp;lbrack;captura 3D&amp;rbrack; Al quitar una máscara, la imagen desaparece
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al importar dos veces un recurso simultáneamente
* &amp;lbrack;Aplicación&amp;rbrack; Hacer una copia de seguridad de la versión anterior de los recursos al abrir un proyecto si nunca se hicieron copias de seguridad
* &amp;lbrack;Aplicación&amp;rbrack; Almacenar mapas con bake correctamente en caché cuando no todos los mapas están procesados correctamente
* &amp;lbrack;Aplicación&amp;rbrack; La pantalla completa se bloquea cuando se muestra un objeto 3D.
* &amp;lbrack;Aplicación&amp;rbrack; El último material se duplica al guardar el proyecto
* &amp;lbrack;Aplicación&amp;rbrack; Evite el bloqueo al cancelar el procesamiento posterior de Mesh durante el paso de procesamiento
* &amp;lbrack;Aplicación&amp;rbrack; La reapertura del proyecto actual no descarta los cambios
* &amp;lbrack;Aplicación&amp;rbrack; Detener la generación de miniaturas para objetos 3D
* &amp;lbrack;2D View&amp;rbrack; Bloqueo al utilizar la herramienta Pincel
* &amp;lbrack;Contenido&amp;rbrack; Relleno según el contenido: el cálculo puede bloquearse
* &amp;lbrack;Contenido&amp;rbrack; El filtro Atlas Creator está reduciendo la escala del canal Opacidad
* &amp;lbrack;Exportar&amp;rbrack; Corregir borrar cola de exportaciones fallidas
* &amp;lbrack;Exportar&amp;rbrack; La exportación OBJ crea un objeto 100 veces más pequeño de lo esperado
* &amp;lbrack;Capas&amp;rbrack; Las imágenes en color importadas como canales en escala de grises ahora se consideran en escala de grises
* &amp;lbrack;Exportar&amp;rbrack; Los archivos FBX no se pueden importar en aplicaciones de terceros
* &amp;lbrack;Exportar&amp;rbrack; Los nombres de salida del sombreador en archivos USD no son correctos
* &amp;lbrack;Capas&amp;rbrack; El nombre de la imagen no se actualiza al cambiar su nombre en el explorador del sistema operativo
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Mostrar un mensaje de error al volver a cargar un script no válido
* &amp;lbrack;UI&amp;rbrack; Botón de material base desactivado cuando no está disponible
* &amp;lbrack;UI&amp;rbrack; Bloqueo al acceder al cuadro de diálogo de archivo en la ventana Plantilla de creación de material
* &amp;lbrack;UI&amp;rbrack; Se puede acceder al descriptor de acceso rápido incluso cuando el panel Capas está cerrado
* &amp;lbrack;UI&amp;rbrack; Los iconos de Enviar a están alineados incorrectamente
* &amp;lbrack;UI&amp;rbrack; El icono de capa cambia al hacer clic en el icono de fusión

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 4.0.1 Plátano

*(Lanzado: 07 de febrero de 2023)*

**Corregido:**

* &amp;lbrack;captura 3D&amp;rbrack; Al utilizar máscaras, la proyección de textura puede romperse
* &amp;lbrack;captura 3D&amp;rbrack; Pueden aparecer artefactos en el objeto
* &amp;lbrack;captura 3D&amp;rbrack; La malla exportada puede ser muy pequeña

**Problemas conocidos:**

* &amp;lbrack;captura 3D&amp;rbrack; Las exportaciones de FBX y OBJ reducen el resultado
* &amp;lbrack;captura 3D&amp;rbrack; captura 3D está disponible en MacOS aunque el hardware no sea compatible. Consulte la documentación.
* &amp;lbrack;captura 3D&amp;rbrack; Bloqueo cuando se realiza la reconstrucción de la malla.
* &amp;lbrack;Capas&amp;rbrack; El Relleno según el contenido se puede bloquear si se ajustan las capas siguientes
* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 4.0.0 Plátano

*(Lanzado: 31 de enero de 2023)*

**Agregado:**

* &amp;lbrack;captura 3D&amp;rbrack; Creación de objetos 3D a partir de imágenes
* &amp;lbrack;captura 3D&amp;rbrack; Asistente para captura 3D dedicadas
* &amp;lbrack;captura 3D&amp;rbrack; Importar o generar máscaras en blanco y negro en el conjunto de datos
* &amp;lbrack;captura 3D&amp;rbrack; Resultado de la alineación: ver todas las funciones coincidentes como una nube de puntos
* &amp;lbrack;captura 3D&amp;rbrack; Resultado de la alineación: vea e interactúe con las cámaras asociadas a cada fotografía alineada
* &amp;lbrack;captura 3D&amp;rbrack; Definir el área de reconstrucción con un widget de cuadro delimitador
* &amp;lbrack;captura 3D&amp;rbrack; Escalar, trasladar y rotar en todos los ejes el widget de cuadro delimitador
* &amp;lbrack;captura 3D&amp;rbrack; Definir la precisión geométrica de la malla reconstruida
* &amp;lbrack;captura 3D&amp;rbrack; Optimice sus mallas y texturas creando una nueva versión
* &amp;lbrack;captura 3D&amp;rbrack; Cada una de las versiones se diezma automáticamente al conjunto de números de caras de destino
* &amp;lbrack;captura 3D&amp;rbrack; El paso posterior al proceso desenvuelve, vuelve a proyectar texturas automáticamente y, a continuación, hornea la información normal de height y AO de la malla de alta densidad de poli
* &amp;lbrack;captura 3D&amp;rbrack; Agregue el resultado original o una versión al proyecto de Sampler
* &amp;lbrack;captura 3D&amp;rbrack; Nueva capa posterior al proceso de malla para diezmar, desenvolver, volver a proyectar texturas y hornear detalles de la capa de malla subyacente de forma automática
* &amp;lbrack;captura 3D&amp;rbrack; Nueva capa de transformación de malla para escalar, rotar o trasladar la capa de malla subyacente
* &amp;lbrack;Exportar&amp;rbrack; Nueva ventana de exportación
* &amp;lbrack;Exportar&amp;rbrack; Ajustes e interfaz de usuario dedicados en función del tipo de activo (material, luz de entorno, malla)
* &amp;lbrack;Exportar&amp;rbrack; Exportar la malla como USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &amp;lbrack;Exportar&amp;rbrack; Definir el tipo de material al exportar ficheros de Substance (SBSAR, SBS)
* &amp;lbrack;UI&amp;rbrack; Mueva la configuración de la caché a una nueva pestaña en el menú emergente Preferencias
* &amp;lbrack;Aplicación&amp;rbrack; Las ventanas gráficas 2D y 3D ahora se pueden cambiar de tamaño, intercambiar y apilar verticalmente
* &amp;lbrack;Aplicación&amp;rbrack; Nueva variable de entorno SAMPLER_RESOURCES_PATH para añadir recursos de inicio adicionales
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Se han añadido variables de entorno SAMPLER_PLUGIN_PATH y SAMPLER_SCRIPT_PATH para importar complementos y secuencias de comandos al inicio
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Se han añadido funciones de exportación para materiales, luces de entorno y objetos 3D
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Se han añadido a los parámetros identificadores, valores predeterminados, valores mínimos y máximos, etiquetas y valores enum
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Se ha añadido la función import_textures para introducir un uso personalizado al importar imágenes

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al abrir un proyecto reciente y guardar en el cuadro de diálogo de confirmación
* &amp;lbrack;Aplicación&amp;rbrack; El cuadro de diálogo Archivo impide abrir archivos .ssa
* &amp;lbrack;Aplicación&amp;rbrack; Los cuadros de diálogo de archivo pueden aparecer en una ventana de fondo en macOS
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo potencial al abrir proyectos de la versión 3.2
* &amp;lbrack;Aplicación&amp;rbrack; Al seleccionar un archivo, se cierra el cuadro de diálogo Archivo antes de mostrar advertencias
* &amp;lbrack;Parámetros expuestos&amp;rbrack; La exportación de luces de entorno paramétricas no funciona
* &amp;lbrack;Capas&amp;rbrack; El vínculo &quot;Haga clic aquí para examinar&quot; de la pila de capas ya no funciona
* &amp;lbrack;Capas&amp;rbrack; En ocasiones, pintar varias imágenes dentro de la misma capa no funciona
* &amp;lbrack;Capas&amp;rbrack; La configuración de una imagen en las propiedades de capa no actualiza la miniatura del selector de imágenes
* &amp;lbrack;Capas&amp;rbrack; La modificación de un recurso de Sampler añadido como capa no funciona
* &amp;lbrack;Proyecto&amp;rbrack; Actualización de recursos no deseada al abrir un proyecto
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Buscar la carpeta del complemento a veces falla en Windows
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Bloqueo al utilizar &#39;open_project()&#39; en un script de Python
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Falta la exportación del JPEG en la API
* &amp;lbrack;Secuencias de comandos&amp;rbrack; El panel de registro no es de solo lectura
* &amp;lbrack;Secuencias de comandos&amp;rbrack; el valor del parámetro image_picker no funciona
* &amp;lbrack;UI&amp;rbrack; Falta el icono de recurso para las luces de entorno en el panel Proyecto
* &amp;lbrack;UI&amp;rbrack; El menú desplegable Enviar a formato Designer del menú emergente Preferencias puede estar vacío
* &amp;lbrack;UI&amp;rbrack; Algunos botones tienen un estilo incorrecto
* &amp;lbrack;UI&amp;rbrack; La etiqueta se superpone a los botones de los widgets de grupo de botones
* &amp;lbrack;UI&amp;rbrack; La posición de la información sobre herramientas es incorrecta para &quot;Herramientas&quot; en el menú Definir tamaño físico
* &amp;lbrack;UI&amp;rbrack; Al cambiar el idioma, el menú Archivo no está alineado correctamente

**Problemas conocidos:**

* &amp;lbrack;captura 3D&amp;rbrack; Al utilizar máscaras, la proyección de textura puede romperse
* &amp;lbrack;captura 3D&amp;rbrack; Pueden aparecer pequeños defectos en el objeto si la escala en la transformación de malla es demasiado pequeña
* &amp;lbrack;captura 3D&amp;rbrack; La malla exportada puede ser muy pequeña. Restablecer la escala de la transformación de malla y volver a exportar
* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

## Versión 3

### 3.4.1 Arancini

*(Lanzado: 6 de octubre de 2022)*

**Agregado:**

* &amp;lbrack;Incorporación&amp;rbrack; Nuevas pantallas de bienvenida y novedades
* &amp;lbrack;Incorporación&amp;rbrack; IU actualizada de la pantalla Inicio
* &amp;lbrack;Incorporación&amp;rbrack; Nuevo contenido de Formación en la pantalla de inicio
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Registrar un error en el panel Registro cuando no se reconoce un método
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Nuevo módulo ssa.helpers para habilitar la impresión en el panel Registro
* &amp;lbrack;Aplicación&amp;rbrack; Compatibilidad con el nuevo widget de botones en paralelo de Substance 3D Designer

**Corregido:**

* &amp;lbrack;Exportar&amp;rbrack; Bloqueo al exportar un archivo .sbsar que hace referencia a una imagen que falta
* &amp;lbrack;Exportar&amp;rbrack; Bloqueo al exportar un recurso que hace referencia a un archivo de imagen dañado
* &amp;lbrack;Exportar&amp;rbrack; Exportar un archivo .sbsar con una capa de bordado produce un material gris
* &amp;lbrack;Exportar&amp;rbrack; La exportación de un material a un archivo .sbs/sbsar puede generar un material totalmente transparente
* &amp;lbrack;Exportar&amp;rbrack; El parámetro Formato normal no se expone correctamente en archivos .sbs/.sbsar
* &amp;lbrack;Exportar&amp;rbrack; La exportación de Sbs/Sbsar de una pila de capas que hace referencia a un archivo .svg está dañada
* &amp;lbrack;Exportar&amp;rbrack; La capa de transformación no se exporta correctamente / Se ha actualizado el ajuste preestablecido de exportación de Enscape - Revit
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Bloqueo al eliminar una capa que contiene un parámetro expuesto
* &amp;lbrack;Parámetros expuestos&amp;rbrack; La actualización de una capa obsoleta en la pila de capas puede generar una lista dañada de parámetros expuestos
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Los parámetros que no se deben exportar se exportan de todos modos
* &amp;lbrack;Parámetros expuestos&amp;rbrack; La eliminación de un filtro de mezcla al eliminar una capa no deja de exponer sus parámetros
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Los parámetros de texto rompen las exportaciones de .sbs/.sbsar
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al soltar una pila de capas en otra pila de capas
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al no cargar un filtro
* &amp;lbrack;Capas&amp;rbrack; No se puede volver a cargar la imagen anterior al restablecer el campo Imagen
* &amp;lbrack;Capas&amp;rbrack; No se pueden deshacer/rehacer los cambios de la herramienta de transformación
* &amp;lbrack;Capas&amp;rbrack; La capa Tampón de clonar se bloquea tras hacer clic en &quot;Restablecer todas las configuraciones&quot;
* &amp;lbrack;Capas&amp;rbrack; El uso de cualquiera de los botones de restablecimiento impide dibujar en el campo Imagen
* &amp;lbrack;Capas&amp;rbrack; El botón Restablecer no borra la máscara de dibujo en el campo Imagen
* &amp;lbrack;Capas&amp;rbrack; El botón Restablecer del campo Imagen no hace nada si el usuario ha pintado algo
* &amp;lbrack;Capas&amp;rbrack; La caché de procesamiento no funciona cuando se utiliza la herramienta Pincel
* &amp;lbrack;Capas&amp;rbrack; La capa eliminada puede seguir apareciendo en el panel Propiedades
* &amp;lbrack;Capas&amp;rbrack; El cálculo de capas se puede detener al cambiar entre recursos del proyecto
* &amp;lbrack;Proyecto&amp;rbrack; En ocasiones, Sampler no puede abrir un proyecto desde el disco
* &amp;lbrack;2D View&amp;rbrack; La vista 2D siempre vuelve por defecto a Salida de material

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.4.0 Arancini

*(Lanzado: 6 de septiembre de 2022)*

**Agregado:**

* &amp;lbrack;Parámetros expuestos&amp;rbrack; Nuevo Panel Parámetros expuestos
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Botón Nuevo en los parámetros al pasar por encima para exponer y desexponer parámetros en el panel Propiedades
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Nuevo menú contextual del botón derecho del ratón sobre parámetros para exponer y desexponer parámetros en el panel Propiedades
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Los parámetros expuestos se enumeran en el Panel Parámetros expuestos
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Los puntos de color y los discos de color se añaden en varios lugares para identificar fácilmente los parámetros expuestos
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Las etiquetas de parámetros se pueden editar en el Panel Parámetros expuestos
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Mostrar una advertencia para los parámetros no exportables
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Mostrar una advertencia al mover una capa con parámetros de fusión expuestos a un lugar donde se oculten
* &amp;lbrack;Parámetros expuestos&amp;rbrack; Los parámetros expuestos se exportan en formatos SBS y SBSAR
* &amp;lbrack;Metadatos&amp;rbrack; Compatibilidad con plantillas de metadatos personalizadas
* &amp;lbrack;Metadatos&amp;rbrack; Nueva plantilla de metadatos de propiedades físicas de CLO
* &amp;lbrack;Metadatos&amp;rbrack; Añadir iconos al pasar el ratón para añadir o quitar metadatos personalizados
* &amp;lbrack;API de Python; Nueva API de Python
* &amp;lbrack;API de Python; API para creación de activos
* &amp;lbrack;API de Python; API para la gestión de capas
* &amp;lbrack;API de Python; API para la administración de parámetros
* &amp;lbrack;API de Python; API para la administración de proyectos
* &amp;lbrack;API de Python; Se puede activar y desactivar un complemento.
* &amp;lbrack;API de Python; Documentación de la API de Python accesible en el menú Ayuda
* &amp;lbrack;Secuencias de comandos&amp;rbrack; La sección Nuevos complementos y scripts en el elemento emergente Preferencias
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Crear e importar complementos para personalizar la interfaz de Sampler con sus propios paneles
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Los complementos pasan a formar parte de la interfaz de Sampler y se pueden acoplar y mover como paneles estándar de Sampler
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Barra de botones dedicada para los complementos en la barra de herramientas de la derecha de Sampler
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Crear e importar scripts para realizar una lista de tareas determinadas
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Inicio de scripts de Python a través del menú Scripts
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Los complementos y los scripts se pueden eliminar, reordenar y volver a cargar desde la ventana Preferencias
* &amp;lbrack;Secuencias de comandos&amp;rbrack; Se han añadido parámetros de línea de comandos —run-script
* &amp;lbrack;Logs&amp;rbrack; Nuevo panel Registros
* &amp;lbrack;Logs&amp;rbrack; Habilitar el panel Registros desde la ventana Preferencias
* &amp;lbrack;Logs&amp;rbrack; Nueva barra de acciones para borrar, copiar y pegar registros y exportarlos
* &amp;lbrack;Propiedades&amp;rbrack; Botón Nuevo en el cursor de los parámetros para restablecer el valor del parámetro
* &amp;lbrack;Propiedades&amp;rbrack; Nuevo menú contextual del botón derecho del ratón sobre parámetros para restablecer el valor del parámetro
* &amp;lbrack;Contenido&amp;rbrack; Imagen a material (con tecnología de IA) ahora funciona en MacOS
* &amp;lbrack;Motor&amp;rbrack; Actualizar el motor de Substance a v8.6.0

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; La aplicación podía bloquearse al salir cuando estaba en curso una generación de miniaturas
* &amp;lbrack;Aplicación&amp;rbrack; La aplicación puede bloquearse al utilizar Guardar como al salir
* &amp;lbrack;Aplicación&amp;rbrack; La aplicación se podría bloquear durante el apagado en MacOS
* &amp;lbrack;Aplicación&amp;rbrack; Al guardar con el cuadro de diálogo de color abierto, no se guardan los cambios
* &amp;lbrack;Exportar&amp;rbrack; La convención de nomenclatura de uso no es correcta al exportar
* &amp;lbrack;Capas&amp;rbrack; La colocación de un material sobre un filtro podría bloquearse
* &amp;lbrack;Capas&amp;rbrack; La actualización de una pila de capas obsoleta podría actualizar pilas de capas no relacionadas
* &amp;lbrack;Metadatos&amp;rbrack; Se exportan los campos vacíos
* &amp;lbrack;Metadatos&amp;rbrack; Cuando solo hay un elemento de metadatos, la interfaz de usuario le permite intentar reordenarlo
* &amp;lbrack;Proyecto&amp;rbrack; La computación nunca termina después de duplicar un material
* &amp;lbrack;Proyecto&amp;rbrack; El recurso del proyecto se duplica después de guardar el proyecto inicial
* &amp;lbrack;Proyecto&amp;rbrack; Cálculos innecesarios al cambiar de recurso
* &amp;lbrack;Procesando&amp;rbrack; Algunas pilas de capas no se procesan correctamente después de eliminar una capa
* &amp;lbrack;Seguridad&amp;rbrack; Corrección de CVE-2015-20107
* &amp;lbrack;UI&amp;rbrack; Las salidas 2D pueden ser borrosas dependiendo del tamaño de la ventana
* &amp;lbrack;UI&amp;rbrack; La vista previa de activos puede permanecer abierta en la parte superior cuando la aplicación pierde el enfoque
* &amp;lbrack;UI&amp;rbrack; Las esquinas redondeadas de la pantalla de bienvenida tienen un fondo opaco cuadrado

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.3.2 Calabacín

*(Lanzado: 28 de junio de 2022)*

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; Solucionar un posible bloqueo al abrir un proyecto
* &amp;lbrack;Exportar&amp;rbrack; Al reiniciar Sampler, se rompe la lista de ajustes preestablecidos de exportación personalizados importados
* &amp;lbrack;Interoperabilidad&amp;rbrack; Solucionar bloqueo cuando se elimina un material enviado desde Designer y luego se vuelve a enviar desde Designer
* &amp;lbrack;Proyecto&amp;rbrack; No es posible eliminar el último material o luz ambiental si es el último recurso del proyecto
* &amp;lbrack;Proyecto&amp;rbrack; Al hacer clic con el botón derecho en una luz ambiental, aparece el asterisco &quot;modificaciones no guardadas&quot;

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.3.1 Calabacín

*(Lanzado: 07 de junio de 2022)*

**Agregado:**

* &amp;lbrack;Aplicación&amp;rbrack; Compatibilidad nativa con Apple Silicon (M1)
* &amp;lbrack;UI&amp;rbrack; Nuevo método abreviado, tecla &quot;C&quot;, para desplazarse por los canales en la vista 2D
* &amp;lbrack;Herramientas&amp;rbrack; Campo numérico para editar el valor de color de escala de grises en la barra de herramientas Pincel

**Corregido:**

* &amp;lbrack;Herramientas&amp;rbrack; El uso de la herramienta Pincel en Windows con una escala de IU fraccional (150 %) desplaza los trazos
* &amp;lbrack;Rendimiento&amp;rbrack; Mejorar el consumo de memoria
* &amp;lbrack;Tamaño físico&amp;rbrack; Puede faltar información de tamaño físico al habilitar la función
* &amp;lbrack;UI&amp;rbrack; El desplazamiento del ratón a veces no funciona del modo esperado al pulsar la tecla Alt
* &amp;lbrack;Aplicación&amp;rbrack; La aplicación puede bloquearse al abrir un proyecto guardado
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al arrastrar y soltar varias imágenes y utilizar la importación de texturas en la ventana Plantilla de creación de material
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo potencial al guardar un proyecto que contiene un filtro personalizado
* &amp;lbrack;Aplicación&amp;rbrack; En ocasiones, el estado de la tecla Control se pierde al cambiar de aplicación
* &amp;lbrack;Assets&amp;rbrack; Bloqueo al cambiar el nombre de una carpeta local

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.3.0 Calabacín

*(Lanzado: 17 de mayo de 2022)*

**Agregado:**

* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Relleno según el contenido (Windows y Mac)
* &amp;lbrack;Contenido&amp;rbrack; El Relleno según el contenido (Content Aware Fill) está trabajando en imágenes, materiales PBR y luces de entorno
* &amp;lbrack;Contenido&amp;rbrack; Añada el parámetro &quot;Conservar segmentación&quot; a Imagen a material (con tecnología de IA)
* &amp;lbrack;Contenido&amp;rbrack; El filtro Transformación de perspectiva puede mostrar una cuadrícula entre sus cuatro puntos
* &amp;lbrack;Interoperabilidad&amp;rbrack; Enviar materiales a Adobe Substance 3D Stager
* &amp;lbrack;Herramientas&amp;rbrack; Centrar la transformación pulsando Ctrl al cambiar el tamaño de las herramientas Transformar o Recortar
* &amp;lbrack;Herramientas&amp;rbrack; Bloquee la proporción al cuadrado presionando Mayús al cambiar el tamaño de las herramientas Transformar o Recortar
* &amp;lbrack;Herramientas&amp;rbrack; El cursor del tampón de clonar ofrece una vista previa de lo que se sellará
* &amp;lbrack;Herramientas&amp;rbrack; Previsualización del contenido original en el cursor del Borrador al utilizar el Tampón de clonar
* &amp;lbrack;Herramientas&amp;rbrack; Ctrl+Clic crea un nuevo sello en la capa Tampón de clonar
* &amp;lbrack;Herramientas&amp;rbrack; Los sucesivos sellos de clonación ahora se agrupan en una sola capa
* &amp;lbrack;Herramientas&amp;rbrack; Revampación de IU de barras de pinceles
* &amp;lbrack;Herramientas&amp;rbrack; La posición de la barra de herramientas Pincel es persistente durante una sesión
* &amp;lbrack;Herramientas&amp;rbrack; Nuevas opciones de mosaico de pinceles por eje
* &amp;lbrack;Herramientas&amp;rbrack; Ocultar/mostrar la superposición sobre la vista 2D al pintar
* &amp;lbrack;Herramientas&amp;rbrack; Nuevo método abreviado, tecla &quot;X&quot;, para alternar entre Pincel y Borrador
* &amp;lbrack;Herramientas&amp;rbrack; Nuevo método abreviado, &quot;&amp;brack;&quot; &quot;&amp;brack;&quot; para cambiar el tamaño del pincel
* &amp;lbrack;Herramientas&amp;rbrack; Nuevo método abreviado, tecla &quot;E&quot;, para cambiar el Borrador
* &amp;lbrack;2D View&amp;rbrack; Nuevo modo de Proyección esférica al crear luz ambiental
* &amp;lbrack;2D View&amp;rbrack; La herramienta Pincel es compatible con el modo de proyección esférica
* &amp;lbrack;2D View&amp;rbrack; La herramienta Posición es compatible con el modo de proyección esférica
* &amp;lbrack;2D View&amp;rbrack; La función Deshacer/Rehacer es compatible con el modo de proyección esférica
* &amp;lbrack;2D View&amp;rbrack; En Proyección esférica, defina la posición predeterminada para que mire al centro del entorno
* &amp;lbrack;2D View&amp;rbrack; Nuevo control de exposición
* &amp;lbrack;UI&amp;rbrack; En el panel Propiedades, el ajuste de imagen muestra el origen del contenido (imagen o de una capa)
* &amp;lbrack;UI&amp;rbrack; Se ha mejorado el fondo desplegable de las salidas de capa/material
* &amp;lbrack;UI&amp;rbrack; Nueva posición de la información de resolución en la vista 2D
* &amp;lbrack;UI&amp;rbrack; Nueva información sobre herramientas con métodos abreviados de los controles de navegación de la vista 3D
* &amp;lbrack;UI&amp;rbrack; Nueva información sobre herramientas con controles de pincel
* &amp;lbrack;UI&amp;rbrack; Nueva información sobre herramientas con métodos abreviados de controles de navegación de proyección
* &amp;lbrack;Filtros compuestos&amp;rbrack; Los filtros compuestos controlan las variaciones para trabajar con imágenes, materiales PBR y luces de entorno
* &amp;lbrack;Filtros compuestos&amp;rbrack; El orden de los ajustes coincide con el orden de la lista de nodos en el filtro compuesto
* &amp;lbrack;Filtros compuestos&amp;rbrack; Los ajustes de nodos diferentes con el mismo grupo se combinarán en un solo grupo en el panel Propiedades
* &amp;lbrack;Aplicación&amp;rbrack; Tener una configuración de visor dedicada por tipo de activo

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; La aplicación puede bloquearse al cambiar a la vista 2D
* &amp;lbrack;Aplicación&amp;rbrack; Solucionar un posible interbloqueo o bloqueo al exportar varias veces
* &amp;lbrack;Aplicación&amp;rbrack; Hacer que los valores predeterminados de los canales sean coherentes con Substance 3D Designer
* &amp;lbrack;Aplicación&amp;rbrack; La carga de un proyecto no activa el recálculo de material
* &amp;lbrack;Aplicación&amp;rbrack; Se ha actualizado la URL de la documentación de importación de texturas
* &amp;lbrack;Contenido&amp;rbrack; Cuando se utiliza un filtro compuesto, solicita que se actualice cuando no debería, al volver a cargar
* &amp;lbrack;Contenido&amp;rbrack; Los detalles del mapa de height desaparecen al utilizar la fusión de opacidad
* &amp;lbrack;UI&amp;rbrack; En el cuadro de diálogo Color, es posible salirse del rango mediante los campos de texto del regulador
* &amp;lbrack;UI&amp;rbrack; La lista de uso tiene una barra de desplazamiento vertical inútil

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &amp;lbrack;Contenido&amp;rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &amp;lbrack;Interoperabilidad&amp;rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.2.1 Yakitori

*(Lanzado: 08 de marzo de 2022)*

**Agregado:**

* &amp;lbrack;Exportar&amp;rbrack; Exportación de metadatos de ppp en archivos de imagen
* &amp;lbrack;Tamaño físico&amp;rbrack; Mantener la proporción con texturas no cuadradas al editar dimensiones físicas
* &amp;lbrack;Tamaño físico&amp;rbrack; Los metadatos de tamaño físico se aplican inmediatamente cuando cambia el tamaño físico
* &amp;lbrack;UI&amp;rbrack; Ajuste el regulador Escala de Height máxima para que pueda influir en cualquier tipo de material cuando el Tamaño físico está activado
* &amp;lbrack;UI&amp;rbrack; Nuevas sugerencias sobre filtros de búsqueda en el panel Activos
* &amp;lbrack;UI&amp;rbrack; Utilice información sobre herramientas para explicar cuándo están desactivados los botones en el panel Activos
* &amp;lbrack;Contenido&amp;rbrack; Actualización del filtro de contraste de brillo

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; El botón de rotación de 90 grados de las herramientas Recortar y Transformar no funciona del modo esperado
* &amp;lbrack;2D View&amp;rbrack; El widget de recorte a veces desaparece
* &amp;lbrack;Aplicación&amp;rbrack; Borrar un parámetro de imagen no vuelve a conectar la capa subyacente
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir después de guardar un proyecto
* &amp;lbrack;Aplicación&amp;rbrack; Se produce un bloqueo al arrastrar y soltar el material actual en una colección del panel Activos
* &amp;lbrack;Aplicación&amp;rbrack; La acción de arrastrar y soltar un recurso en la ventana gráfica puede bloquearse
* &amp;lbrack;Contenido&amp;rbrack; La mezcla normal tiene una modificación aleatoria de la semilla
* &amp;lbrack;Contenido&amp;rbrack; El filtro Snow tiene una salida normal incorrecta en función de los valores de los parámetros de nieve fresca y derretida
* &amp;lbrack;Contenido&amp;rbrack; Filtro de parquet: costuras inesperadas fijas
* &amp;lbrack;Contenido&amp;rbrack; Filtro de bordado: quitar rosca en mapa metálico
* &amp;lbrack;Contenido&amp;rbrack; Filtro de azulejos de piso: corregir el recuento de mosaicos x e y
* &amp;lbrack;Contenido&amp;rbrack; Filtro de pared de ladrillo: salida normal y height a 16 bits
* &amp;lbrack;Exportar&amp;rbrack; El nombre de archivo predeterminado en la ventana emergente de exportación no es el nombre de material actual
* &amp;lbrack;Exportar&amp;rbrack; La exportación con una proporción física con un ajuste preestablecido de exportación produce dimensiones incorrectas
* &amp;lbrack;Exportar&amp;rbrack; Falta Metallic en el ajuste preestablecido de exportación de CLO
* &amp;lbrack;Exportar&amp;rbrack; Al reemplazar un ajuste personalizado de exportación, el nombre para mostrar no se actualiza
* &amp;lbrack;Capas&amp;rbrack; No se descubren los canales personalizados de la primera capa insertada
* &amp;lbrack;Capas&amp;rbrack; El material se vuelve a evaluar al cambiar los ajustes de una capa oculta
* &amp;lbrack;Localización&amp;rbrack; La información sobre herramientas no se localiza en el panel Exportar
* &amp;lbrack;Tamaño físico&amp;rbrack; Al deshabilitar el Tamaño físico de un recurso no se elimina la escala física
* &amp;lbrack;Tamaño físico&amp;rbrack; El valor Escala de height no se puede establecer fuera de los límites del regulador la primera vez
* &amp;lbrack;Tamaño físico&amp;rbrack; Importar una imagen sin tamaño físico impide abrir el proyecto
* &amp;lbrack;Tamaño físico&amp;rbrack; El tamaño físico se establece erróneamente en cero cuando falta
* &amp;lbrack;Tamaño físico&amp;rbrack; El estado de la casilla de verificación Escala física de tamaño físico no se actualiza la primera vez que se muestra
* &amp;lbrack;UI&amp;rbrack; Material base y Normal al Height no tienen una categoría
* &amp;lbrack;UI&amp;rbrack; El cursor a veces es invisible al pintar una imagen
* &amp;lbrack;UI&amp;rbrack; Deshabilite las opciones &quot;Copiar todo&quot; y &quot;Cortar todo&quot; en el menú de edición de un campo de texto si está vacío
* &amp;lbrack;UI&amp;rbrack; Los nombres de filtro tienen caracteres incorrectos
* &amp;lbrack;UI&amp;rbrack; El botón de bloqueo del tamaño físico no tiene el estilo correcto
* &amp;lbrack;UI&amp;rbrack; El botón Cerrar de la barra de búsqueda del panel Activos no borra la cadena de búsqueda

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.2.0 Yakitori

*(Lanzado: 25 de enero de 2022)*

**Agregado:**

* &amp;lbrack;Tamaño físico&amp;rbrack; Nuevo panel Tamaño físico
* &amp;lbrack;Tamaño físico&amp;rbrack; Añadir opciones de Tamaño físico a la ventana Plantilla de Creación de Material
* &amp;lbrack;Tamaño físico&amp;rbrack; Herramienta Agregar medida de Tamaño físico
* &amp;lbrack;Tamaño físico&amp;rbrack; Herramienta Agregar medida automática de Tamaño físico
* &amp;lbrack;Tamaño físico&amp;rbrack; Herramienta Agregar diagnóstico de Tamaño físico
* &amp;lbrack;Tamaño físico&amp;rbrack; Permitir la configuración del valor z del Tamaño físico
* &amp;lbrack;Tamaño físico&amp;rbrack; Widget desplegable para establecer el nivel de zoom en la vista 2D
* &amp;lbrack;Tamaño físico&amp;rbrack; Nueva opción &quot;Mostrar con proporción física&quot; en el menú desplegable de nivel de zoom
* &amp;lbrack;Tamaño físico&amp;rbrack; Nueva opción &quot;Ajustar al tamaño físico&quot; en el menú desplegable de nivel de zoom
* &amp;lbrack;Tamaño físico&amp;rbrack; Mostrar el Tamaño físico en la vista 2D
* &amp;lbrack;Tamaño físico&amp;rbrack; Mostrar el Tamaño físico en la ventana gráfica 3D
* &amp;lbrack;Tamaño físico&amp;rbrack; En el cuadro de diálogo de importación de imágenes, muestre la profundidad de tamaño físico si hay un mapa de height importado
* &amp;lbrack;Tamaño físico&amp;rbrack; Mostrar el Tamaño físico en el menú contextual del recurso
* &amp;lbrack;Tamaño físico&amp;rbrack; Defina la unidad de longitud en Preferencias
* &amp;lbrack;Tamaño físico&amp;rbrack; Exportación de texturas respetando la proporción física
* &amp;lbrack;Metadatos&amp;rbrack; Posibilidad de añadir metadatos personalizados a un activo creado por el usuario
* &amp;lbrack;Exportar&amp;rbrack; Exportación de metadatos personalizados a archivos .sbs(ar)
* &amp;lbrack;Exportar&amp;rbrack; Exportar descripción, categoría, autor y etiquetas de metadatos a archivos .sbs(ar)
* &amp;lbrack;Exportar&amp;rbrack; Exporte el Tamaño físico a archivos .sbs(ar)
* &amp;lbrack;Exportar&amp;rbrack; Establecer la configuración de compresión de archivos .sbsar
* &amp;lbrack;Exportar&amp;rbrack; Exporte la miniatura del activo a archivos .sbs(ar)
* &amp;lbrack;Exportar&amp;rbrack; Definir el tipo de gráfico al exportar un archivo .sbs(ar)
* &amp;lbrack;Aplicación&amp;rbrack; El motor en tiempo real 2021 ya no está disponible
* &amp;lbrack;Aplicación&amp;rbrack; Ahora, Deshacer/Rehacer admite cambios de segmentación (U,V) y de escala de height
* &amp;lbrack;Procesando&amp;rbrack; Generar caché de disco al guardar el activo creado
* &amp;lbrack;Assets&amp;rbrack; Utilice Ctrl+clic para activar varios filtros de tipo de recurso en el panel Recursos
* &amp;lbrack;UI&amp;rbrack; Posibilidad de bloquear los reguladores de Mosaico (U,V)
* &amp;lbrack;UI&amp;rbrack; Añadir un menú contextual con &quot;Copiar&quot;, &quot;Cortar&quot;, &quot;Pegar&quot;, &quot;Copiar todo&quot; y &quot;Cortar todo&quot; en los campos de texto
* &amp;lbrack;UI&amp;rbrack; Unidad de longitud (metros, pulgadas, parsecs, ...) compatibilidad con etiquetas y campos de texto
* &amp;lbrack;UI&amp;rbrack; El usuario puede establecer la precisión decimal utilizada para mostrar los números
* &amp;lbrack;UI&amp;rbrack; Utilice las unidades en las ventanas emergentes de medida en todas partes que sea relevante
* &amp;lbrack;Localización&amp;rbrack; El nombre del nuevo recurso predeterminado ahora está localizado
* &amp;lbrack;Contenido&amp;rbrack; Nuevo generador de tejido de tela
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de cambio de canal
* &amp;lbrack;Contenido&amp;rbrack; Todos los filtros relevantes son ahora conscientes del Tamaño físico
* &amp;lbrack;Contenido&amp;rbrack; Nuevos iconos para Acabado en Madera
* &amp;lbrack;Contenido&amp;rbrack; Todos los filtros son ahora compatibles con los canales de Adobe de materiales estándar (ASM)
* &amp;lbrack;Contenido&amp;rbrack; Los filtros ahora pueden tener una variación de &quot;entorno&quot;

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; El canal permanece en la lista cuando se elimina
* &amp;lbrack;Aplicación&amp;rbrack; No se puede duplicar un recurso cargado desde el explorador de archivos del sistema operativo
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir
* &amp;lbrack;Aplicación&amp;rbrack; Se produce un bloqueo al hacer clic en &quot;Activos iniciales&quot; en el panel Activos
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al eliminar un material
* &amp;lbrack;Aplicación&amp;rbrack; La variable de entorno &quot;SUBSTANCE_DISABLE_SPECIFIC_FEATURES&quot; sigue activa cuando se define en &quot;0&quot; o &quot;&quot;.
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al guardar un proyecto con varios materiales
* &amp;lbrack;Aplicación&amp;rbrack; Importar una imagen puede provocar un bloqueo
* &amp;lbrack;Aplicación&amp;rbrack; Faltan algunos recursos de inicio en el primer inicio
* &amp;lbrack;Exportar&amp;rbrack; La exportación de un activo a veces produce un bloqueo
* &amp;lbrack;Capas&amp;rbrack; No se pueden importar imágenes cuando el panel Capa está cerrado o es invisible
* &amp;lbrack;Capas&amp;rbrack; Al cambiar el idioma, se vuelve a calcular el activo actual
* &amp;lbrack;Capas&amp;rbrack; Al cambiar el uso de una imagen importada, no se actualiza la variación de filtro que se debe utilizar
* &amp;lbrack;Capas&amp;rbrack; A veces, la imagen a material (IA) no se calcula al ajustar capas por debajo de ella
* &amp;lbrack;Capas&amp;rbrack; A veces, la imagen a material (IA) se vuelve a calcular cuando no es necesario
* &amp;lbrack;Capas&amp;rbrack; No se sugiere ninguna actualización cuando se actualiza un filtro personalizado en el disco
* &amp;lbrack;Capas&amp;rbrack; El canal normal a veces tiene un formato de píxel incorrecto
* &amp;lbrack;Capas&amp;rbrack; Algunas capas aún se calculan incluso cuando no están visibles
* &amp;lbrack;Capas&amp;rbrack; Las herramientas de la vista 2D pueden romperse al cambiar la visibilidad de una capa
* &amp;lbrack;Capas&amp;rbrack; La interfaz de usuario se bloquea al utilizar Imagen a material (AI)
* &amp;lbrack;Capas&amp;rbrack; Al cambiar la visibilidad de la capa de filtro Transformar, se rompe la herramienta de vista 2D y puede producirse un bloqueo
* &amp;lbrack;Capas&amp;rbrack; Demasiados cálculos al eliminar una capa de la pila de capas
* &amp;lbrack;Capas&amp;rbrack; Cuando un filtro compuesto contiene una entrada/salida inusual o personalizada, Sampler no la calcula
* &amp;lbrack;Rendimiento&amp;rbrack; El panel Activos tarda en abrirse
* &amp;lbrack;Rendimiento&amp;rbrack; Evite algunos cálculos innecesarios de la pila de capas
* &amp;lbrack;Rendimiento&amp;rbrack; La carga de recursos del proyecto tarda demasiado tiempo
* &amp;lbrack;Rendimiento&amp;rbrack; No se puede usar la caché de procesamiento en el disco
* &amp;lbrack;Rendimiento&amp;rbrack; El cambio entre capas es lento
* &amp;lbrack;Rendimiento&amp;rbrack; La modificación de un material o un filtro es lenta
* &amp;lbrack;Proyecto&amp;rbrack; Guardar un proyecto al salir puede producir un bloqueo
* &amp;lbrack;Procesando&amp;rbrack; Al quitar una imagen, es posible que se eliminen todas las salidas
* &amp;lbrack;Procesando&amp;rbrack; El tiempo de procesamiento mostrado en la ventana gráfica es incorrecto al realizar ajustes
* &amp;lbrack;UI&amp;rbrack; No se puede desplazar verticalmente en la ventana emergente de exportación cuando es necesario
* &amp;lbrack;UI&amp;rbrack; Es posible abrir la ventana emergente de exportación cuando no hay nada que exportar
* &amp;lbrack;UI&amp;rbrack; Algunas ventanas emergentes no se desplazan si su contenido se desborda
* &amp;lbrack;UI&amp;rbrack; Los campos de texto no se seleccionan al hacer clic en ellos o abrir un menú
* &amp;lbrack;UI&amp;rbrack; El nombre del modo de fusión en el panel de propiedades a veces no es correcto
* &amp;lbrack;UI&amp;rbrack; La opción Guardar del menú Archivo a veces está atenuada
* &amp;lbrack;UI&amp;rbrack; El campo de texto no desaparece después de cambiar el nombre de dos materiales
* &amp;lbrack;UI&amp;rbrack; Error tipográfico en la ventana emergente de preferencias

**Problemas conocidos:**

* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.1.2 Xocoatl

*(Lanzado: 14 de diciembre de 2021)*

**Corregido:**

* &amp;lbrack;Interoperabilidad&amp;rbrack; El archivo .sbsar abierto con Substance 3D Sampler desde Bridge puede fallar en Windows
* &amp;lbrack;Capas&amp;rbrack; Si mueve la única capa por debajo de sí misma, se producirá un bloqueo
* &amp;lbrack;UI&amp;rbrack; El botón Configuración de canal desaparece al cambiar el idioma
* &amp;lbrack;UI&amp;rbrack; El nombre del material en el panel Propiedades desaparece después de guardar el proyecto
* &amp;lbrack;Assets&amp;rbrack; Hacer clic en &quot;Todas las bibliotecas&quot; puede provocar un bloqueo

**Problemas conocidos:**

* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; El cálculo intensivo puede bloquear la aplicación
* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; Realtime Engine 2021 se bloqueará en un equipo Windows con la CPU AMD y la GPU NVIDIA instaladas
* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.1.1 Xocoatl

*(Lanzado: 24 de noviembre de 2021)*

**Agregado:**

* &amp;lbrack;Interoperabilidad&amp;rbrack; Enviar recursos (SBS o SBSAR) a Substance 3D Designer
* &amp;lbrack;Interoperabilidad&amp;rbrack; Defina en las preferencias el formato predeterminado para la interoperabilidad con Substance 3D Designer
* &amp;lbrack;Interoperabilidad&amp;rbrack; Recibir varios recursos de Adobe Bridge
* &amp;lbrack;UI&amp;rbrack; Nuevo widget Raíz aleatoria
* &amp;lbrack;UI&amp;rbrack; Actualización del menú contextual
* &amp;lbrack;Assets&amp;rbrack; Arrastrar y soltar imágenes desde el panel Activos al panel Propiedades
* &amp;lbrack;Proyecto&amp;rbrack; Los nombres de los activos se corrigen para evitar algunos caracteres específicos
* &amp;lbrack;Marca&amp;rbrack; Icono Actualizar archivo para archivos SBSAR
* &amp;lbrack;Motor&amp;rbrack; Actualizar Substance Engine versión 8.3.0

**Corregido:**

* &amp;lbrack;Contenido&amp;rbrack; Recortar: conservar proporción al recortar imágenes no cuadradas
* &amp;lbrack;Contenido&amp;rbrack; Transformar: la transformación horizontal no se invierte al utilizar el widget
* &amp;lbrack;Contenido&amp;rbrack; Grava: corrija la pintura de máscara personalizada en todos los canales
* &amp;lbrack;Contenido&amp;rbrack; Baldosas de suelo: solucione problemas con el azulejo de motivos y la repetición
* &amp;lbrack;Assets&amp;rbrack; Opción Gris hacia fuera en Adobe Bridge si no está instalada
* &amp;lbrack;Selector de color&amp;rbrack; La tecla Escape cierra el Selector de color
* &amp;lbrack;Procesando&amp;rbrack; Corrección de la escala de distancia de dispersión al utilizar la entrada de escala de grises
* &amp;lbrack;Compartir&amp;rbrack; Las opciones Enviar a solo están disponibles con licencias de Adobe
* &amp;lbrack;Proyecto&amp;rbrack; Solucionar un problema de rendimiento de memoria

**Problemas conocidos:**

* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; El cálculo intensivo puede bloquear la aplicación
* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; Realtime Engine 2021 se bloqueará en un equipo Windows con la CPU AMD y la GPU NVIDIA instaladas
* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.1.0 Xocoatl

*(Lanzado: 28 de septiembre de 2021)*

**Agregado:**

* &amp;lbrack;Selector de color&amp;rbrack; Nueva interfaz de usuario del selector de color
* &amp;lbrack;Selector de color&amp;rbrack; Vista previa de los colores actuales y anteriores en paralelo
* &amp;lbrack;Selector de color&amp;rbrack; Introducir el color en hexadecimal
* &amp;lbrack;Selector de color&amp;rbrack; Nuevo cuentagotas con previsualización de color
* &amp;lbrack;Selector de color&amp;rbrack; El cuentagotas puede seleccionar un color fuera de Sampler
* &amp;lbrack;Selector de color&amp;rbrack; Ajustar el color en espacios de color RGB o HSV
* &amp;lbrack;Selector de color&amp;rbrack; Almacenamiento y gestión de muestras
* &amp;lbrack;Interoperabilidad&amp;rbrack; Editar imágenes en Illustrator desde la capa de importación de imágenes o los parámetros de imagen
* &amp;lbrack;Interoperabilidad&amp;rbrack; Editar imágenes en Photoshop desde la capa de importación de imágenes o los parámetros de imagen
* &amp;lbrack;Widget&amp;rbrack; Nuevo widget de recorte
* &amp;lbrack;Widget&amp;rbrack; Pulsa la tecla Entrar para validar el recorte
* &amp;lbrack;Widget&amp;rbrack; El widget Recortar lee el tamaño de la imagen para que se ajuste al widget y mantiene la proporción al cambiar el tamaño
* &amp;lbrack;UI&amp;rbrack; Nueva interfaz de usuario del regulador de escala de grises
* &amp;lbrack;Aplicación&amp;rbrack; Añadir la selección de formato normal en las preferencias
* &amp;lbrack;Aplicación&amp;rbrack; El formato normal de las capas de importación de imágenes sigue el formato normal predeterminado establecido en las preferencias
* &amp;lbrack;Aplicación&amp;rbrack; En la vista 2D, la normal se muestra según el formato normal definido en las preferencias
* &amp;lbrack;Aplicación&amp;rbrack; La normal se exporta en el formato normal definido en las preferencias
* &amp;lbrack;Exportar&amp;rbrack; Agregar un parámetro de formato normal a las exportaciones de archivos SBS y SBSAR
* &amp;lbrack;Exportar&amp;rbrack; Añadir configuración de sombreado a las exportaciones de archivos SBS y SBSAR
* &amp;lbrack;Exportar&amp;rbrack; Definir la resolución predeterminada de los gráficos SBS exportados
* &amp;lbrack;Filtros compuestos&amp;rbrack; Empaquetar filtros SSA con 7z
* &amp;lbrack;Filtros compuestos&amp;rbrack; Adición de metadatos de categoría en filtros compuestos
* &amp;lbrack;Filtros compuestos&amp;rbrack; Los filtros compuestos pueden tener una miniatura incrustada
* &amp;lbrack;Filtros compuestos&amp;rbrack; Se ha añadido la extensión Filtros compuestos (.ssafilter) al cuadro de diálogo Obtener contenido del archivo
* &amp;lbrack;Filtros compuestos&amp;rbrack; Importar filtros compuestos (.ssafilter) en el panel Activos
* &amp;lbrack;Motor&amp;rbrack; Actualizar el motor de Substance a la versión 8.2.0

**Corregido:**

* &amp;lbrack;Aplicación&amp;rbrack; Las carpetas locales conectadas pueden bloquearse
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al iniciar dos instancias de Sampler
* &amp;lbrack;Contenido&amp;rbrack; El filtro Recortar tiene un ajuste aleatorio de la velocidad
* &amp;lbrack;Contenido&amp;rbrack; Algunos materiales de Substance a veces no se actualizan
* &amp;lbrack;Exportar&amp;rbrack; Bloqueo al exportar con un ajuste preestablecido personalizado recién añadido
* &amp;lbrack;Exportar&amp;rbrack; Falta el tamaño estimado del paquete en la ventana emergente de exportación
* &amp;lbrack;Exportar&amp;rbrack; Corregir pérdidas de memoria al exportar archivos SBS y SBSAR
* &amp;lbrack;Filtros compuestos&amp;rbrack; Los filtros compuestos pueden tener entradas duplicadas
* &amp;lbrack;Filtros compuestos&amp;rbrack; Bloqueo si un filtro tiene referencias no satisfechas
* &amp;lbrack;Filtros compuestos&amp;rbrack; Bloqueo al reordenar una pila de capas con un filtro compuesto
* &amp;lbrack;Filtros compuestos&amp;rbrack; El renderizado a veces se bloquea
* &amp;lbrack;Importación de imágenes&amp;rbrack; Importar una imagen activa varias representaciones
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al deshacer o rehacer
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al añadir un Material base
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al utilizar una imagen no válida como luz de entorno
* &amp;lbrack;Capas&amp;rbrack; Corregir la importación duplicada al insertar un filtro con varios gráficos
* &amp;lbrack;Capas&amp;rbrack; La reordenación de capas no siempre funciona
* &amp;lbrack;Proyecto&amp;rbrack; Bloqueo al cargar un archivo de proyecto incompleto
* &amp;lbrack;Proyecto&amp;rbrack; Bloqueo al abrir un proyecto dañado
* &amp;lbrack;Proyecto&amp;rbrack; Algunos recursos pueden desaparecer de un proyecto
* &amp;lbrack;Propiedades&amp;rbrack; Corregir los ajustes preestablecidos de filtros que faltan
* &amp;lbrack;UI&amp;rbrack; No se pueden establecer parámetros de ángulo
* &amp;lbrack;UI&amp;rbrack; Visualización de metadatos de filtros en el panel Activos
* &amp;lbrack;UI&amp;rbrack; Agrupar por categoría oculta filtros
* &amp;lbrack;UI&amp;rbrack; Problema de desplazamiento en el panel Activos
* &amp;lbrack;UI&amp;rbrack; El panel Exportar ahora tiene una barra de desplazamiento
* &amp;lbrack;UI&amp;rbrack; La miniatura no se muestra para algunos formatos de imagen en el selector de imágenes

**Problemas conocidos:**

* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; El cálculo intensivo puede bloquear la aplicación
* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; Realtime Engine 2021 se bloqueará en un equipo Windows con la CPU AMD y la GPU NVIDIA instaladas
* &amp;lbrack;Selector de color&amp;rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.0.1 Waffle

*(Lanzado: 27 de julio de 2021)*

**Agregado:**

* &amp;lbrack;Brush&amp;rbrack; Activar colores en la herramienta Pincel si la entrada de imagen lo admite
* &amp;lbrack;Brush&amp;rbrack; Si mantiene pulsada la tecla Mayús en la herramienta Pincel, se dibujarán líneas rectas
* &amp;lbrack;Brush&amp;rbrack; Mostrar una previsualización de línea al mantener pulsada la tecla Mayús en la herramienta Pincel
* &amp;lbrack;Brush&amp;rbrack; La herramienta Pincel ahora admite deshacer y rehacer
* &amp;lbrack;2D View&amp;rbrack; El color predeterminado de entrada de imagen se utiliza al pintar
* &amp;lbrack;Capas&amp;rbrack; Leer el valor predeterminado de entrada del Substance en archivos SBSAR
* &amp;lbrack;Procesando&amp;rbrack; Permitir combinar el height con normal
* &amp;lbrack;Procesando&amp;rbrack; Compatibilidad con la dispersión subsuperficial (no disponible en MacOS)
* &amp;lbrack;Assets&amp;rbrack; Usar el tipo de gráfico SBSAR para determinar el tipo de activo
* &amp;lbrack;Assets&amp;rbrack; Mejor rendimiento para la búsqueda y la detección de activos en el panel Activos
* &amp;lbrack;Assets&amp;rbrack; Se ha añadido la entrada &quot;Todas las bibliotecas&quot; en el panel Activos, que muestra todos los activos de todas las bibliotecas
* &amp;lbrack;Assets&amp;rbrack; El usuario ahora puede elegir agrupar activos por categoría o tipo
* &amp;lbrack;Importar&amp;rbrack; Detección automática de texturas de anisotropía, capa, brillo y specular edge color en la importación
* &amp;lbrack;UI&amp;rbrack; Sustitución del título del panel protegido por un icono
* &amp;lbrack;UI&amp;rbrack; Actualización de estilo de Textfields
* &amp;lbrack;UI&amp;rbrack; Nuevo texto de descripción en la ventana Creación de plantillas de luz de entorno
* &amp;lbrack;Aplicación&amp;rbrack; Exportar recursos con la resolución actual al enviarlos a una aplicación externa
* &amp;lbrack;Aplicación&amp;rbrack; La resolución predeterminada del material es ahora 2048\*2048 (1024\*1024 en macos)
* &amp;lbrack;Contenido&amp;rbrack; Nuevos patrones en el filtro de azulejos de piso
* &amp;lbrack;Contenido&amp;rbrack; Nuevo modo de color dual en el filtro de reemplazo de color

**Corregido:**

* &amp;lbrack;2D View&amp;rbrack; El primer trazo de la herramienta Pincel a veces se rompe
* &amp;lbrack;2D View&amp;rbrack; Recursos libres cuando la herramienta Pincel no está visible
* &amp;lbrack;2D View&amp;rbrack; Usar el cursor de cambio de tamaño adecuado en el widget de transformación
* &amp;lbrack;2D View&amp;rbrack; Los widgets no se muestran si el usuario ha realizado una panorámica en la vista 2D antes
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al abrir un proyecto con un flujo de trabajo interrumpido
* &amp;lbrack;Aplicación&amp;rbrack; Solucionar el cierre de la aplicación para evitar que el registro se llene de errores inútiles
* &amp;lbrack;Aplicación&amp;rbrack; Los métodos abreviados de teclado para rehacer, eliminar y guardar no funcionan en algunos sistemas operativos
* &amp;lbrack;Aplicación&amp;rbrack; El cambio de deshacer/rehacer del uso de la imagen en la capa de importación no funciona
* &amp;lbrack;Exportar&amp;rbrack; Las imágenes exportadas con color de emisión tienen un nombre incorrecto
* &amp;lbrack;Exportar&amp;rbrack; El entorno es de 8 bits al utilizar la exportación SBSAR
* &amp;lbrack;Exportar&amp;rbrack; Eliminación de espacios adicionales en los nombres de archivos de imagen exportados
* &amp;lbrack;Exportar&amp;rbrack; La sustitución o eliminación de un ajuste preestablecido de exportación personalizado se bloquea
* &amp;lbrack;Capas&amp;rbrack; Evite el bloqueo cuando haya una discrepancia en el recuento de entradas
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al insertar una capa de Material base
* &amp;lbrack;Capas&amp;rbrack; El recuento de entrada de filtro se limita al valor predeterminado
* &amp;lbrack;Capas&amp;rbrack; Rehacer cambia erróneamente el tipo de fusión a fusión de Height
* &amp;lbrack;Capas&amp;rbrack; Quitar zona de colocación encima de los encabezados de entrada
* &amp;lbrack;Capas&amp;rbrack; Las capas se insertan en el lugar incorrecto alrededor de los encabezados de entrada
* &amp;lbrack;Capas&amp;rbrack; El botón Restablecer todos los ajustes no restablece los valores de los widgets desplegables
* &amp;lbrack;Capas&amp;rbrack; Deshacer/rehacer al cambiar una imagen en la capa de importación de imágenes marca el proyecto como modificado y, por lo tanto, para guardarlo
* &amp;lbrack;Capas&amp;rbrack; Las capas de mezcla pueden detener los usos
* &amp;lbrack;Proyecto&amp;rbrack; Bloqueo al cargar un proyecto heredado con la carpeta de dependencias que faltan
* &amp;lbrack;Proyecto&amp;rbrack; Bloqueo al utilizar deshacer/rehacer después de guardar
* &amp;lbrack;Proyecto&amp;rbrack; Al abrir un archivo SBSAR que contiene una luz ambiental, se crea un activo material
* &amp;lbrack;Proyecto&amp;rbrack; Cambiar el nombre de un material puede desencadenar la generación de miniaturas
* &amp;lbrack;Proyecto&amp;rbrack; Guardar después de cambiar el nombre de un material marca el proyecto como no modificado
* &amp;lbrack;Proyecto&amp;rbrack; Algunos cambios realizados después de cambiar el nombre de un material no se guardan
* &amp;lbrack;Procesando&amp;rbrack; Los puntos brillantes se ven en el entorno con el motor en tiempo real de 2020
* &amp;lbrack;Procesando&amp;rbrack; Bloqueo al cambiar el tamaño con Real Time Engine 2021
* &amp;lbrack;Procesando&amp;rbrack; Calcular sombras al cambiar el nivel del height
* &amp;lbrack;Assets&amp;rbrack; Las carpetas conectadas dejan de indizar nuevos recursos al agregar un archivo no válido
* &amp;lbrack;Assets&amp;rbrack; Bloqueo al conectar una carpeta local con muchos materiales
* &amp;lbrack;UI&amp;rbrack; Faltan descripciones emergentes de los botones de vista 2D/3D
* &amp;lbrack;UI&amp;rbrack; Todos los activos del panel Activos aparecen resaltados al iniciarse
* &amp;lbrack;UI&amp;rbrack; A veces, las rutas de navegación desaparecen en el panel Activos al importar materiales
* &amp;lbrack;UI&amp;rbrack; Cambiar el idioma no afecta al panel Proyecto
* &amp;lbrack;UI&amp;rbrack; El panel Configuración de canal muestra información del flujo de trabajo heredado
* &amp;lbrack;UI&amp;rbrack; Alinear correctamente el texto &quot;Sin configuración para este elemento&quot; para filtros sin ajustes en el panel Propiedades
* &amp;lbrack;UI&amp;rbrack; Los elementos se desalinean en la pantalla de bienvenida y aparecen las preferencias
* &amp;lbrack;UI&amp;rbrack; Los títulos del panel tienen un ancho incorrecto
* &amp;lbrack;UI&amp;rbrack; El desplazamiento a veces se interrumpe en el panel Propiedades
* &amp;lbrack;UI&amp;rbrack; La pantalla de bienvenida tiene una proporción incorrecta y está borrosa
* &amp;lbrack;UI&amp;rbrack; El modo de pantalla completa no es de pantalla completa
* &amp;lbrack;UI&amp;rbrack; Los paneles no acoplados siempre están en la parte superior, incluso cuando la aplicación no está activa en MacOS
* &amp;lbrack;UI&amp;rbrack; Imagen del banner de la pantalla de bienvenida
* &amp;lbrack;Contenido&amp;rbrack; El filtro de segmentación no procesa el canal de oclusión de ambiente
* &amp;lbrack;Contenido&amp;rbrack; Problema de puntada de tejido con la selección de la costura del conjunto de soldadura y el patrón de diamante
* &amp;lbrack;Contenido&amp;rbrack; El filtro de relieve funciona en 256 x 256 px
* &amp;lbrack;Contenido&amp;rbrack; Corregir el problema de mosaico con los mosaicos de suelo cuando el desplazamiento es mayor que 0

**Problemas conocidos:**

* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; Cálculo intenso, bloqueo de la aplicación
* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; Realtime Engine 2021 se bloquea en equipos Windows con CPU AMD y GPU NVIDIA

### 3.0.0 Waffle

*(Lanzado: 23 de junio de 2021)*

**Agregado:**

* &amp;lbrack;Marca&amp;rbrack; Substance Alchemist se convierte en Adobe Substance 3D Sampler
* &amp;lbrack;Marca&amp;rbrack; Nuevos iconos de aplicación
* &amp;lbrack;UI&amp;rbrack; Nueva experiencia de usuario e interfaz de usuario
* &amp;lbrack;UI&amp;rbrack; Nueva pantalla de presentación
* &amp;lbrack;UI&amp;rbrack; Los paneles son desacoplables y acoplables en la interfaz
* &amp;lbrack;UI&amp;rbrack; Acoplar hasta 3 paneles en la misma columna
* &amp;lbrack;UI&amp;rbrack; Acoplar hasta 3 paneles en el mismo panel (pestañas)
* &amp;lbrack;UI&amp;rbrack; Desacoplar paneles para crear una ventana independiente en la misma pantalla o en otra distinta
* &amp;lbrack;UI&amp;rbrack; Los paneles cerrados aparecen al hacer clic en sus iconos
* &amp;lbrack;UI&amp;rbrack; Reorganización de la barra izquierda y derecha moviendo los iconos de los paneles
* &amp;lbrack;UI&amp;rbrack; Nueva barra de herramientas para acceder directamente a filtros específicos (Recortar, Transformar, Transformación de perspectiva, Tampón de clonar)
* &amp;lbrack;UI&amp;rbrack; Nuevo botón &quot;Obtener contenido&quot; en la barra izquierda
* &amp;lbrack;UI&amp;rbrack; Importar archivos directamente en los activos con el botón Obtener contenido
* &amp;lbrack;UI&amp;rbrack; Importa archivos directamente a tus capas con el botón Obtener contenido
* &amp;lbrack;UI&amp;rbrack; Acceder directamente al sitio web de Adobe Substance 3D Assets con el botón Obtener contenido
* &amp;lbrack;UI&amp;rbrack; Ahora se puede acceder directamente al widget de resolución en la ventana gráfica
* &amp;lbrack;UI&amp;rbrack; Todos los elementos de la interfaz de usuario ahora se cargan dinámicamente
* &amp;lbrack;UI&amp;rbrack; Método abreviado: utilice &quot;2&quot; para cambiar la visibilidad de la vista 2D
* &amp;lbrack;UI&amp;rbrack; Método abreviado: utilice &quot;3&quot; para cambiar la visibilidad de la vista 3D
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Crear un proyecto con un solo clic con el botón Nuevo
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Banner de nueva ilustración
* &amp;lbrack;Proyecto&amp;rbrack; Todos los proyectos se asocian ahora a un archivo único
* &amp;lbrack;Proyecto&amp;rbrack; Nueva extensión de archivo de proyecto .ssa
* &amp;lbrack;Proyecto&amp;rbrack; Guardar como proyecto le pedirá que seleccione dónde guardar el proyecto
* &amp;lbrack;Proyecto&amp;rbrack; Al cerrar Sampler, se le pedirá que guarde el proyecto si no se ha guardado
* &amp;lbrack;Proyecto&amp;rbrack; Al cerrar Sampler, se le pedirá que guarde el proyecto si hay modificaciones desde la última operación de guardado
* &amp;lbrack;Proyecto&amp;rbrack; El nombre del proyecto se muestra encima de la ventana gráfica
* &amp;lbrack;Proyecto&amp;rbrack; El nombre del proyecto aparece en cursiva con una estrella si no se ha guardado o si contiene modificaciones desde la última operación de guardado
* &amp;lbrack;Proyecto&amp;rbrack; Abra un archivo de proyecto .ssa directamente desde el explorador del sistema operativo
* &amp;lbrack;Proyecto&amp;rbrack; Si abre un archivo .sbsar desde el explorador del sistema operativo, Sampler se iniciará con un nuevo proyecto que ya podrá utilizar
* &amp;lbrack;Proyecto&amp;rbrack; Abra un archivo .alch (archivo Substance Alchemist heredado) desde el explorador del sistema operativo
* &amp;lbrack;Panel Proyecto&amp;rbrack; Nuevo panel que contendrá todos los recursos creados dentro de un proyecto
* &amp;lbrack;Panel Proyecto&amp;rbrack; Cree un activo (material o luz ambiental) mediante el icono +
* &amp;lbrack;Panel Proyecto&amp;rbrack; Al hacer clic con el botón derecho en un recurso, se abre un menú contextual
* &amp;lbrack;Panel Proyecto&amp;rbrack; En el menú contextual que se muestra al hacer clic con el botón derecho, puede eliminar un activo
* &amp;lbrack;Panel Proyecto&amp;rbrack; En el menú contextual que se muestra al hacer clic con el botón derecho, puede duplicar un activo
* &amp;lbrack;Panel Proyecto&amp;rbrack; En el menú contextual que se muestra al hacer clic con el botón derecho, puede cambiar el nombre de un activo
* &amp;lbrack;Panel Proyecto&amp;rbrack; Cambiar entre activos no perderá modificaciones
* &amp;lbrack;Resolución&amp;rbrack; Ahora puede establecer una resolución no cuadrada para todos sus activos
* &amp;lbrack;Resolución&amp;rbrack; El valor de resolución se guarda por recurso dentro de un proyecto
* &amp;lbrack;Luz del entorno&amp;rbrack; Crear luz ambiental en Substance 3D Sampler
* &amp;lbrack;Luz del entorno&amp;rbrack; Al crear una luz de entorno, al arrastrar y soltar imágenes se mostrará la ventana Plantilla de creación de luz de entorno
* &amp;lbrack;Luz del entorno&amp;rbrack; En Plantilla de creación de luz de entorno, seleccione Importar entorno para asignar la imagen al entorno en la vista 3D
* &amp;lbrack;Luz del entorno&amp;rbrack; En la plantilla de creación de luz de entorno, seleccione la combinación HDR para crear una luz de entorno a partir de varias imágenes de 360 grados con diferente exposición
* &amp;lbrack;Luz del entorno&amp;rbrack; En la plantilla de creación de luz ambiental, seleccione &quot;Usar como mapa de bits&quot; para editar las imágenes antes de crear una luz ambiental
* &amp;lbrack;Luz del entorno&amp;rbrack; Asigne el uso del entorno en la capa de importación de imágenes para asignar directamente la imagen al entorno en la vista 3D
* &amp;lbrack;Luz del entorno&amp;rbrack; En la vista 2D del canal de entorno, existe una corrección de color automática para que el procesamiento tenga el mismo aspecto que en la vista 3D
* &amp;lbrack;Luz del entorno&amp;rbrack; Nuevo contenido dedicado para la creación de luz ambiental
* &amp;lbrack;Panel de recursos&amp;rbrack; Los paneles Recursos y Filtros se combinan en un nuevo panel Activos
* &amp;lbrack;Panel de recursos&amp;rbrack; El panel Activos ahora admite los siguientes tipos de activos: materiales, filtros e imágenes
* &amp;lbrack;Panel de recursos&amp;rbrack; Se puede acceder a todos los Activos iniciales en la sección Activos iniciales
* &amp;lbrack;Panel de recursos&amp;rbrack; La sección Activos iniciales es de solo lectura
* &amp;lbrack;Panel de recursos&amp;rbrack; Nueva sección &quot;Sus activos&quot;
* &amp;lbrack;Panel de recursos&amp;rbrack; La sección &quot;Sus activos&quot; es el lugar donde puede importar todos sus recursos
* &amp;lbrack;Panel de recursos&amp;rbrack; Todos los activos de &quot;Sus activos&quot; se añaden a una carpeta específica de sus Documentos
* &amp;lbrack;Panel de recursos&amp;rbrack; Conectar carpetas locales en el panel Activos para añadir nuevas secciones
* &amp;lbrack;Panel de recursos&amp;rbrack; La búsqueda buscará en la carpeta actual y sus subcarpetas
* &amp;lbrack;Panel de recursos&amp;rbrack; Desplazarse entre carpetas y subcarpetas con rutas de exploración
* &amp;lbrack;Panel de recursos&amp;rbrack; Filtrar la carpeta actual por material, filtro o imagen
* &amp;lbrack;Panel de recursos&amp;rbrack; Combina varios filtros para obtener solo materiales e imágenes
* &amp;lbrack;Panel de recursos&amp;rbrack; Cambiar la visualización cambiando entre una cuadrícula o una lista
* &amp;lbrack;Panel de recursos&amp;rbrack; Los filtros se representan con su icono
* &amp;lbrack;Panel de recursos&amp;rbrack; Las imágenes se representan con su previsualización
* &amp;lbrack;Panel de recursos&amp;rbrack; Al aumentar la anchura, se cambiará el diseño del panel con una vista específica para desplazarse por las carpetas
* &amp;lbrack;Panel de recursos&amp;rbrack; En las secciones que no sean de solo lectura, elimine un recurso arrastrándolo y soltándolo en el icono de la papelera
* &amp;lbrack;Panel de recursos&amp;rbrack; Al hacer clic con el botón derecho en un recurso, se abre un menú contextual
* &amp;lbrack;Panel de recursos&amp;rbrack; En el menú contextual del botón derecho, acceda a los metadatos del activo (nombre, categoría, ubicación)
* &amp;lbrack;Panel de recursos&amp;rbrack; En el menú contextual, elimine el activo (solo disponible en las secciones de no solo lectura)
* &amp;lbrack;Panel de recursos&amp;rbrack; En el menú contextual del botón derecho, examine el contenido en Adobe Bridge
* &amp;lbrack;Panel Capas&amp;rbrack; Nuevo icono para añadir directamente un material base encima de las capas
* &amp;lbrack;Panel Capas&amp;rbrack; Método abreviado : Mayús + B añadirá un material base encima de las capas
* &amp;lbrack;Panel Capas&amp;rbrack; Las capas ahora tienen una vista previa en miniatura (miniatura de material, icono de filtro o vista previa de imagen)
* &amp;lbrack;Panel Propiedades&amp;rbrack; Nuevo diseño del título del panel Propiedades con el nombre del recurso y la miniatura del recurso
* &amp;lbrack;Panel Propiedades&amp;rbrack; Las capas de filtro ahora admiten ajustes preestablecidos
* &amp;lbrack;Panel Propiedades&amp;rbrack; En Capa de importación de imágenes, haga clic con el botón derecho en la vista previa de la imagen para editarla en Photoshop
* &amp;lbrack;Adobe Bridge&amp;rbrack; Examine el recurso en Adobe Bridge; Bridge se iniciará en la ubicación del recurso
* &amp;lbrack;Adobe Photoshop&amp;rbrack; Editar en Adobe Photoshop abrirá la imagen en Photoshop lista para editarse
* &amp;lbrack;Adobe Photoshop&amp;rbrack; En cada operación de guardar en Adobe Photoshop, la imagen editada se volverá a cargar en Sampler
* &amp;lbrack;Substance 3D Designer&amp;rbrack; Los contenidos enviados desde Adobe Substance 3D Designer aparecerán directamente en la sección &quot;Sus contenidos&quot; del panel de contenidos
* &amp;lbrack;Exportar&amp;rbrack; Enviar recursos directamente a Adobe Substance 3D Painter y Adobe Substance 3D Stager
* &amp;lbrack;Exportar&amp;rbrack; Enviar materiales y luces de entorno a Adobe Substance 3D Painter
* &amp;lbrack;Exportar&amp;rbrack; Enviar luces de entorno a Adobe Substance 3D Stager
* &amp;lbrack;Procesando&amp;rbrack; Las nuevas propiedades de material ahora son compatibles y se representan en 3D
* &amp;lbrack;Procesando&amp;rbrack; Adición de la compatibilidad de brillo (Color de brillo, opacidad de brillo y rugosidad de brillo)
* &amp;lbrack;Procesando&amp;rbrack; Añadir soporte de recubrimiento (Color de la capa, Rugosidad de la capa, Normal de la capa, Specular level de la capa y IOR de la capa)
* &amp;lbrack;Procesando&amp;rbrack; Adición de compatibilidad de Anisotropía (nivel de Anisotropía y ángulo de Anisotropía)
* &amp;lbrack;Procesando&amp;rbrack; Adición de compatibilidad con Speculares edges color
* &amp;lbrack;Procesando&amp;rbrack; Active estas nuevas propiedades en el panel Configuración de canal
* &amp;lbrack;Procesando&amp;rbrack; Introducción de un nuevo procesador de Realtime Engine (2021) en la versión beta
* &amp;lbrack;Procesando&amp;rbrack; Cambiar entre las dos versiones de procesador en el panel Configuración del visor
* &amp;lbrack;Procesando&amp;rbrack; El procesador del motor en tiempo real (2021) admite las propiedades de translucidez, absorción y dispersión de materiales
* &amp;lbrack;Procesando&amp;rbrack; El procesador del motor en tiempo real (2021) presenta una nueva forma de calcular las sombras a partir de la luz del entorno
* &amp;lbrack;Procesando&amp;rbrack; El procesador del motor en tiempo real (2021) calcula en tiempo real la irradiancia de la luz del entorno
* &amp;lbrack;Panel Configuración del sombreador&amp;rbrack; Nuevo panel Ajustes del sombreado para ajustar parámetros específicos del sombreado de material
* &amp;lbrack;Panel Configuración del sombreador&amp;rbrack; Nuevos parámetros (Escala normal, Escala de height, Nivel de height, Intensidad de emisión, IOR, Intensidad normal de capa y IOR de capa)
* &amp;lbrack;Panel Configuración del sombreador&amp;rbrack; Parámetros específicos para el motor en tiempo real 2021 (dispersión subsuperficial, distancia de dispersión, desplazamiento rojo y dispersión de Rayleigh)
* &amp;lbrack;Panel Configuración del sombreador&amp;rbrack; Los valores de configuración se guardan por recurso
* &amp;lbrack;Panel de configuración del visor&amp;rbrack; Se ha añadido una previsualización de las luces de entorno predeterminadas
* &amp;lbrack;Panel de configuración del visor&amp;rbrack; Se ha añadido una vista previa de las mallas predeterminadas
* &amp;lbrack;Panel de configuración del visor&amp;rbrack; Nuevo parámetro de opacidad del entorno
* &amp;lbrack;Panel de configuración del visor&amp;rbrack; Nuevo parámetro de desenfoque de entorno (específico del procesador de Realtime Engine 2021)
* &amp;lbrack;Localización&amp;rbrack; Nuevas traducciones en alemán y francés
* &amp;lbrack;Contenido&amp;rbrack; Nuevos materiales de inicio predeterminados
* &amp;lbrack;Contenido&amp;rbrack; Nuevas luces de entorno predeterminadas
* &amp;lbrack;Contenido&amp;rbrack; Todos los filtros se han actualizado, limpiado y optimizado
* &amp;lbrack;Contenido&amp;rbrack; El filtro Ajuste se ha dividido en varios filtros
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Brillo/contraste
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Tono/Saturación
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de intensidad
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Enfocar
* &amp;lbrack;Contenido&amp;rbrack; Nuevo ajuste Normal/Height
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de paneles
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de difuminado
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de Tejidos
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de transformación de deformación
* &amp;lbrack;Contenido&amp;rbrack; Nuevo Height para el filtro AO
* &amp;lbrack;Contenido&amp;rbrack; Nuevo Height a filtro normal
* &amp;lbrack;Contenido&amp;rbrack; Sustitución de color: Reemplazar en nuevos canales compatibles (brillo, capa, Anisotropía, etc.)
* &amp;lbrack;Contenido&amp;rbrack; Variación de color: modo manual para seleccionar exactamente los colores que desea cambiar
* &amp;lbrack;Contenido&amp;rbrack; Mosaico - opción para visualizar las costuras cortadas
* &amp;lbrack;Contenido&amp;rbrack; Mosaico - opción para pintar las costuras cortadas para un azulejo perfecto
* &amp;lbrack;Contenido&amp;rbrack; Coincidencia : Opción para añadir un material para que coincida con su color y su rugosidad
* &amp;lbrack;Contenido&amp;rbrack; Coincidencia : ahora funciona en imágenes para que coincidan con el color de otra imagen
* &amp;lbrack;Contenido&amp;rbrack; Luz de ambiente - Nuevo filtro de temperatura de color
* &amp;lbrack;Contenido&amp;rbrack; Luz ambiental - Nuevo filtro de exposición
* &amp;lbrack;Contenido&amp;rbrack; Luz de entorno: nuevo filtro de previsualización de exposición
* &amp;lbrack;Contenido&amp;rbrack; Luz ambiental - Nuevo filtro de Nadir patch
* &amp;lbrack;Contenido&amp;rbrack; Luz ambiental - Nuevo filtro de Nadir extract
* &amp;lbrack;Contenido&amp;rbrack; Luz ambiental: nuevos filtros de luces (esfera, línea, forma, plano)
* &amp;lbrack;Contenido&amp;rbrack; Luz de entorno: nuevo filtro de parche de panorama
* &amp;lbrack;Contenido&amp;rbrack; Luz ambiental - Nuevo filtro Enderezar horizonte
* &amp;lbrack;Contenido&amp;rbrack; Luz de entorno: nuevo filtro de combinación HDR

**Problemas conocidos:**

* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; Al cambiar el diseño, se bloquea la aplicación
* &amp;lbrack;Motor en tiempo real 2021&amp;rbrack; Cálculo intenso, bloqueo de la aplicación
* &amp;lbrack;Panels&amp;rbrack; MacOS : los paneles no acoplados se encuentran delante de todas las aplicaciones
* &amp;lbrack;Widgets&amp;rbrack; Los widgets Transformar y Posiciones pueden desaparecer. Ocultar y mostrar la capa para que aparezcan.
* &amp;lbrack;Exportar&amp;rbrack; La exportación SBSAR de una luz ambiental pierde la precisión de 32 profundidades de bits
* &amp;lbrack;Panel de recursos&amp;rbrack; Los recursos se pueden resaltar al abrir una carpeta
* &amp;lbrack;Panel Propiedades&amp;rbrack; El restablecimiento de los parámetros no restablece la interfaz de usuario del cuadro combinado
* &amp;lbrack;Localización&amp;rbrack; El cambio de idioma no afecta al panel Proyecto hasta que se vuelva a crear

## Versión 2

### 2.3.2 (2020.3.2) Vermicelli

*(Lanzado: 23 de febrero de 2021)*

**Agregado:**

* &amp;lbrack;Localización&amp;rbrack; Compatibilidad con japonés

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Al retocar un material en el filtro de bordado, se pierde la imagen del bordado

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### 2.3.1 (2020.3.1) Vermicelli

*(Lanzado: 17 de diciembre de 2020)*

**Agregado:**

* &amp;lbrack;Motor&amp;rbrack; Actualización del Substance Engine
* &amp;lbrack;Aplicación&amp;rbrack; Variable de entorno para desactivar funciones específicas
* &amp;lbrack;Contenido&amp;rbrack; Reemplazar color: nueva opción de segmentación avanzada
* &amp;lbrack;Contenido&amp;rbrack; Azulejos de piso - nuevos patrones y opciones disponibles
* &amp;lbrack;Contenido&amp;rbrack; Bordado - Completa renovación del filtro
* &amp;lbrack;Contenido&amp;rbrack; Ajuste: nuevo parámetro metálico + corrección de transformación segura de opacidad

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; No se puede importar dos veces el mismo filtro personalizado
* &amp;lbrack;Capas&amp;rbrack; No se puede utilizar la entrada de imagen con la herramienta Pincel
* &amp;lbrack;Exportar&amp;rbrack; Exportar .jpg en lugar de .jpeg
* &amp;lbrack;UI&amp;rbrack; Actualizar créditos de imagen de pantalla de bienvenida
* &amp;lbrack;UI&amp;rbrack; Corregir separador invisible en los menús
* &amp;lbrack;UI&amp;rbrack; Los botones de opción muestran información sobre herramientas cuando se truncan
* &amp;lbrack;UI&amp;rbrack; Tipografía: Materiales de inicio
* &amp;lbrack;Aplicación&amp;rbrack; Los caracteres UTF-8 en los nombres de recursos no funcionan
* &amp;lbrack;Localización&amp;rbrack; Deshabilitar el estilo de fuente en cursiva para la configuración regional china
* &amp;lbrack;Localización&amp;rbrack; Cadena localizada dividida en 2 líneas
* &amp;lbrack;Localización&amp;rbrack; Ajustar el nombre de la carpeta y reemplazarlo por puntos suspensivos si es demasiado largo
* &amp;lbrack;Localización&amp;rbrack; Formatear números con separador de miles
* &amp;lbrack;Localización&amp;rbrack; Localizar la visualización de fecha y hora
* &amp;lbrack;Localización&amp;rbrack; Localizar el selector de color en Windows
* &amp;lbrack;Contenido&amp;rbrack; Transformar : Con la transformación segura activada, la normal gira correctamente cada 45°
* &amp;lbrack;Contenido&amp;rbrack; Relieve de superficie: Solución del problema de segmentación con el ruido fractal perlin (ruido avanzado)
* &amp;lbrack;Contenido&amp;rbrack; Patrón de pared de ladrillo - entrada de Height en 16 bits
* &amp;lbrack;Contenido&amp;rbrack; Procesamiento de iconos de material: problema de reflejos de Specular
* &amp;lbrack;Contenido&amp;rbrack; Variación de color : No hay cambio de color entre las entradas de color y el resultado
* &amp;lbrack;Contenido&amp;rbrack; Variación de color: actualización de rendimiento

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### 2.3.0 (2020.3.0) Vermicelli

*(Lanzado: 26 de octubre de 2020)*

**Agregado:**

* &amp;lbrack;Imagen a material&amp;rbrack; Compatibilidad con NVIDIA RTX serie 3000
* &amp;lbrack;Imagen a material&amp;rbrack; Nuevos parámetros para controlar los detalles de geometría
* &amp;lbrack;Imagen a material&amp;rbrack; Nuevos parámetros para controlar la rugosidad
* &amp;lbrack;Imagen a material&amp;rbrack; Nuevos parámetros para controlar la intensidad del deleite
* &amp;lbrack;Miniaturas&amp;rbrack; Nuevo generador de miniaturas basado en el procesador PBR de Substance Designer
* &amp;lbrack;Miniaturas&amp;rbrack; Actualizar materiales base y atlas para incrustar su miniatura
* &amp;lbrack;Miniaturas&amp;rbrack; Recupere la miniatura del archivo .sbsar si existe
* &amp;lbrack;Miniaturas&amp;rbrack; Cambiar la calidad de la miniatura en Preferencias
* &amp;lbrack;Motor&amp;rbrack; Actualizado a la versión 8 de Substance Engine
* &amp;lbrack;Localización&amp;rbrack; Localización en chino
* &amp;lbrack;UI&amp;rbrack; Selector de tintas planas experimental
* &amp;lbrack;Contenido&amp;rbrack; Nuevo mapa de entorno - Studio 06
* &amp;lbrack;Contenido&amp;rbrack; Añadir el filtro Generador de Atlas
* &amp;lbrack;Contenido&amp;rbrack; Añadir filtro de Atlas splitter
* &amp;lbrack;Contenido&amp;rbrack; Añadir filtro de encías descartadas
* &amp;lbrack;Contenido&amp;rbrack; Agregar filtro de huellas dactilares
* &amp;lbrack;Contenido&amp;rbrack; Añadir Scratches, filtro
* &amp;lbrack;Contenido&amp;rbrack; Añadir filtro de Relieve de superficie (reemplazar filtro de modulación de height)
* &amp;lbrack;Contenido&amp;rbrack; Añadir filtro de deformación
* &amp;lbrack;Contenido&amp;rbrack; Añadir filtro Invertir
* &amp;lbrack;Contenido&amp;rbrack; Añadir filtro Colorear
* &amp;lbrack;Contenido&amp;rbrack; Añadir filtro Reemplazar color
* &amp;lbrack;Contenido&amp;rbrack; Transformar : añada la posibilidad de desactivar la transformación en un canal específico
* &amp;lbrack;Contenido&amp;rbrack; Transformar : añadir rotación cuando se activa la transformación segura
* &amp;lbrack;Contenido&amp;rbrack; Variación de color : añada una opción de segmentación para elegir cómo distribuir los colores

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Actualizar correctamente la interfaz de usuario al realizar varias acciones de deshacer/rehacer
* &amp;lbrack;Capas&amp;rbrack; Evitar bloqueos al realizar varias acciones de deshacer/rehacer
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al utilizar Imagen a material (con tecnología de IA), con registro: ordinal de dispositivo no válido
* &amp;lbrack;Filters&amp;rbrack; Mejorar la detección de tarjetas gráficas NVIDIA para funciones específicas de NVIDIA
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al cerrar la aplicación
* &amp;lbrack;Aplicación&amp;rbrack; Corrección de la detección de VRAM en MacOS
* &amp;lbrack;Exportar&amp;rbrack; A veces, faltan algunos ajustes preestablecidos de exportación
* &amp;lbrack;Contenido&amp;rbrack; Efecto Pintura al óleo - Fijar rango de height con alta amplitud de desplazamiento
* &amp;lbrack;Contenido&amp;rbrack; Hacer que el azulejo sea avanzado: no hay color base lavado en la exportación
* &amp;lbrack;Contenido&amp;rbrack; Make It Tile Advanced - Máscara blanca en el color base cuando el AO es demasiado fuerte
* &amp;lbrack;Contenido&amp;rbrack; Ajuste: ahora funciona en imágenes (scan1, ...)

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### 2.2.1 (2020.2.1) Udon

*(Lanzado: 21 de julio de 2020)*

**Agregado:**

* &amp;lbrack;Capas&amp;rbrack; Mensaje de error de In App cuando se agota la memoria de una imagen a material (impulsada por IA)

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Imagen a material (con tecnología de IA) no funciona con flujos de trabajo de Specular/brillo
* &amp;lbrack;Capas&amp;rbrack; Se bloquea cuando se queda sin memoria de vídeo al utilizar Imagen a material (con tecnología de IA)
* &amp;lbrack;Capas&amp;rbrack; La caché de disco no se utiliza para la visualización al abrir una pila
* &amp;lbrack;Capas&amp;rbrack; Detección de NVIDIA RTX 8000
* &amp;lbrack;Capas&amp;rbrack; A veces es imposible mover una capa fuera de una entrada de Splatter
* &amp;lbrack;Capas&amp;rbrack; La caché de disco no se utiliza al insertar una pila en una pila
* &amp;lbrack;Capas&amp;rbrack; Algunos usos de canal se calculan aunque no se utilizan
* &amp;lbrack;Capas&amp;rbrack; En ocasiones, se crean salidas en blanco al importar imágenes
* &amp;lbrack;2D View&amp;rbrack; Cambiar a otra capa con el modo Dibujo activado bloquea la panorámica y el zoom
* &amp;lbrack;Contenido&amp;rbrack; Snow: problema de 8 bits en el mapa normal
* &amp;lbrack;Contenido&amp;rbrack; Patrón de pavimento - emisión de 8 bits en el mapa normal
* &amp;lbrack;Contenido&amp;rbrack; Ecualizador: problema de 8 bits en el mapa normal
* &amp;lbrack;Contenido&amp;rbrack; Generador de grava - 8 bits problema en el mapa normal
* &amp;lbrack;Contenido&amp;rbrack; Azulejos de piso - Manejar la opacidad y el specular level
* &amp;lbrack;Contenido&amp;rbrack; Ciclos de fusión aún exportar ajuste preestablecido - invertir mapa normal
* &amp;lbrack;Contenido&amp;rbrack; Corregir el problema con imágenes enormes con Imagen a material (con tecnología de IA)
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al elegir &quot;Copia de seguridad y reinicio&quot; en el error de base de datos
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al hacer clic rápidamente en el mismo activo
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueos raros al salir
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al colocar archivos en la pantalla de bienvenida
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al cargar un archivo de entorno dañado
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo raro al cambiar rápidamente de recurso procesado
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir mientras se está calculando un activo
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo raro al inicio en macOS
* &amp;lbrack;Aplicación&amp;rbrack; Interbloqueo al cerrar la aplicación poco después del inicio
* &amp;lbrack;Procesando&amp;rbrack; La vista 3D a veces parpadea
* &amp;lbrack;UI&amp;rbrack; El selector de color y los widgets de semilla aleatoria no están alineados con el resto de los ajustes
* &amp;lbrack;Procesando&amp;rbrack; Se muestra un tiempo de cálculo incorrecto
* &amp;lbrack;Exportar&amp;rbrack; A veces, faltan algunos ajustes preestablecidos de exportación

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### Udon 2.2.0 (2020.2.0)

*(Lanzado: 15 de junio de 2020)*

**Agregado:**

* &amp;lbrack;Crear&amp;rbrack; Nuevo filtro de imagen a material (con tecnología de IA) disponible en Windows y Linux
* &amp;lbrack;Crear&amp;rbrack; Cambiar nombre de mapa de bits de material a imagen a material (B2M)
* &amp;lbrack;Importación de imágenes&amp;rbrack; Ventana emergente Plantilla de creación de material nuevo
* &amp;lbrack;Importación de imágenes&amp;rbrack; Nueva opción &quot;Añadir un material base&quot;
* &amp;lbrack;Importación de imágenes&amp;rbrack; Posibilidad de arrastrar y soltar imágenes adicionales en la plantilla Creación de material
* &amp;lbrack;Importación de imágenes&amp;rbrack; Posibilidad de eliminar imágenes en la plantilla Creación de material
* &amp;lbrack;Importación de imágenes&amp;rbrack; Asignar automáticamente un canal a mapas de bits importados en función del nombre de archivo
* &amp;lbrack;Importación de imágenes&amp;rbrack; Ser capaz de invertir mapas normales
* &amp;lbrack;2D View&amp;rbrack; Introducción de un modo de pintura
* &amp;lbrack;2D View&amp;rbrack; Los azulejos de pintura
* &amp;lbrack;2D View&amp;rbrack; Establecer un valor de escala de grises para el color del pincel
* &amp;lbrack;2D View&amp;rbrack; Panorámica y zoom al pintar
* &amp;lbrack;2D View&amp;rbrack; Método abreviado X para invertir el valor de escala de grises del pincel
* &amp;lbrack;2D View&amp;rbrack; &amp;lbrack; y &amp;brack; métodos abreviados para cambiar el tamaño del pincel
* &amp;lbrack;2D View&amp;rbrack; Ctrl (o Cmd) + Rueda del ratón para cambiar el tamaño del pincel
* &amp;lbrack;2D View&amp;rbrack; Ahora es posible modificar la posición de origen al utilizar el parche de clonación
* &amp;lbrack;Capas&amp;rbrack; Mayús + arrastrar y soltar en atlas de dispersión automática
* &amp;lbrack;Capas&amp;rbrack; Alt + arrastrar y soltar inserta un material como una pegatina
* &amp;lbrack;Capas&amp;rbrack; Exponga fácilmente los transformares matrices de Substance Designer
* &amp;lbrack;Capas&amp;rbrack; La colocación de texturas en una pila no vacía se asigna automáticamente a los canales correctos
* &amp;lbrack;Capas&amp;rbrack; Nuevo tipo de capa: Filtros compuestos
* &amp;lbrack;Parámetros&amp;rbrack; Admitir entradas de cadena de Substance
* &amp;lbrack;UI&amp;rbrack; Se han añadido sombras paralelas para ventanas emergentes y menús
* &amp;lbrack;UI&amp;rbrack; Nuevo widget de color con opciones de clic derecho (borrar, copiar, pegar)
* &amp;lbrack;UI&amp;rbrack; Opción Nuevo widget de imagen con la herramienta de pintura
* &amp;lbrack;UI&amp;rbrack; Pintar sobre una imagen importada en un widget de imagen
* &amp;lbrack;Procesando&amp;rbrack; Nueva posición de cámara predeterminada
* &amp;lbrack;Exportar&amp;rbrack; Los archivos de Substance se exportan para Substance Designer 2020.1.2 (10.1.2)
* &amp;lbrack;Rendimiento&amp;rbrack; Mejor tiempo de inicio de la aplicación
* &amp;lbrack;Rendimiento&amp;rbrack; Mejorar la gestión de tareas asincrónicas
* &amp;lbrack;Rendimiento&amp;rbrack; Mejorar el rendimiento de la pila de capas al añadir, eliminar o mover capas
* &amp;lbrack;Rendimiento&amp;rbrack; De imagen a material (con tecnología de IA) se ejecuta más rápido en las GPU RTX
* &amp;lbrack;Contenido&amp;rbrack; Nuevas mallas: Camiseta de mujer, Camiseta de hombre, Zapato
* &amp;lbrack;Contenido&amp;rbrack; Nuevo modo de fusión: fusión por canal
* &amp;lbrack;Contenido&amp;rbrack; Corrección del height de mezcla de opacidad con 2 nuevos parámetros (posición de height y escala de height)
* &amp;lbrack;Contenido&amp;rbrack; Añadir ajustes de Height en el modo Fusión de Height
* &amp;lbrack;Contenido&amp;rbrack; Opción Usar información de Height en Fusión de máscara personalizada
* &amp;lbrack;Contenido&amp;rbrack; Nueva herramienta de corrección de perspectiva
* &amp;lbrack;Contenido&amp;rbrack; Generador de motivos: añada un parámetro para invertir el motivo
* &amp;lbrack;Contenido&amp;rbrack; Generador de motivos - Añadir un nuevo parámetro Anular detalles de material
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de pegatinas
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de musgo
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de Grietas
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de Validación PBR
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de azulejos de piso
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Costura de tejido
* &amp;lbrack;Contenido&amp;rbrack; Atlas scatter: Añadir entrada de máscara personalizada para activar la opción de pintura
* &amp;lbrack;Contenido&amp;rbrack; Dirt: Añadir entrada de máscara personalizada para activar la opción de pintura
* &amp;lbrack;Contenido&amp;rbrack; Ajuste preestablecido de exportación CLO
* &amp;lbrack;Contenido&amp;rbrack; Ajuste preestablecido de exportación de VStitcher
* &amp;lbrack;Contenido&amp;rbrack; Los ajustes preestablecidos de HDRP de Unity exportan un detailMap

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Las imágenes importadas se cargan demasiadas veces
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al crear un parche de clonación en la parte inferior de la pila
* &amp;lbrack;Capas&amp;rbrack; Añadir un material en la parte inferior de la pila hace que sea inestable
* &amp;lbrack;Capas&amp;rbrack; Filtrar tras importar imágenes no funciona correctamente
* &amp;lbrack;Capas&amp;rbrack; el valor workflow_type no se actualiza al cambiar el flujo de trabajo entre proyectos con un filtro personalizado
* &amp;lbrack;Capas&amp;rbrack; Desactivar el botón &quot;Eliminar capa&quot; cuando no hay ninguna capa seleccionada
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al cargar un recurso que contiene un parche de clonación
* &amp;lbrack;Capas&amp;rbrack; El filtro Normal a Height se bloquea en MacOs
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al cargar mapas de entorno hacia delante y hacia atrás
* &amp;lbrack;Aplicación&amp;rbrack; Problemas de rendimiento cuando se instala un controlador de la tableta gráfica
* &amp;lbrack;Aplicación&amp;rbrack; La importación de archivos EXR de 32 bits es negra
* &amp;lbrack;Aplicación&amp;rbrack; Se bloquea al cargar y descargar recursos
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al cambiar de explorar a crear
* &amp;lbrack;Aplicación&amp;rbrack; La colección de destino al guardar un material no es del proyecto actual
* &amp;lbrack;Aplicación&amp;rbrack; Corregir copia de seguridad y reiniciar
* &amp;lbrack;Importación de imágenes&amp;rbrack; Importar correctamente imágenes en escala de grises
* &amp;lbrack;Contenido&amp;rbrack; Nuevos filtros para el nuevo control de matrices
* &amp;lbrack;Contenido&amp;rbrack; Los filtros personalizados importados son visibles en la barra de acceso rápido
* &amp;lbrack;Contenido&amp;rbrack; Corrección del cambio de color con el filtro avanzado Hacer azulejo
* &amp;lbrack;Rendimiento&amp;rbrack; Abrir un cuadro de diálogo de color es lento y vuelve a calcular la capa actual
* &amp;lbrack;UI&amp;rbrack; Los métodos abreviados de teclado a veces no funcionan
* &amp;lbrack;2D View&amp;rbrack; El Relleno según el contenido necesita un primer clic inútil para funcionar
* &amp;lbrack;Resources&amp;rbrack; En las carpetas de los discos locales se sigue buscando actualizaciones después de quitarlas
* &amp;lbrack;Resources&amp;rbrack; Al eliminar una carpeta vinculada del sistema de archivos, no se elimina
* &amp;lbrack;Exportar&amp;rbrack; Los usos personalizados en los ajustes preestablecidos de exportación personalizados no se exportan
* &amp;lbrack;Exportar&amp;rbrack; No se puede exportar el archivo .sbsar con caracteres especiales en la ruta

**Problemas conocidos:**

* Los cálculos repetitivos de Imagen a material (con IA) pueden provocar un bloqueo (memoria insuficiente)
* Los cálculos repetitivos del Delighter pueden desencadenar un bloqueo (memoria insuficiente)
* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* El uso de Imagen a material (IA) en la GPU con poca VRAM puede provocar un bloqueo (memoria insuficiente)
* Imagen a material (con tecnología de IA) no está disponible en Specular/brillo PBR
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### 2.1.1 (2020.1.1) Tiramisu

*(Lanzado: 01 de abril de 2020)*

**Agregado:**

* &amp;lbrack;Proyecto&amp;rbrack; Exportación e importación de metadatos
* &amp;lbrack;Aplicación&amp;rbrack; Ctrl+S ahora guarda un ajuste preestablecido en Explorar
* &amp;lbrack;Rendimiento&amp;rbrack; Utilice la caché de procesamiento en lugar de volver a calcular los materiales guardados para resoluciones de hasta 2k

**Corregido:**

* &amp;lbrack;UI&amp;rbrack; Indicador de computación fija en la ventana gráfica
* &amp;lbrack;UI&amp;rbrack; La introducción de valores negativos en los reguladores es fija
* &amp;lbrack;UI&amp;rbrack; Cuadros combinados: las flechas del teclado y la barra de desplazamiento ahora funcionan
* &amp;lbrack;UI&amp;rbrack; Mantenga el canal seleccionado al cambiar entre &quot;salidas de material&quot; y &quot;entradas de capa&quot; en la vista 2D
* &amp;lbrack;Capas&amp;rbrack; Se ha corregido el bloqueo al añadir canales personalizados en Material base
* &amp;lbrack;Capas&amp;rbrack; Bloqueo al manipular capas
* &amp;lbrack;Capas&amp;rbrack; Los canales personalizados no se muestran con un material guardado
* &amp;lbrack;Aplicación&amp;rbrack; Se ha corregido un bloqueo raro al importar un activo
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al salir
* &amp;lbrack;Aplicación&amp;rbrack; Los cuadros combinados ahora muestran los valores correctos al cambiar los ajustes preestablecidos
* &amp;lbrack;Exportar&amp;rbrack; Ajuste preestablecido de Enscape renombrado a Enscape Revit
* &amp;lbrack;Exportar&amp;rbrack; La importación de un ajuste preestablecido de exportación después de eliminarlo funciona
* &amp;lbrack;Exportar&amp;rbrack; Bloqueo al exportar
* &amp;lbrack;Procesando&amp;rbrack; Se ha corregido el procesamiento cuando el color base está en formato de flotador medio de 16 bits
* &amp;lbrack;Proyecto&amp;rbrack; No se bloquea al importar un paquete dañado
* &amp;lbrack;Proyecto&amp;rbrack; Controle la migración de 2019.1.4 a 2.x.x cuando Create nunca se ha abierto
* &amp;lbrack;Proyecto&amp;rbrack; Solucionar un bloqueo al importar el mismo proyecto dos veces
* &amp;lbrack;Proyecto&amp;rbrack; Solucionar un bloqueo al importar proyectos
* &amp;lbrack;Resources&amp;rbrack; Los filtros personalizados importados en versiones anteriores funcionan
* &amp;lbrack;Resources&amp;rbrack; Los materiales con el mismo nombre ya no se borran entre sí
* &amp;lbrack;Resources&amp;rbrack; Bloqueo al vincular una carpeta local
* &amp;lbrack;Resources&amp;rbrack; Las carpetas creadas por el usuario de materiales de inicio ya no se eliminan después de reiniciar
* &amp;lbrack;Inspire&amp;rbrack; Corregir el área de colocación de material/colección y agregar un mensaje de advertencia si se utiliza un material no guardado

**Problemas conocidos:**

* Los filtros de relleno según el contenido son lentos en alta resolución
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador

### 2.1.0 (2020.1.0) Tiramisu

*(Lanzado: 12 de marzo de 2020)*

**Agregado:**

* &amp;lbrack;Exportar&amp;rbrack; Exportar selección de ajustes preestablecidos para empaquetar texturas para procesadores y motores de juegos
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Unreal Engine 4
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Unity Standard
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Unity HDRP
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Ciclos de fusión/Eve
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Arnold 5
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido al procesador de Corona
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Enscape
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Keyshot 9
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Redshift
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Vray Siguiente
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Lens Studio
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Spark AR Studio
* &amp;lbrack;Exportar&amp;rbrack; Exportar ajuste preestablecido a Brillo de Specular PBR desde Rugosidad metálica PBR
* &amp;lbrack;Exportar&amp;rbrack; Nueva interfaz de exportación
* &amp;lbrack;Exportar&amp;rbrack; Recordar ajustes de exportación
* &amp;lbrack;Exportar&amp;rbrack; Importar y administrar los ajustes preestablecidos de exportación personalizados
* &amp;lbrack;Exportar&amp;rbrack; Eliminar y reemplazar los ajustes preestablecidos de exportación personalizados
* &amp;lbrack;Exportar&amp;rbrack; Cambie el nombre de los ajustes preestablecidos de exportación personalizados
* &amp;lbrack;Exportar&amp;rbrack; Establecer la resolución de exportación predeterminada en la resolución actual
* &amp;lbrack;Exportar&amp;rbrack; Añada la opción de crear una subcarpeta a la ubicación de exportación
* &amp;lbrack;Exportar&amp;rbrack; Mensaje de advertencia antes de reemplazar archivos existentes
* &amp;lbrack;Aplicación&amp;rbrack; Nuevo esquema de numeración de versiones
* &amp;lbrack;Aplicación&amp;rbrack; Abra Crear al iniciar y cambie el orden de los laboratorios
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Nuevo banner de bienvenida
* &amp;lbrack;Proyecto&amp;rbrack; Abrir el último proyecto al iniciar
* &amp;lbrack;UI&amp;rbrack; Nuevo estilo de cuadro combinado
* &amp;lbrack;2D view&amp;rbrack; Método abreviado F para enfocar en la vista 2D
* &amp;lbrack;Filters&amp;rbrack; Se ha agregado la compatibilidad con la etiqueta alchemist::parameterVisibility en los gráficos de Substance
* &amp;lbrack;Filters&amp;rbrack; Realizar un ajuste global para administrar la visibilidad de los parámetros en función del flujo de trabajo
* &amp;lbrack;Resources&amp;rbrack; Nueva opción de línea de comandos para configurar recursos y carpetas vinculadas con un archivo de configuración
* &amp;lbrack;Comprobador de versiones&amp;rbrack; Configuración de la comprobación de la versión
* &amp;lbrack;Contenido&amp;rbrack; Nuevos materiales de arranque
* &amp;lbrack;Contenido&amp;rbrack; Bitmap para material: añada la posibilidad de definir el canal metálico (importación de imágenes uniforme y personalizada, selección de color).
* &amp;lbrack;Contenido&amp;rbrack; Ajuste : añada la compatibilidad con el flujo de trabajo de specular/brillo de PBR
* &amp;lbrack;Contenido&amp;rbrack; Atlas scatter - Nuevos parámetros

**Corregido:**

* &amp;lbrack;Proyecto&amp;rbrack; Bloqueo al importar el mismo proyecto dos veces
* &amp;lbrack;Proyecto&amp;rbrack; Se ha corregido el bloqueo al importar y abrir proyectos varias veces
* &amp;lbrack;Aplicación&amp;rbrack; Bloqueo al cargar un material sin nombre
* &amp;lbrack;Aplicación&amp;rbrack; Reconocer los archivos que faltan al volver a importarlos
* &amp;lbrack;Aplicación&amp;rbrack; Solucionar bloqueo aleatorio al apagar
* &amp;lbrack;Aplicación&amp;rbrack; Se ha corregido un raro bloqueo al descargar un material en Crear
* &amp;lbrack;Aplicación&amp;rbrack; Se ha corregido un bloqueo aleatorio al utilizar controles de IU
* &amp;lbrack;Aplicación&amp;rbrack; Se ha corregido la exportación de archivos de registro al escritorio en Windows 10
* &amp;lbrack;UI&amp;rbrack; El panel Exportar tiene un tamaño incorrecto al abrirlo en Crear
* &amp;lbrack;UI&amp;rbrack; Abrir proyecto con un solo clic
* &amp;lbrack;UI&amp;rbrack; Definición correcta de los valores mínimo y máximo del regulador
* &amp;lbrack;UI&amp;rbrack; Mostrar la etiqueta de los usos del canal en lugar de los ID
* &amp;lbrack;UI&amp;rbrack; Al hacer clic en un material, siempre se abre o cierra el panel de ajustes
* &amp;lbrack;UI&amp;rbrack; Corregir colores de capas ocultas
* &amp;lbrack;UI&amp;rbrack; Mejoras en los botones de pantalla de bienvenida
* &amp;lbrack;Capas&amp;rbrack; Menos cálculos innecesarios
* &amp;lbrack;Capas&amp;rbrack; Se bloquea al utilizar el parche de clonación
* &amp;lbrack;Capas&amp;rbrack; La selección de una capa de importación de imágenes ya no activa un equipo
* &amp;lbrack;Capas&amp;rbrack; Las capas Clonar parche y Relleno según el contenido ya no se vuelven a calcular cuando se seleccionan
* &amp;lbrack;Configuración del canal&amp;rbrack; La activación o desactivación de usos ahora activa un procesamiento
* &amp;lbrack;Resources&amp;rbrack; Evitar el bloqueo al hacer clic de forma masiva en una pila de la biblioteca
* &amp;lbrack;Resources&amp;rbrack; Se produce un impacto en el rendimiento al volver a añadir una carpeta vinculada previamente añadida
* &amp;lbrack;Resources&amp;rbrack; Se ha corregido un bloqueo al intentar abrir un archivo .sbsar eliminado.
* &amp;lbrack;Rendimiento&amp;rbrack; Evite cargar materiales para acceder a sus parámetros
* &amp;lbrack;Rendimiento&amp;rbrack; Realizar copia de seguridad de activos solo cuando se utilizan en un proyecto o en un material creado
* &amp;lbrack;Exportar&amp;rbrack; En ocasiones, los materiales corregidos de la cola de exportación se omiten o se exportan con parámetros incorrectos
* &amp;lbrack;2D View&amp;rbrack; Panorámica y zoom restaurados
* &amp;lbrack;Contenido&amp;rbrack; Parquet Patrón tiene en cuenta el canal de Oclusión ambiental
* &amp;lbrack;Contenido&amp;rbrack; Paint: muestra la entrada de máscara al activar la máscara personalizada
* &amp;lbrack;Contenido&amp;rbrack; Patrón de Stonewall - Eliminar posibles efectos de bandas en el mapa normal
* &amp;lbrack;Contenido&amp;rbrack; Modulación de height: Corregir entradas de color de base doble en la vista 2D

**Problemas conocidos:**

* Los filtros de relleno según el contenido son lentos en alta resolución
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador

## Versión 1

### 1.1.4 (2019.1.4) Sésamo

*(Lanzado: 30 de enero de 2020)*

**Agregado:**

* &amp;lbrack;Resources&amp;rbrack; Mensaje de confirmación al borrar una carpeta de recursos

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Mover capas a dos o más capas superiores o inferiores
* &amp;lbrack;Crear&amp;rbrack; Asignación de suficiente presupuesto de VRAM para tener un buen rendimiento

**Problemas conocidos:**

* Importar una gran cantidad de recursos puede ralentizar al Substance Alchemist
* Los filtros de relleno según el contenido son lentos en alta resolución
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a Height puede bloquearse en MacOS

### 1.1.3 (2019.1.3) Sésamo

*(Lanzado: 28 de enero de 2020)*

**Agregado:**

* &amp;lbrack;Flujo de trabajo&amp;rbrack; Compatibilidad con varios flujos de trabajo
* &amp;lbrack;Flujo de trabajo&amp;rbrack; Compatibilidad con el flujo de trabajo Brillo de Specular PBR
* &amp;lbrack;Flujo de trabajo&amp;rbrack; Nuevo panel Configuración de canal
* &amp;lbrack;Flujo de trabajo&amp;rbrack; Selección de flujo de trabajo en la creación de proyectos
* &amp;lbrack;Configuración de canal&amp;rbrack; Activar o desactivar cálculo de canal específico
* &amp;lbrack;Configuración de canal&amp;rbrack; Mostrar la lista de canales personalizados disponibles en el material actual
* &amp;lbrack;Configuración de canal&amp;rbrack; Cálculo automático de canales personalizados cuando sea necesario
* &amp;lbrack;Configuración de canal&amp;rbrack; Forzar/Bloquear el cálculo de canales personalizados
* &amp;lbrack;Capas&amp;rbrack; Nueva interfaz de usuario del marcador de posición de entrada de material en los filtros de Atlas scatter y salpicaduras
* &amp;lbrack;Capas&amp;rbrack; El parámetro de entrada de imagen de un filtro se puede alimentar debajo de las capas
* &amp;lbrack;Capas&amp;rbrack; Mostrar una notificación cuando algunas capas no estén actualizadas
* &amp;lbrack;Capas&amp;rbrack; Posibilidad de actualizar a la última versión de las capas obsoletas a través de la notificación
* &amp;lbrack;Proyecto&amp;rbrack; Nuevos campos de metadatos en la creación de proyectos
* &amp;lbrack;Inspire&amp;rbrack; Las variaciones generadas son específicas de un proyecto
* &amp;lbrack;2D View&amp;rbrack; Cambiar entre las entradas de capa, las salidas de capa y las salidas de material
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Opción Agregar proyecto de importación (.alch)
* &amp;lbrack;Preferencias&amp;rbrack; Nueva ventana Preferencias para definir la configuración de privacidad de análisis y ubicación de la caché
* &amp;lbrack;UI&amp;rbrack; Nuevos botones de IU
* &amp;lbrack;Rendimiento&amp;rbrack; Mejora global del sistema de paralelización
* &amp;lbrack;Rendimiento&amp;rbrack; Optimización del número de equipos de materiales
* &amp;lbrack;Motor&amp;rbrack; Actualización del Substance Engine
* &amp;lbrack;Framework&amp;rbrack; Actualización a Qt 5.13
* &amp;lbrack;MacOS&amp;rbrack; Mejoras globales de la compatibilidad con macOS Catalina
* &amp;lbrack;Contenido&amp;rbrack; Filtro de ajuste: intensidad normal y parámetros de inversión

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Anular la configuración del parámetro Entrada de imagen al eliminar la capa
* &amp;lbrack;Capas&amp;rbrack; Corrección de un bloqueo al añadir una capa de parche de clonación
* &amp;lbrack;Capas&amp;rbrack; Solucionar algunos bloqueos al mezclar capas y apilar materiales en otros materiales de pila de capas
* &amp;lbrack;Exportar&amp;rbrack; Ahora se respeta la selección de canales para la exportación
* &amp;lbrack;Resources&amp;rbrack; No se bloquea al navegar por el panel Recursos
* &amp;lbrack;Resources&amp;rbrack; Solucionar bloqueo al importar archivos de Substance dañados
* &amp;lbrack;Resources&amp;rbrack; Reducir el número de bloqueos al cargar carpetas grandes
* &amp;lbrack;Miniatura&amp;rbrack; El cálculo de miniaturas no bloquea la interfaz
* &amp;lbrack;Importación de imágenes&amp;rbrack; Uniformización del tipo de imagen compatible en toda la aplicación
* &amp;lbrack;Preset&amp;rbrack; Guardar la descripción al crear un ajuste preestablecido desde una SBSAR
* &amp;lbrack;Inspire&amp;rbrack; Corrección de arrastrar y soltar imágenes
* &amp;lbrack;Aplicación&amp;rbrack; Solucionar bloqueos al salir
* &amp;lbrack;Aplicación&amp;rbrack; Solucionar bloqueos al salir al exportar materiales
* &amp;lbrack;UI&amp;rbrack; Correcciones y mejoras
* &amp;lbrack;UI&amp;rbrack; Cambiar el nombre del activo temporal a &quot;material no guardado&quot;
* &amp;lbrack;Contenido&amp;rbrack; Actualización global y limpieza de todos los filtros

**Problemas conocidos:**

* Importar una gran cantidad de recursos puede ralentizar al Substance Alchemist
* Los filtros de relleno según el contenido son lentos en alta resolución
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a Height puede bloquearse en MacOS

### 1.1.2 (2019.1.2) Sesame

*(Lanzado: 11 de diciembre de 2019)*

**Agregado:**

* &amp;lbrack;Capas&amp;rbrack; Se puede acceder a las opciones Guardar y Guardar como desde la interfaz de la barra de herramientas de la pila de capas
* &amp;lbrack;Resources&amp;rbrack; Limpieza de la ruta de exploración en el panel Recursos para desplazarse por las carpetas
* &amp;lbrack;Resources&amp;rbrack; Botón Mantener atrás pulsado para acceder a todas las carpetas superiores
* &amp;lbrack;Resources&amp;rbrack; Opción Añadir recarga de materiales importados para actualizarlos a la última versión
* &amp;lbrack;Capas&amp;rbrack; Posibilidad de cambiar la imagen en la capa de importación de imágenes
* &amp;lbrack;Capas&amp;rbrack; Posibilidad de definir una imagen como canal (color base, normal, height,...) en la capa de importación de imágenes
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de Atlas scatter para la dispersión de nuevos elementos de atlas desde Substance Source
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Efecto Pintura al óleo
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Generación de canales para generar height, oclusión de ambiente y rugosidad a partir de mapas normales y de color base

**Corregido:**

* &amp;lbrack;UI&amp;rbrack; Reactivar información sobre herramientas en la barra de herramientas de la pila Capas
* &amp;lbrack;UI&amp;rbrack; Solucionar problema al escribir dos decimales en un valor del regulador
* &amp;lbrack;Rendimiento&amp;rbrack; Solucionar bloqueo al cambiar rápidamente de un material a otro
* &amp;lbrack;Exportar&amp;rbrack; El cambio a otro material antes del final de una exportación ya no se bloquea
* &amp;lbrack;Resources&amp;rbrack; El menú contextual se muestra en la parte superior del material al hacer clic con el botón derecho en él
* &amp;lbrack;Capas&amp;rbrack; El vínculo &quot;Haga clic aquí&quot; funciona cuando la pila de capas está vacía
* &amp;lbrack;Ajustes preestablecidos&amp;rbrack; El botón Quitar guardar del panel de ajustes cuando se trata de un material creado en Alchemist
* &amp;lbrack;Tweak&amp;rbrack; Mensaje de información que se muestra cuando es un material creado en Alchemist
* &amp;lbrack;Viewport&amp;rbrack; El valor predeterminado de la textura del Specular level se corrige a 0,04
* &amp;lbrack;Menú Archivo&amp;rbrack; Opción Corregir y cambiar nombre Guardar y guardar como
* &amp;lbrack;Motor&amp;rbrack; Actualice la versión del motor de Substance para evitar el bloqueo de algunos archivos SBSAR durante la importación.
* &amp;lbrack;Contenido&amp;rbrack; El filtro de mosaico funciona en el canal de oclusión ambiente
* &amp;lbrack;Contenido&amp;rbrack; El filtro Recortar funciona en el canal de oclusión de ambiente
* &amp;lbrack;Contenido&amp;rbrack; Filtro de agua modifica el mapa de height
* &amp;lbrack;Contenido&amp;rbrack; Mosaico correcto del material superior en el modo de fusión de opacidad
* &amp;lbrack;Contenido&amp;rbrack; El height del material superior se conserva en el modo de fusión de opacidad
* &amp;lbrack;Contenido&amp;rbrack; Posibilidad de añadir una máscara personalizada, un motivo personalizado o un mapa de escala en el filtro de perforación
* &amp;lbrack;Contenido&amp;rbrack; Height El filtro de modulación fuerza el height y los mapas normales en 16 bits
* &amp;lbrack;Contenido&amp;rbrack; El filtro de ajuste fuerza el height y los mapas normales en 16 bits

**Problemas conocidos:**

* Importar una gran cantidad de recursos puede ralentizar al Substance Alchemist
* Los filtros de relleno según el contenido son lentos en alta resolución
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a Height puede bloquearse en MacOS

### 1.1.1 (2019.1.1) Sésamo

*(Lanzado: 26 de noviembre de 2019)*

**Agregado:**

* &amp;lbrack;Fusionar&amp;rbrack; Nuevo modo de fusión de opacidad
* &amp;lbrack;Motor&amp;rbrack; Nueva versión de Substance Engine

**Corregido:**

* &amp;lbrack;Capas&amp;rbrack; Solucionar el bloqueo al eliminar una capa que aún se está calculando
* &amp;lbrack;Capas&amp;rbrack; Solucionar el bloqueo al eliminar la capa inferior
* &amp;lbrack;Capas&amp;rbrack; Solucionar bloqueo mientras el nombre del material contiene caracteres especiales
* &amp;lbrack;Capas&amp;rbrack; Detener el cálculo de todos los filtros que utilizan un widget
* &amp;lbrack;Capas&amp;rbrack; Evite el bloqueo al utilizar los filtros Clonar parche y Relleno según el contenido
* &amp;lbrack;Capas&amp;rbrack; Solucionar el bloqueo al arrastrar y soltar un filtro en ranuras de entrada de salpicaduras
* &amp;lbrack;Resources&amp;rbrack; Solucionar el bloqueo al vincular carpetas locales o importar recursos en Substance Alchemist
* &amp;lbrack;Colección&amp;rbrack; Solucionar el bloqueo al cambiar rápidamente de un material a otro
* &amp;lbrack;UI&amp;rbrack; Se ha solucionado el bloqueo si el valor es nulo o no es válido en los reguladores de mosaico y desplazamiento de la ventana gráfica.
* &amp;lbrack;Inspire&amp;rbrack; Solucionar el bloqueo al acceder a la pestaña Inspirar
* &amp;lbrack;Inspire&amp;rbrack; Solucionar el bloqueo al inspirar en un material de pila de capas recién guardado
* &amp;lbrack;Rendimiento&amp;rbrack; Los materiales y filtros Substance pesados (segmentación) calculan más rápido
* &amp;lbrack;Ayuda&amp;rbrack; Corregir archivo de registro de exportación
* &amp;lbrack;Contenido&amp;rbrack; El filtro aleatorio funciona en todos los canales
* &amp;lbrack;Contenido&amp;rbrack; El flujo de trabajo multiangular tiene en cuenta todas las digitalizaciones
* &amp;lbrack;Contenido&amp;rbrack; Mezcla correcta de AO
* &amp;lbrack;Contenido&amp;rbrack; Fusión de curvatura fusión correcta
* &amp;lbrack;Contenido&amp;rbrack; Fusión correcta de fusión de ID de color
* &amp;lbrack;Contenido&amp;rbrack; Fusión de máscara personalizada fusión correcta
* &amp;lbrack;Contenido&amp;rbrack; Corregir filtro de ajuste para modificación de rugosidad
* &amp;lbrack;Contenido&amp;rbrack; Corregir filtro de Material base para la carga de canales normales personalizados
* &amp;lbrack;Contenido&amp;rbrack; Corregir el patrón de importación personalizado del filtro Relieve

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a Height puede bloquearse en MacOS

### 1.1.0 (2019.1.0) Sésamo

*(Lanzado: 04 de noviembre de 2019)*

**Agregado:**

* &amp;lbrack;Proyecto&amp;rbrack; Creación de un proyecto
* &amp;lbrack;Proyecto&amp;rbrack; Introducción al formato de archivo .alch que contiene los datos del proyecto
* &amp;lbrack;Proyecto&amp;rbrack; Exportar un proyecto .alch que contenga las colecciones y sus materiales
* &amp;lbrack;Proyecto&amp;rbrack; Importar un proyecto .alch
* &amp;lbrack;Proyecto&amp;rbrack; Abrir proyectos recientes
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Se muestra una pantalla de bienvenida al iniciar
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Crear un proyecto desde la pantalla de bienvenida
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Acceda a la lista de todos sus proyectos en la pantalla de bienvenida
* &amp;lbrack;Pantalla de bienvenida&amp;rbrack; Enlaces rápidos para acceder a la documentación, la información acerca de la gestión de licencias y ventanas emergentes
* &amp;lbrack;Menú Archivo&amp;rbrack; Integración de un menú de archivo
* &amp;lbrack;Menú Archivo&amp;rbrack; Acceda a los comandos del proyecto desde la pestaña Archivo y guarde la pila de capas
* &amp;lbrack;Menú Archivo&amp;rbrack; Acceder a los comandos de deshacer y rehacer desde la pestaña Editar
* &amp;lbrack;Menú Archivo&amp;rbrack; El menú Ayuda anterior se trasladó al menú Archivo de la ficha Ayuda
* &amp;lbrack;Capas&amp;rbrack; Nueva arquitectura de la pila de capas
* &amp;lbrack;Capas&amp;rbrack; Nueva interfaz de usuario de la pila de capas
* &amp;lbrack;Capas&amp;rbrack; Seleccione el modo de fusión directamente en la barra de herramientas
* &amp;lbrack;Capas&amp;rbrack; Acceda por separado a los parámetros de mezcla y a los parámetros de material
* &amp;lbrack;Capas&amp;rbrack; Añade materiales directamente en entradas dedicadas del filtro Salpicadura en la pila de capas
* &amp;lbrack;Capas&amp;rbrack; Cambiar el orden de digitalización directamente en la capa de importación de imágenes
* &amp;lbrack;Viewport&amp;rbrack; Control del campo de visión de la cámara
* &amp;lbrack;Viewport&amp;rbrack; Posibilidad de cambiar entre cámara ortográfica o de perspectiva
* &amp;lbrack;Viewport&amp;rbrack; Mostrar la información de resolución y profundidad de bits de cada canal
* &amp;lbrack;Resources&amp;rbrack; Materiales base se abre de forma predeterminada
* &amp;lbrack;Caché&amp;rbrack; Localizar la carpeta de caché de miniaturas
* &amp;lbrack;Caché&amp;rbrack; Localizar la carpeta de caché de procesamiento
* &amp;lbrack;Panels&amp;rbrack; El panel Ajustes de material está oculto temporalmente
* &amp;lbrack;Flujo de trabajo&amp;rbrack; Specular/Brillo desactivado temporalmente
* &amp;lbrack;MacOS&amp;rbrack; Notarización de la versión del sistema operativo Catalina
* &amp;lbrack;Contenido&amp;rbrack; Nueva versión del filtro Delighter
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Relleno según el contenido de imagen
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Relleno según el contenido de material
* &amp;lbrack;Contenido&amp;rbrack; El filtro Transformar tiene una opción de transformación segura

**Corregido:**

* Todos los errores anteriores relacionados con Create no son válidos hoy con la nueva versión de la interfaz de usuario y la arquitectura
* La información sobre herramientas no oculta los iconos de la barra superior (3D, 2D, 2D/3D)
* &amp;lbrack;Contenido&amp;rbrack; Splatter filter acepta Atlas con mapa de height completo
* &amp;lbrack;Contenido&amp;rbrack; El filtro de transformación funciona en imágenes (scan1, scan2,...)

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a Height puede bloquearse en MacOS

## Beta

### 0.8.1-beta Quinua

*(Lanzado: 19 de agosto de 2019)*

**Agregado:**

* Posibilidad de enviar recursos de Substance Source desde el iniciador al Substance Alchemist de proyectos

**Corregido:**

* &amp;lbrack;Crear&amp;rbrack; Algunos filtros se enumeraron en el descriptor de acceso rápido, pero no en el panel de filtros
* &amp;lbrack;MacOS&amp;rbrack; Se han solucionado algunos bloqueos al salir

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* No se recomienda el cambio de visibilidad rápida de una etapa de Delighter
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a height puede bloquearse en MacOS
* Todavía se puede bloquear aleatoriamente al salir de MacOS

### 0.8.0-beta Quinua

*(Lanzado: 08 de agosto de 2019)*

**Agregado:**

* &amp;lbrack;Resources&amp;rbrack; Conectar y reflejar las carpetas de materiales en los discos locales
* &amp;lbrack;Resources&amp;rbrack; Examine las carpetas de materiales y sus subcarpetas
* &amp;lbrack;Resources&amp;rbrack; Separe el panel de recursos materiales en una ventana independiente para ver los recursos en pantalla completa
* &amp;lbrack;Resources&amp;rbrack; Nuevo diseño del panel Recursos para admitir la navegación por carpetas y subcarpetas
* &amp;lbrack;Resources&amp;rbrack; Utilizar la ruta de exploración para desplazarse por las carpetas
* &amp;lbrack;Resources&amp;rbrack; Fuerce la sincronización de la carpeta local con la opción Sincronizar accesible haciendo clic con el botón derecho
* &amp;lbrack;Resources&amp;rbrack; Desconectar la carpeta local con la opción Desconectar disponible haciendo clic con el botón derecho
* &amp;lbrack;Administrar&amp;rbrack; Visualización de etiquetas incrustadas de archivos de Substance
* &amp;lbrack;Administrar&amp;rbrack; Añade, edita y elimina etiquetas de tus materiales
* &amp;lbrack;Administrar&amp;rbrack; Califica tus materiales
* &amp;lbrack;Capas&amp;rbrack; Salida de panorama de soporte
* &amp;lbrack;Capas&amp;rbrack; Puede eliminar las entradas de imagen en la capa de importación de imágenes
* &amp;lbrack;Capas&amp;rbrack; Selección automática de la nueva capa añadida
* &amp;lbrack;Capas&amp;rbrack; Selección automática de la capa inferior después de eliminar una capa
* &amp;lbrack;UX&amp;rbrack; Mantener la visibilidad de los paneles izquierdos al cambiar a otro laboratorio
* &amp;lbrack;UX&amp;rbrack; No cree una capa base ni abra la ventana emergente de flujo de trabajo de material al importar imágenes en una pila de capas no vacías
* &amp;lbrack;UI&amp;rbrack; Nuevo estilo de TextField
* &amp;lbrack;UI&amp;rbrack; Nuevo estilo de SearchBox
* &amp;lbrack;UI&amp;rbrack; Nuevo estilo de encabezado de panel
* &amp;lbrack;UI&amp;rbrack; Nuevo estilo de indicador Ocupado
* &amp;lbrack;UI&amp;rbrack; Nuevo estilo de fondo de pila de capas
* &amp;lbrack;UI&amp;rbrack; Usar fuente de Adobe Clean
* &amp;lbrack;UI&amp;rbrack; Eliminar marcador de posición del icono de cuentagotas del parámetro de entrada de color
* &amp;lbrack;Rendimiento&amp;rbrack; Optimización del indicador Ocupado
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Generador de motivos
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de desenfoque

**Corregido:**

* &amp;lbrack;Inspire&amp;rbrack; Solucionar bloqueo al utilizar más de 10 colores
* &amp;lbrack;2D View&amp;rbrack; Corrección de la barra de desplazamiento en la lista de canales de la vista 2D
* &amp;lbrack;Visor&amp;rbrack; Solucionar bloqueo al importar un mapa de entorno que no es de alimentación 2
* &amp;lbrack;Contenido&amp;rbrack; Corrección en la importación de PNG para el patrón personalizado de filtros de relieve y perforación
* &amp;lbrack;Exportar&amp;rbrack; Corrección de la exportación normal y de height de 16 bits por canal
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

### 0.7.0-beta Pepper

*(Lanzado: 13 de junio de 2019)*

**Agregado:**

* &amp;lbrack;Filters&amp;rbrack; Acceda rápidamente a los filtros pulsando la barra espaciadora
* &amp;lbrack;Filters&amp;rbrack; Nuevo panel dedicado para administrar, examinar e importar sus filtros
* &amp;lbrack;Metadatos&amp;rbrack; Haga clic con el botón derecho en un material para ver sus metadatos
* &amp;lbrack;Metadatos&amp;rbrack; Haga clic con el botón derecho en un material para ver su ubicación en el disco
* &amp;lbrack;Reguladores&amp;rbrack; Animación de los controles deslizantes al pasar el puntero sobre ellos pulsando Ctrl
* &amp;lbrack;Reguladores&amp;rbrack; Detenga y reinicie la animación de los reguladores pulsando P
* &amp;lbrack;Exportar&amp;rbrack; La exportación SBSAR sigue las directrices del Substance Source
* &amp;lbrack;Licencia&amp;rbrack; Activar Substance Alchemist mediante una variable de entorno
* &amp;lbrack;UX&amp;rbrack; El cuadro de diálogo Archivo recuerda la última ruta de archivo seleccionada
* &amp;lbrack;UX&amp;rbrack; El cuadro de diálogo Carpeta recuerda la última ruta de carpeta seleccionada
* &amp;lbrack;UI&amp;rbrack; Actualizar IU del panel Recursos
* &amp;lbrack;UI&amp;rbrack; Actualizar IU de la barra de búsqueda
* &amp;lbrack;UI&amp;rbrack; Se actualiza el icono Crear nuevo material
* &amp;lbrack;Ayuda&amp;rbrack; Las direcciones URL se actualizan al dominio substance3d.com
* &amp;lbrack;Malla&amp;rbrack; Ya hay disponible una malla de tela
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de corrosión
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de oxidación
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de musgo
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de Dust
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de patrón de pared metálica
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de patrón de Stonewall
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de acabado de madera
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de acabado metálico
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de Snow
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro aleatorio
* &amp;lbrack;Contenido&amp;rbrack; Ahora puede importar sus texturas directamente en el filtro de Material base

**Corregido:**

* Solucionar un bloqueo al guardar la pila de capas
* Se puede añadir un valor por encima de 1 en el regulador de rotación de entorno
* No pierda parámetros de fusión cuando una capa de fusión se transforme de una capa de fusión a otra de una capa de material
* Corregir duplicados al generar variaciones de la misma pila de capas varias veces
* Al volver a abrir un material, Alchemist recuerda los rangos modificados (mínimo y máximo) de los reguladores

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* No se recomienda el cambio de visibilidad rápida de una etapa de Delighter
* La importación de entorno personalizado puede volverse negra
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a height puede bloquearse en MacOS

### 0.6.1-beta Orange

*(Lanzado: 13 de junio de 2019)*

**Agregado:**

* &amp;lbrack;Motor&amp;rbrack; La actualización de Substance Engine será compatible con la última versión de Substance Designer
* &amp;lbrack;Licencia&amp;rbrack; Actualizar la carpeta de licencias para las primeras instalaciones
* &amp;lbrack;Capas&amp;rbrack; Vuelva a cargar en cualquier momento la pila de capas para actualizar los filtros personalizados

**Corregido:**

* &amp;lbrack;Compatibilidad de datos&amp;rbrack; Corrección preventiva para limitar la corrupción de datos en el momento de la actualización

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* No se recomienda el cambio de visibilidad rápida de una etapa de Delighter
* La importación de entorno personalizado puede volverse negra
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador

### 0.6.0-beta Orange

*(Lanzado: 18 de abril de 2019)*

**Agregado:**

* &amp;lbrack;Metadatos&amp;rbrack; Ver y rellenar metadatos de materiales en una pestaña dedicada
* &amp;lbrack;Colección&amp;rbrack; Crear una colección directamente desde los resultados de búsqueda
* &amp;lbrack;Publicación de medios&amp;rbrack; Exportación de un tablero de una colección
* &amp;lbrack;UX&amp;rbrack; Deshacer un cambio de ajuste o importación de imágenes pulsando Ctrl+Z
* &amp;lbrack;UX&amp;rbrack; Rehacer un cambio de ajuste o importación de imágenes pulsando Ctrl+Mayús+Z
* &amp;lbrack;UI&amp;rbrack; Nuevos iconos con un nuevo estilo
* &amp;lbrack;Rendimiento&amp;rbrack; Nuevo Administrador de sesiones para gestionar mejor el cambio de pestañas
* &amp;lbrack;Rendimiento&amp;rbrack; Apertura más rápida de la capa de importación de imágenes
* &amp;lbrack;Contenido&amp;rbrack; Nuevo material genérico de metal
* &amp;lbrack;Contenido&amp;rbrack; Nuevo material de Óxido
* &amp;lbrack;Contenido&amp;rbrack; Nuevo material genérico de piedra
* &amp;lbrack;Contenido&amp;rbrack; Actualización del filtro de relieve
* &amp;lbrack;Contenido&amp;rbrack; Actualización del filtro de bordado
* &amp;lbrack;Contenido&amp;rbrack; Actualización del filtro de pintura
* &amp;lbrack;Contenido&amp;rbrack; Actualización del filtro Delighter

**Corregido:**

* &amp;lbrack;Contenido&amp;rbrack; El filtro de agua funciona en el flujo de trabajo Specular/Brillo
* Solucionar el botón de opción de escala de grises en la ventana emergente de activación
* Aceptar archivos que contengan caracteres de coma
* Solucionar problemas con fuentes pequeñas en ventanas emergentes
* Solucionar un problema de transparencia en la IU debido a un conflicto con el parámetro FXAA de algunas tarjetas NVIDIA
* Quitar el enfoque del campo después de introducir un valor en un regulador
* Asigne la cantidad mínima de VRAM al encendedor para reducir los bloqueos
* Corregir el bloqueo de la ventana al cambiar el tamaño de la ventana de la aplicación
* Se ha corregido un bloqueo que se producía al eliminar la pila de capas durante la evaluación

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* No se recomienda el cambio de visibilidad rápida de una etapa de Delighter
* La importación de entorno personalizado puede volverse negra
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador

### 0.5.4-beta Nacho

*(Lanzado: 26 de marzo de 2019)*

**Corregido:**

* &amp;lbrack;Pila&amp;rbrack; Bloqueo al eliminar una capa de salpicaduras
* &amp;lbrack;Datos&amp;rbrack; La base de datos de activos se daña cuando la aplicación se bloquea
* &amp;lbrack;Datos&amp;rbrack; El Substance Alchemist no se puede iniciar si la base de datos de recursos está dañada
* Bloqueo aleatorio al importar materiales de Substance

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento
* La importación de entorno personalizado puede volverse negra
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* La colección predeterminada para guardar puede estar vacía

### 0.5.3-beta Nacho

*(Lanzado: 19 de marzo de 2019)*

**Agregado:**

* Búsqueda por nombre de material en el panel Recursos
* &amp;lbrack;UI&amp;rbrack; Herramienta Clonar nueva interfaz de usuario con visualización del tamaño del pincel
* &amp;lbrack;UI&amp;rbrack; Selección y eliminación de etapas ocultas
* &amp;lbrack;UI&amp;rbrack; Nueva interfaz de usuario de TextField
* &amp;lbrack;Ayuda&amp;rbrack; Acceder a los sitios web de Substance Source, Substances shares y academias de Substance
* &amp;lbrack;Contenido&amp;rbrack; Nuevos materiales predeterminados con generadores y atlas
* &amp;lbrack;Contenido&amp;rbrack; Actualización de mapa de bits a material
* &amp;lbrack;Contenido&amp;rbrack; Actualización de dirt
* &amp;lbrack;Contenido&amp;rbrack; Actualización de óxido
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de relieve
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de bordado
* &amp;lbrack;Contenido&amp;rbrack; Nuevo Filtro erosionado
* &amp;lbrack;Contenido&amp;rbrack; Nuevo generador de grava
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de pintura
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de motivo de parquet
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de motivo de pavimento
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de perforación
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de salpicaduras
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de desgaste textil
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro Transformar

**Corregido:**

* &amp;lbrack;Viewport&amp;rbrack; Malla de esfera con mosaico x2 en X
* &amp;lbrack;Viewport&amp;rbrack; Bloqueo al cargar su propio entorno
* &amp;lbrack;Viewport&amp;rbrack; Los mapas de entorno están utilizando ahora el valor de exposición también
* &amp;lbrack;Viewport&amp;rbrack; El método abreviado F no restablece el ángulo de la cámara
* &amp;lbrack;Exportar&amp;rbrack; La exportación de SBS funciona con la última versión de Substance Designer 2018.3.3
* &amp;lbrack;Exportar&amp;rbrack; La exportación SBSAR respeta las mismas directrices que los materiales de Substance Source
* &amp;lbrack;UI&amp;rbrack; Las barras de desplazamiento se pueden arrastrar
* Se admiten caracteres especiales en las rutas de carpetas y archivos
* La miniatura se vuelve a generar al guardar el material

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento
* La importación de entorno personalizado puede volverse negra
* Las imágenes TIF no se muestran en el panel Propiedades de la capa de importación de imágenes
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* La colección predeterminada para guardar puede estar vacía

### 0.5.2-beta Nacho

*(Lanzado: 07 de marzo de 2019)*

**Agregado:**

* Detección y uso de la GPU de alto perfil

**Corregido:**

* El parámetro de rotación tiene un widget de regulador adecuado
* Corregir la visibilidad de la línea de color azul al arrastrar y soltar materiales
* Corrección de la fusión de materiales al colocar un material debajo de la primera capa
* Conectar las entradas de imagen sólo si no se ha definido una ruta de imagen personalizada

**Problemas conocidos:**

* Los caracteres especiales de la ruta de archivo impiden guardar un material
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento
* Bloqueo al cargar su propio entorno

### 0.5.1-beta Nacho

*(Lanzado: 4 de marzo de 2019)*

**Corregido:**

* Solucionar errores de informes de errores y licencias emergentes

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento
* Bloqueo al cargar su propio entorno

### 0.5.0-beta Nacho

*(Lanzado: 28 de febrero de 2019)*

**Agregado:**

* &amp;lbrack;Pila de capas&amp;rbrack; Reordenación de capas
* &amp;lbrack;Pila de capas&amp;rbrack; Eliminación de una capa oculta
* &amp;lbrack;Pila de capas&amp;rbrack; Importe un material directamente en la posición que desee
* &amp;lbrack;Pila de capas&amp;rbrack; Entrada de material como un nuevo tipo de parámetro de filtro
* &amp;lbrack;Rendimiento&amp;rbrack; El presupuesto del Substance Engine es dinámico para un mejor rendimiento
* &amp;lbrack;Rendimiento&amp;rbrack; Rendimiento de OpenGL mejorado especialmente en MacOS
* &amp;lbrack;Datos&amp;rbrack; Actualización de datos más rápida después del lanzamiento de una nueva versión
* &amp;lbrack;Contenido&amp;rbrack; AI Delighter disponible en Windows 7 y Windows 8
* &amp;lbrack;Contenido&amp;rbrack; AI Delighter disponible en la GPU RTX

**Corregido:**

* Solucionar posibles bloqueos al salir de la aplicación
* La ventana emergente de exportación se abre más rápido al exportar colecciones grandes

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento
* Bloqueo al cargar su propio entorno

### 0.4.0-beta Muffin

*(Lanzado: 17 de enero de 2019)*

**Agregado:**

* &amp;lbrack;Exportar&amp;rbrack; exportación del archivo de Substance (sbsar) de su colección
* &amp;lbrack;Exportar&amp;rbrack; exportación de archivos de Substance (sbs) de su colección
* &amp;lbrack;Exportar&amp;rbrack; Cola de exportación visible en el panel Exportar
* &amp;lbrack;Exportar&amp;rbrack; Asignar un nombre a la colección o material antes de la exportación
* &amp;lbrack;Datos&amp;rbrack; Guardar como material pulsando Ctrl+Mayús+S
* &amp;lbrack;Datos&amp;rbrack; Guarde el material pulsando Ctrl+S
* &amp;lbrack;Datos&amp;rbrack; Las colecciones y los materiales son compatibles entre versiones
* &amp;lbrack;Datos&amp;rbrack; Actualizar la pila de capas de material con filtros actualizados
* &amp;lbrack;Datos&amp;rbrack; Recarga en caliente de filtros personalizados importados
* &amp;lbrack;UI&amp;rbrack; Retroalimentación visual en la ventana gráfica mientras se está computando
* &amp;lbrack;UI&amp;rbrack; Nuevo estilo de botón
* &amp;lbrack;UI&amp;rbrack; La ventana emergente Guardar muestra el nombre de la colección activa
* &amp;lbrack;UI&amp;rbrack; Modificación de imágenes de origen de una capa de importación de imágenes
* &amp;lbrack;Contenido&amp;rbrack; Ahora se admiten usos personalizados
* &amp;lbrack;Contenido&amp;rbrack; Se admiten más formatos de imagen en los parámetros de entrada de imagen.
* &amp;lbrack;Contenido&amp;rbrack; Nuevo filtro de mosaico llamado Make It Tile Advanced
* &amp;lbrack;Contenido&amp;rbrack; Actualización del filtro de agua

**Corregido:**

* Mapa de bits a material controla el flujo de trabajo Specular/Brillo

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* Delighter no es compatible con tarjetas RTX GPU
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento

### 0.3.1-beta Lasaña

*(Lanzado: 17 de diciembre de 2018)*

**Corregido:**

* Generar una variación de color con 10 bloqueos extraídos de color
* Generar una variación de color con una pila de capas que se acaba de guardar se bloquea
* Vínculos incorrectos en la ventana emergente de actualización de la versión del Substance Alchemist

**Problemas conocidos:**

* El mapa de bits a material no gestiona el flujo de trabajo de Specular/Rugosidad
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento

### 0.3.0-beta Lasaña

*(Lanzado: 12 de diciembre de 2018)*

**Agregado:**

* &amp;lbrack;Exportar&amp;rbrack; Nueva ventana emergente de exportación
* &amp;lbrack;Exportar&amp;rbrack; Exportar una colección completa
* &amp;lbrack;Exportar&amp;rbrack; Exportar mapas de bits en el formato deseado
* &amp;lbrack;Exportar&amp;rbrack; Exporte mapas de bits con la resolución que desee
* &amp;lbrack;Exportar&amp;rbrack; Exporte solo los canales que desee
* &amp;lbrack;Exportar&amp;rbrack; Previsualizar el tamaño estimado de la exportación
* &amp;lbrack;Exportar&amp;rbrack; Previsualice el tamaño disponible en el disco antes de exportar
* &amp;lbrack;UX&amp;rbrack; Acciones en una colección accesibles haciendo clic con el botón derecho
* &amp;lbrack;UX&amp;rbrack; Permitir la desconfiguración de una imagen o un recurso en Inspire
* &amp;lbrack;UX&amp;rbrack; Substance Alchemist se inicia maximizado
* &amp;lbrack;Assets&amp;rbrack; Nueva forma de guardar tus materiales para mantenerlos persistentes con las próximas versiones
* &amp;lbrack;Ayuda&amp;rbrack; Acceso a la documentación en línea a través del menú de ayuda
* &amp;lbrack;Rendimiento&amp;rbrack; Variaciones de color más rápidas en materiales complejos creados con Substance Alchemist
* &amp;lbrack;Rendimiento&amp;rbrack; Reducir pérdidas de memoria al cambiar de laboratorio
* &amp;lbrack;Contenido&amp;rbrack; Comprobador de escala para diagnosticar el tamaño físico del material
* &amp;lbrack;Contenido&amp;rbrack; Actualizar Italien Venecia Mosaico material de baldosas
* &amp;lbrack;Contenido&amp;rbrack; Actualizar la salpicadura de musgo

**Corregido:**

* Se acabó el nombre predeterminado al guardar un material
* Los parámetros de filtros se pierden después de guardar un material y volver a abrir el Substance Alchemist
* &amp;lbrack;Contenido&amp;rbrack; Corrección desde la lógica inferior y superior para la fusión de AO y curvatura

**Problemas conocidos:**

* Los materiales creados con una versión anterior no estarán disponibles en la nueva versión.
* El mapa de bits a material no gestiona el flujo de trabajo de Specular/Rugosidad
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento

### 0.2.0-beta Kiwi

*(Lanzado: 09 de noviembre de 2018)*

**Agregado:**

* La configuración del visor se guarda de una sesión a otra
* La configuración de material se guarda de una sesión a otra
* Carga rápida del panel Propiedades
* &amp;lbrack;Registro&amp;rbrack; Exportar archivo de registro a través del menú Ayuda
* &amp;lbrack;UI&amp;rbrack;Nuevo estilo de controles deslizantes
* &amp;lbrack;UI&amp;rbrack;Se han combinado los paneles Ajustes preestablecidos y Retoque
* &amp;lbrack;UI&amp;rbrack;Nuevo estilo de miniaturas
* Configuración de desplazamiento, Mosaico y Sombras accesible directamente en la ventana gráfica
* &amp;lbrack;Contenido&amp;rbrack; Nuevos materiales predeterminados
* &amp;lbrack;Contenido&amp;rbrack; Actualización de Moss Splatter
* &amp;lbrack;Framework&amp;rbrack; Actualizar Substance Engine Framework

**Corregido:**

* Se ha solucionado la eliminación de la pila de capas al cambiar de laboratorio
* Los valores de tiempo de carga mostrados en la ventana gráfica son correctos
* Los canales predeterminados del flujo de trabajo de material se inicializan correctamente
* Desactivar importación de malla personalizada
* Exportación de mapa de bits
* &amp;lbrack;MacOS&amp;rbrack; El Substance Alchemist de cierre puede necesitar un &quot;Forzar el cierre&quot;

**Problemas conocidos:**

* Los materiales creados con una versión anterior no estarán disponibles en la nueva versión.
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento

### 0.1.1-beta Jam

*(Lanzado: 24 de octubre de 2018)*

**Agregado:**

* BaseColor Delighter ya está disponible
* Acceder a la información del Substance Alchemist a través del menú Ayuda
* Recibir una notificación cuando haya una nueva versión de Substance Alchemist disponible
* La consola ya no está visible en Windows
* Nuevo estilo de miniaturas
* &amp;lbrack;MacOS&amp;rbrack; El Substance Alchemist se puede configurar en pantalla completa
* &amp;lbrack;Filtro&amp;rbrack; Importar máscara personalizada para administrar la fusión entre dos materiales
* &amp;lbrack;Filtro&amp;rbrack; Escala de control de musgo
* &amp;lbrack;Filtro&amp;rbrack; Actualización del parche de clonación

**Corregido:**

* Añadir una imagen en una entrada de imagen en la lista de parámetros actualiza las salidas
* Importar El filtro personalizado no agrega una Oclusión ambiental negra ni una opacidad negra

**Problemas conocidos:**

* Los materiales creados con una versión anterior no estarán disponibles en la nueva versión.
* &amp;lbrack;MacOS&amp;rbrack; El Substance Alchemist de cierre puede necesitar un &quot;Forzar el cierre&quot;
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* El cambio de visibilidad rápida de una etapa de Delighter afectará al rendimiento
* La exportación de materiales puede bloquearse

### 0.1.0-beta IceCream

*(Lanzado: 17 de octubre de 2018)*

**Agregado:**

* Fusión de materiales con 4 tipos de fusión (Fusión de Height, Fusión de muestra, Fusión de curvatura, Fusión de AO)
* Introducir el mecanismo de caché para optimizar los nuevos cálculos de la pila de capas
* Selección automática de un material en Inspire si se presenta en la ventana gráfica
* Formato normal centralizado en el panel Ajustes de material
* Controles de widgets de recorte y segmentación (-90xB0,+90xB0, hacer cuadrado,...) limpieza
* Nuevo filtro de Snow

**Corregido:**

* Limpieza de IU de panel
* Parpadeo de la ventana al cambiar el tamaño de ventanas y paneles
* La pila de capas no se vuelve a calcular al guardarla
* Los nombres de activos en la interfaz utilizan etiquetas en lugar de nombres de gráficos

**Problemas conocidos:**

* Estirar el abono cambiando rápidamente la visibilidad de la capa
* El enfoque restablece el ángulo de cámara
