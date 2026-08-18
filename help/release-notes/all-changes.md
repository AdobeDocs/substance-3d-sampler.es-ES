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

* &lbrack;Assets&rbrack; Comprobar la versión sbsar y avisar a los usuarios si el motor es demasiado antiguo para leerlo
* &lbrack;Captis&rbrack; Opción Añadir atrás para guardar los pies de ilustración de la fotometría en las preferencias

**Corregido:**

* &lbrack;2D View&rbrack; No mostrar con proporción física si el tamaño físico está desactivado
* &lbrack;Análisis&rbrack; Faltan eventos de análisis
* &lbrack;Análisis&rbrack; Evitar que crashpad informe de un bloqueo en el dispositivo vk perdido
* &lbrack;Aplicación&rbrack; No destruya los dispositivos vk al salir para evitar un bloqueo en el controlador nvidia
* &lbrack;Aplicación&rbrack; Corregir salida del Observador de colecciones vinculadas + Administrador de canales
* &lbrack;Aplicación&rbrack; Evitar un bloqueo al salir
* &lbrack;Contenido&rbrack; El filtro de &quot;acabado metálico&quot; no afecta al metal
* &lbrack;Contenido&rbrack; Añadir tamaño físico a los filtros dinámicos en los que falta
* &lbrack;Filters&rbrack; Quitar el relleno según el contenido de la lista de activos ocultos
* &lbrack;Capas&rbrack; Al hacer clic en Restablecer todos los ajustes, no se restablece el menú desplegable &quot;Se aplica a&quot;
* &lbrack;Capas&rbrack; Corrección de los ajustes mínimo y máximo para el widget de posición
* &lbrack;Capas&rbrack; Actualizar correctamente el filtro
* &lbrack;Tamaño físico&rbrack; Asegúrate de que la escala física funciona en todas partes + haz que el tamaño físico sea adecuado con filtros dinámicos
* &lbrack;Proyecto&rbrack; Asegúrese de que la resolución del recurso sea la predeterminada (2k x 2k) al crear un recurso nuevo
* &lbrack;Proyecto&rbrack; Volver a abrir el proyecto actual utilizado para abrir la versión anterior
* &lbrack;Proyecto&rbrack; Sampler ya no ofrece la restauración de una copia de seguridad de los proyectos dañados
* &lbrack;Procesando&rbrack; Procesamiento de miniaturas de material con una resolución máxima de 2k
* &lbrack;UI&rbrack; Código defensivo para evitar el bloqueo si el usuario es más rápido que la IU

### **6.0.1**

*(Lanzado: 21 de mayo de 2026)*

**Agregado:**

* &lbrack;Aplicación&rbrack; Advertir al usuario al abrir un proyecto con objetos 3D o luces de entorno
* &lbrack;Captis&rbrack; Haz que la interfaz de usuario se adapte a pantallas pequeñas
* &lbrack;Captis&rbrack; Actualizar IU de mayúsculas
* &lbrack;Configuración de canal&rbrack; Activar automáticamente SSS al utilizar el canal de SSS en ASM
* &lbrack;Motor&rbrack; Actualizar Substance Engine a la versión 9.4.3
* &lbrack;Preset&rbrack; Active &#39;Aplicar valores de miniatura preestablecidos&#39; de forma predeterminada
* &lbrack;Resources&rbrack; Mostrar &quot;todas las bibliotecas&quot; de forma predeterminada en lugar de &quot;activos de inicio&quot; en el panel de recursos
* &lbrack;Secuencias de comandos&rbrack; Adición de funciones de Python para gestionar la aplicación a una capa
* &lbrack;UI&rbrack; La lista de activos ahora es interactiva: el tamaño del activo se adapta al contenedor
* &lbrack;UI&rbrack; Mostrar vista 3D/2D de forma predeterminada
* &lbrack;UI&rbrack; Mostrar la optimización de materiales emergente al soltar un material del explorador
* &lbrack;UI&rbrack; Activar la inversión de botones de la barra del dispositivo

**Corregido:**

* &lbrack;Aplicación&rbrack; Solucionar problemas de espacio de color
* &lbrack;Aplicación&rbrack; Fijar actualizador de configuración
* &lbrack;Aplicación&rbrack; Activar los canales de digitalización cuando están configurados en automático
* &lbrack;Aplicación&rbrack; El botón Nuevo proyecto de la pantalla de inicio ya no borra el proyecto anterior con el mismo nombre
* &lbrack;Aplicación&rbrack; Evitar un bloqueo al salir de macOS
* &lbrack;Aplicación&rbrack; Impedir el acceso al recurso de referencias de recursos no válidas
* &lbrack;Aplicación&rbrack; Evitar el bloqueo al acceder a la superficie desde VersionedImage en un ajuste
* &lbrack;Aplicación&rbrack; Evitar el bloqueo al eliminar un escenario cuando no hay ninguno
* &lbrack;Captis&rbrack; Asegúrese de que Captis esté desconectado antes de cerrar Sampler
* &lbrack;Captis&rbrack; Evitar que se muestre dos veces la advertencia de USB-2
* &lbrack;Configuración de canal&rbrack; Corregir nombres de canal de OpenPBR
* &lbrack;Configuración de canal&rbrack; Actualización de etiquetas largas para canales de OpenPBR
* &lbrack;Contenido&rbrack; Actualizar todas las unidades de malla de metros a centímetros para los valores de SSS
* &lbrack;Exportar&rbrack; Asegúrese de que los valores predeterminados estén conectados a filtros dinámicos
* &lbrack;Exportar&rbrack; Las imágenes ahora se guardan en un subproceso de trabajo para mejorar el rendimiento
* &lbrack;Filters&rbrack; El Relleno según el contenido se bloquea al activar la escala
* &lbrack;Filters&rbrack; No se pudo abrir la ubicación de un filtro dinámico desde el panel de recursos
* &lbrack;Filters&rbrack; Corregir restablecimiento de todo en el paso de ajuste de segmentación automática
* &lbrack;Filters&rbrack; Restaurar y deshabilitar el procesamiento de uso en la creación de estructuras de árbol
* &lbrack;Filters&rbrack; Establecer el valor predeterminado correcto para el parámetro de aumento de escala
* &lbrack;Filters&rbrack; Actualizar generadores aunque estén en una capa de relleno
* &lbrack;Capas&rbrack; Prohibir cambiar el nombre de las capas de encabezado o marcador de posición de capa de entrada
* &lbrack;Capas&rbrack; Evitar el bloqueo durante la inserción de capas debido a un puntero que cuelga
* &lbrack;Capas&rbrack; Número incorrecto de imágenes en el nombre de la capa de acoplado
* &lbrack;Localización&rbrack; Asegúrese de que los nombres de los ajustes preestablecidos se actualicen al cambiar de idioma
* &lbrack;Localización&rbrack; Varios problemas de traducción en el panel de recursos
* &lbrack;Localización&rbrack; Acciones rápidas categorías problemas de localización
* &lbrack;Rendimiento&rbrack; Cargar ajustes solo en la sección abierta
* &lbrack;Preferencias&rbrack; Al borrar la ruta de caché de preferencias se restablece el valor anterior
* &lbrack;Procesando&rbrack; Pérdida de memoria al utilizar el rastreador de trazado
* &lbrack;Procesando&rbrack; Evita eliminar texturas mientras Vulkan todavía pueda acceder a ellas
* &lbrack;Procesando&rbrack; La rotación de textura no se convirtió de 0-1 a 0-360
* &lbrack;Secuencias de comandos&rbrack; Quitar clases no existentes de la documentación de Python
* &lbrack;Secuencias de comandos&rbrack; selectedAsset devuelve None si no hay ningún activo seleccionado
* &lbrack;Herramientas&rbrack; Al restablecer un valor de textura, ahora se deja de pintar y se borra la vista de parches
* &lbrack;UI&rbrack; No cierre las secciones del panel Propiedades siempre que se modifique algo
* &lbrack;UI&rbrack; Etiqueta de ajuste de color expuesta invisible al pasar el cursor
* &lbrack;UI&rbrack; Corregir el comportamiento interactivo de la lista de activos
* &lbrack;UI&rbrack; Corregir el bucle de enlace en la información sobre herramientas de AssetItem
* &lbrack;UI&rbrack; Corregir doble clic en el grupo de ajustes preestablecidos seleccionado
* &lbrack;UI&rbrack; Corregir área de colocación en el presentador de imágenes
* &lbrack;UI&rbrack; Corregir etiqueta con un botón para todos los idiomas
* &lbrack;UI&rbrack; Corregir height de línea para japonés en la ventana emergente de lista de canales
* &lbrack;UI&rbrack; Corregir el campo de la señal de longitud Aceptada
* &lbrack;UI&rbrack; Corregir ancho emergente con elemento de control izquierdo largo
* &lbrack;UI&rbrack; Corregir la ventana emergente de previsualización en elementos de activo
* &lbrack;UI&rbrack; Corrección de un selector rugoso/reflectante
* &lbrack;UI&rbrack; Corregir puntos suspensivos de cadena
* &lbrack;UI&rbrack; Solucionar problema de truncamiento de cadena
* &lbrack;UI&rbrack; Botón de restablecimiento del ajuste del interruptor de reparación
* &lbrack;UI&rbrack; Ocultar la lista desplegable de Modelos de material cuando se selecciona un ajuste preestablecido de exportación personalizado
* &lbrack;UI&rbrack; Eliminar resolución en la lista de canales de la ventana emergente de exportación
* &lbrack;UI&rbrack; El restablecimiento del diseño predeterminado mantiene la configuración del visor de proyección
* &lbrack;UI&rbrack; Restaurar los elementos de menú &quot;Editar en Photoshop&quot; y &quot;Editar en Illustrator&quot;

**Eliminado:**

* &lbrack;UI&rbrack; Quitar la sección &quot;Aplicado a&quot; de las capas de importación de imágenes
* &lbrack;UI&rbrack; Quitar la información sobre herramientas de acción rápida de apertura automática la primera vez que se inicia

## Versión 5

### **5.1.3 ÎLE FLOTTANTE**

*(Lanzado: 6 de enero de 2026)*

**Agregado:**

* &lbrack;Captis&rbrack; Mostrar una advertencia si el firewall ha desactivado el protocolo FTP

**Corregido:**

* &lbrack;Captis&rbrack; Abortar durante una captura puede producir errores
* &lbrack;Captis&rbrack; Al descargar los resultados al final de una captura, se utiliza mucha RAM
* &lbrack;Captis&rbrack; Ejecutar un enfoque automático inmediatamente después de una intensidad automática puede producir errores
* &lbrack;Captis&rbrack; Visualización de resultados HDR en el panel Resumen
* &lbrack;UI&rbrack; En algunos casos, el cuadro de diálogo de carpetas en MacOS no selecciona la carpeta correcta

### **5.1.2 ÎLE FLOTTANTE**

*(Lanzado: 20 de noviembre de 2025)*

**Agregado:**

* &lbrack;Aplicación&rbrack; Detectar la pérdida del dispositivo gráfico, avisar al usuario y salir correctamente
* &lbrack;Capas&rbrack; Se han mejorado los mensajes al acoplar capas
* &lbrack;Capas&rbrack; Miniaturas mejoradas para las capas de importación de imágenes y capas acopladas
* &lbrack;Incorporación&rbrack; Contenido de aprendizaje actualizado en la pantalla de inicio
* &lbrack;Proyecto&rbrack; Recuperar el último estado guardado de la sesión antes del bloqueo
* &lbrack;UI&rbrack; Actualización del icono de aplicación

**Corregido:**

* &lbrack;Aplicación&rbrack; Insertar un material en la pila de capas puede producir un bloqueo en macOS
* &lbrack;Aplicación&rbrack; Posible bloqueo con carga pesada en macOS
* &lbrack;Aplicación&rbrack; Posible bloqueo al añadir capas cuando la memoria de vídeo está llena
* &lbrack;Aplicación&rbrack; Posible bloqueo al abrir un proyecto
* &lbrack;Captis&rbrack; Error si el enfoque automático se ejecuta poco después de la calibración de intensidad automática
* &lbrack;Captis&rbrack; Problemas de fiabilidad y rendimiento tras la primera captura
* &lbrack;Captis&rbrack; Ralentizaciones y errores al copiar archivos al final de una captura
* &lbrack;Captis&rbrack; Pérdida de memoria pequeña al consultar información del dispositivo Captis
* &lbrack;Exportar&rbrack; Los parámetros expuestos de varios reguladores producen archivos .sbsar dañados
* &lbrack;Capas&rbrack; El patrón de mosaico automático se restablece a los valores predeterminados al cambiar los recursos
* &lbrack;Capas&rbrack; El color base personalizado predeterminado se muestra en rojo
* &lbrack;Capas&rbrack; Es posible el acoplado parcial de las capas secundarias del Tampón de clonar, lo que provoca problemas de procesamiento
* &lbrack;Capas&rbrack; Posible bloqueo al ajustar una pila de capas mientras el procesamiento está en curso
* &lbrack;Capas&rbrack; Error inesperado en el paso de región de interés de segmentación automática al cambiar los canales de origen
* &lbrack;Proyecto&rbrack; En ocasiones, al crear un material, se crea una miniatura incorrecta
* &lbrack;Acciones rápidas&rbrack; Algunas acciones rápidas tienen un recuento de entradas incorrecto
* &lbrack;UI&rbrack; El botón Grupo de acciones tiene anchos diferentes
* &lbrack;UI&rbrack; El botón Borrar de los campos de texto a veces activa la pérdida de enfoque
* &lbrack;UI&rbrack; Los cuadros combinados y los campos de texto son demasiado grandes
* &lbrack;UI&rbrack; Los iconos y las etiquetas no están alineados correctamente
* &lbrack;UI&rbrack; La etiqueta del campo de nombre está colocada incorrectamente
* &lbrack;UI&rbrack; Las etiquetas de botón Acciones rápidas están alineadas incorrectamente
* &lbrack;UI&rbrack; Los reguladores muestran también los ceros finales

**Eliminado:**

* &lbrack;Inteligencia artificial generativa&rbrack; Eliminación de funciones de IA generativa. *Esta característica se ha quitado de la aplicación y el servicio dejará de funcionar en versiones anteriores de Sampler el 5 de marzo.*

### **5.1.1 ÎLE FLOTTANTE**

*(Lanzado: 18 de septiembre de 2025)*

**Agregado:**

* &lbrack;2D View&rbrack; Ser capaz de alejar más la vista 2D para texturas de alta resolución
* &lbrack;Captis&rbrack; Advertencia a los usuarios sobre problemas al copiar archivos
* &lbrack;Capas&rbrack; Al duplicar una capa, use un número incremental en el nuevo nombre de capa

**Corregido:**

* &lbrack;2D View&rbrack; Al pintar trazos después de restablecer todas las propiedades del Tampón de clonar, los trazos creados anteriormente vuelven a aparecer
* &lbrack;Aplicación&rbrack; &quot;¿Desea guardar el proyecto actual?&quot; popup utiliza un nombre de proyecto incorrecto
* &lbrack;Aplicación&rbrack; Bloqueo al salir
* &lbrack;Aplicación&rbrack; Posible bloqueo
* &lbrack;Aplicación&rbrack; A veces, se genera una miniatura con un material incorrecto
* &lbrack;Captis&rbrack; En algunos dispositivos, al realizar una digitalización en alta resolución, el mapa de height aparece en negro
* &lbrack;Captis&rbrack; El botón &quot;Iniciar captura&quot; ya no se desactiva cuando no se ha definido ningún nombre de captura y cuando se está ejecutando una calibración
* &lbrack;Exportar&rbrack; Al exportar un archivo .sbsar, la exportación puede fallar sin notificar al usuario
* &lbrack;Filters&rbrack; La pantalla de parámetros avanzados para el filtro Mosaico automático a veces parpadea al ajustar los parámetros
* &lbrack;Filters&rbrack; Los parámetros predeterminados para el filtro Mosaico producen artefactos grises en la salida
* &lbrack;Filters&rbrack; A veces, con entradas de alta resolución, los ajustes avanzados del filtro Mosaico automático no muestran los puntos de patrón individuales
* &lbrack;Filters&rbrack; El tamaño del patrón del parámetro Mosaico automático de tamaño personalizado tiene un valor predeterminado incorrecto
* &lbrack;Capas&rbrack; Problema ocasional de color con el filtro Mosaico automático visible principalmente en materiales rojos
* &lbrack;Capas&rbrack; A veces, añadir capas restablece algunos ajustes a su valor predeterminado
* &lbrack;Tamaño físico&rbrack; La miniatura de los recursos con un tamaño físico tiene una escala de height incorrecta
* &lbrack;UI&rbrack; No se pueden renombrar los parámetros expuestos
* &lbrack;UI&rbrack; Los botones de activación de canal no son cuadrados
* &lbrack;UI&rbrack; Si la etiqueta del regulador es demasiado larga, no se puede acceder al botón Restablecer
* &lbrack;UI&rbrack; Pulsar la tecla de retorno o hacer clic en él no elimina el enfoque de los campos de texto
* &lbrack;UI&rbrack; A veces aparece información sobre herramientas no deseada en el panel Tamaño físico
* &lbrack;UI&rbrack; La vista 3D muestra una malla incorrecta al crear un proyecto vacío
* &lbrack;UI&rbrack; Al exponer una entrada del selector de color, su etiqueta desaparece al pasar el puntero
* &lbrack;UI&rbrack; Al exponer parámetros, el punto de color a veces se coloca incorrectamente

### **5.1.0 ÎLE FLOTTANTE**

*(Lanzado: 7 de agosto de 2025)*

**Agregado:**

* &lbrack;2D View&rbrack; El tamaño del pincel ahora se adapta a la resolución de textura actual
* &lbrack;Vista&amp;rbrack 3D; Alternar la escala de visualización nativa para el procesamiento 3D en las preferencias
* &lbrack;Aplicación&rbrack; Actualización del motor de procesamiento
* &lbrack;Captis&rbrack; Añadir la posibilidad de &quot;hacer cuadrado&quot; durante la previsualización
* &lbrack;Captis&rbrack; Detección automática de tamaños físicos
* &lbrack;Captis&rbrack; La captura de un nuevo material creará un nuevo activo
* &lbrack;Captis&rbrack; Cambiar la selección de resolución en el menú desplegable a píxeles por pulgada o centímetro en lugar de la resolución de píxeles del área máxima
* &lbrack;Captis&rbrack; Ayuda contextual sobre calibración de alineación
* &lbrack;Captis&rbrack; Generar mapa de rugosidad
* &lbrack;Captis&rbrack; Avisar al usuario si faltan los archivos de calibración predeterminados
* &lbrack;Filters&rbrack; Filtro de segmentación automática para escaneos y materiales estructurados
* &lbrack;Filters&rbrack; Nuevo filtro Eliminador de pliegues
* &lbrack;Filters&rbrack; Nuevas funciones del filtro Tampón de clonar
* &lbrack;Filters&rbrack; Nuevas funciones del filtro Ecualizar
* &lbrack;Capas&rbrack; Capacidad para acoplar capas
* &lbrack;Capas&rbrack; Menú contextual al hacer clic con el botón derecho en una capa para cambiar el nombre, duplicar, eliminar o acoplar la capa
* &lbrack;Incorporación&rbrack; Actualizar el contenido de la bienvenida y de las pantallas Novedades
* &lbrack;Rendimiento&rbrack; Mejor rendimiento al utilizar el filtro Recortar
* &lbrack;Rendimiento&rbrack; Mejorar el uso de memoria para la vista 3D
* &lbrack;Rendimiento&rbrack; La actualización de la vista 3D es más rápida
* &lbrack;Tamaño físico&rbrack; Habilitar &quot;visualización con proporción física&quot; al trabajar con filtros de Substance cuando el Tamaño físico está activado
* &lbrack;Tamaño físico&rbrack; Al importar imágenes en una pila vacía, proponga una resolución más coherente con la proporción de imágenes
* &lbrack;Acciones rápidas&rbrack; 3 nuevas acciones rápidas para el procesamiento de digitalizaciones
* &lbrack;Secuencias de comandos&rbrack; API para acoplar capas
* &lbrack;Secuencias de comandos&rbrack; Obtenga el nombre de archivo de cada imagen de una capa de importación de imágenes
* &lbrack;Secuencias de comandos&rbrack; Nueva función para activar/desactivar un canal determinado de un activo
* &lbrack;UI&rbrack; Rehacer los iconos y botones del panel Capas para adaptarlos a las nuevas funciones
* &lbrack;UI&rbrack; Advertencia sobre la degradación de la creación de luz ambiental

**Corregido:**

* &lbrack;2D View&rbrack; Es posible que la selección de &quot;Mostrar con proporción física&quot; no funcione al utilizar filtros de Substance
* &lbrack;captura 3D&rbrack; Los archivos SVG se muestran en el selector de archivos, pero no son compatibles
* &lbrack;Vista&amp;rbrack 3D; El parámetro de intensidad de emisión de la configuración del sombreado no funciona
* &lbrack;Vista&amp;rbrack 3D; A veces, la posición de la malla es incorrecta al crear un activo nuevo
* &lbrack;Vista&amp;rbrack 3D; El cambio al procesamiento de Path Tracing se bloquea en el hardware no compatible
* &lbrack;Aplicación&rbrack; La aplicación se bloquea al cerrar la ventana emergente de medida manual sin establecer un tamaño
* &lbrack;Aplicación&rbrack; Bloqueo
* &lbrack;Aplicación&rbrack; Bloqueo en Windows al mostrar el escritorio (tecla Windows + método abreviado de teclado D)
* &lbrack;Aplicación&rbrack; Posible bloqueo al cambiar de idioma
* &lbrack;Captis&rbrack; Bloqueo cuando los datos de la vista previa no son válidos
* &lbrack;Captis&rbrack; No es posible reducir completamente después de aumentar la imagen
* &lbrack;Captis&rbrack; Falta la localización en algunos pasos del asistente
* &lbrack;Captis&rbrack; Posible bloqueo al salir al utilizar Captis
* &lbrack;Captis&rbrack; El análisis no funciona si el dispositivo no tiene archivos de calibración
* &lbrack;Filters&rbrack; La vista previa del pincel al utilizar el filtro Tampón de clonar puede ser incorrecta según la textura y los tamaños de pincel
* &lbrack;Filters&rbrack; Tamaño de salida incorrecto después de utilizar el filtro de aumento de escala
* &lbrack;Filters&rbrack; Faltan iconos para los filtros de rotación de entorno y estilización
* &lbrack;Filters&rbrack; La actualización de algunos filtros puede provocar una representación incorrecta
* &lbrack;Capas&rbrack; Primer procesamiento incorrecto al mezclar dos materiales
* &lbrack;Capas&rbrack; El botón para actualizar capas muestra &quot;Actualizar todo&quot; incluso cuando solo hay una actualización
* &lbrack;Capas&rbrack; Cálculos innecesarios al importar imágenes en la pila de capas
* &lbrack;Rendimiento&rbrack; Mejorar la gestión de formatos de mapa de normales para reducir los tiempos de procesamiento
* &lbrack;Tamaño físico&rbrack; La ventana emergente de medición manual solo funciona después de realizar una medición automática
* &lbrack;Tamaño físico&rbrack; Resolución de exportación incorrecta en el elemento emergente Exportar cuando está activado el Tamaño físico
* &lbrack;Acciones rápidas&rbrack; Falta la localización en los nombres de recursos generados
* &lbrack;UI&rbrack; Es posible que la vista previa del activo al pasar el puntero no se muestre
* &lbrack;UI&rbrack; Al hacer clic en el botón Restablecer el valor predeterminado, se pueden romper algunos de los controles
* &lbrack;UI&rbrack; Los mensajes de error no se borran al cambiar de proyecto
* &lbrack;UI&rbrack; Asegúrese de que el nombre del material en el panel Ventana gráfica y propiedades esté vacío cuando no haya ningún recurso
* &lbrack;UI&rbrack; El botón Restablecer el valor predeterminado para el parámetro de punto de vista no funciona
* &lbrack;UI&rbrack; Superposición del botón Restablecer al valor predeterminado
* &lbrack;UI&rbrack; No se puede hacer clic en algunos botones cuando un panel está desacoplado
* &lbrack;UI&rbrack; Parámetro V de segmentación de texturas parcialmente oculto en Ajustes del visualizador y Vista 3D

**Eliminado:**

* &lbrack;captura 3D&rbrack; Quitar compatibilidad con captura 3D
* &lbrack;Aplicación&rbrack; Quitar la compatibilidad con macOS x86

### **5.0.3 AVELLANA**

*(Lanzado: 3 de junio de 2025)*

**Agregado:**

* &lbrack;Captis&rbrack; Permitir dar a un material el mismo nombre que a uno ya existente
* &lbrack;Captis&rbrack; Mover mensajes de error a ventanas emergentes en lugar de tostadas
* &lbrack;Filters&rbrack; Actualizar bordado
* &lbrack;Preferencias&rbrack; Añadir restablecimiento en la configuración del visualizador y en la configuración de sombreadores
* &lbrack;UI&rbrack; No presente el elemento de menú &quot;Mostrar ubicación&quot; en los recursos del proyecto

**Corregido:**

* &lbrack;captura 3D&rbrack; El filtro tras el proceso de malla no genera los mapas esperados
* &lbrack;Vista&amp;rbrack 3D; La vista 3D no funciona debido a la corrupción de la caché de sombreado
* &lbrack;Vista&amp;rbrack 3D; El plano de tierra y la cuadrícula son verticales cuando la escena es Z arriba
* &lbrack;Vista&amp;rbrack 3D; La malla a veces desaparece
* &lbrack;Aplicación&rbrack; Cerrar la ventana de inicio de sesión al iniciarse sin iniciar sesión a veces bloquea la aplicación
* &lbrack;Aplicación&rbrack; Bloqueo al denegar el acceso al archivo de configuración de complementos
* &lbrack;Aplicación&rbrack; El material actual no se selecciona al guardar el proyecto
* &lbrack;Aplicación&rbrack; Al restablecer el diseño predeterminado, la resolución se establece en 64x64
* &lbrack;Aplicación&rbrack; Sampler a veces se bloquea al procesar una pila de capas
* &lbrack;Exportar&rbrack; La resolución de exportación se restablece a veces a 64x64
* &lbrack;Exportar&rbrack; A veces no es posible exportar archivos .sbs/.sbsar
* &lbrack;Capas&rbrack; El botón Añadir material base no hace nada cuando el material está vacío
* &lbrack;Capas&rbrack; El mosaico de textura se cambia al duplicar un material
* &lbrack;Tamaño físico&rbrack; La medición automática no funciona si el panel Tamaño físico se ha acoplado antes de importar la imagen
* &lbrack;Secuencias de comandos&rbrack; El complemento de guardado automático está dañado
* &lbrack;UI&rbrack; Espaciado incorrecto en el cuadro de diálogo Exportar
* &lbrack;UI&rbrack; La animación del regulador de los ajustes ya no funciona
* &lbrack;UI&rbrack; Los reguladores no se ajustan a valores enteros cuando es necesario
* &lbrack;UI&rbrack; Se recortan algunos menús desplegables

### **5.0.2 AVELLANA**

*(Lanzado: 22 de abril de 2025)*

**Corregido:**

* &lbrack;Aplicación&rbrack; El botón Atrás de la página de inicio está roto
* &lbrack;Aplicación&rbrack; Sampler a veces no se inicia si hay datos dañados de versiones anteriores en el disco
* &lbrack;Aplicación&rbrack; La imagen importada no aparece en la ventana gráfica ni en la pila de capas
* &lbrack;Captis&rbrack; El campo de dirección IP Captis permanece vacío incluso después de reiniciar Sampler
* &lbrack;Captis&rbrack; La vista previa de cámara interactiva solo funciona cuando el idioma de la aplicación está establecido en inglés
* &lbrack;Exportar&rbrack; Bloqueo durante la exportación &lbrack;Layers&rbrack; A veces, la pintura no funciona en proyectos guardados anteriormente
* &lbrack;Capas&rbrack; Sampler a veces actualiza todas las texturas cuando solo se actualiza un canal
* &lbrack;Capas&rbrack; No es posible utilizar mezclas de materiales en la pila de capas después de actualizar a 5.0.x
* &lbrack;Capas&rbrack; La actualización de un proyecto con una versión anterior de Image to Material (AI) vuelve negro todo el material
* &lbrack;Capas&rbrack; Al intentar importar una imagen no compatible, Sampler crea una capa rota
* &lbrack;Secuencias de comandos&rbrack; Parte de la API de Python no funciona con un proyecto vacío
* &lbrack;UI&rbrack; Los elementos de menú a veces se desbordan en el menú Archivo

### **5.0.1 AVELLANA**

*(Lanzado: 20 de marzo de 2025)*

**Agregado**

* &lbrack;Aplicación&rbrack; Lista actualizada de compatibilidad de controladores gráficos
* &lbrack;Captis&rbrack; Mostrar una ventana emergente cuando las directivas del sistema operativo bloqueen el uso de HP Z Captis
* &lbrack;Acciones rápidas&rbrack; Explicar por qué una acción rápida está desactivada en una información sobre herramientas
* &lbrack;UI&rbrack; Estilo de IU de ventana de informe de bloqueos
* &lbrack;UI&rbrack; Al copiar en el portapapeles, mostrar un brindis para decir que se ha hecho

**Corregido:**

* &lbrack;2D View&rbrack; El regulador Exposición no tiene efecto cuando la proyección esférica está desactivada
* &lbrack;2D View&rbrack; Pintar fuera de la textura crea un trazo interrumpido
* &lbrack;2D View&rbrack; El botón de exposición no tiene información sobre herramientas.
* &lbrack;2D View&rbrack; El zoom en el lateral de una imagen no cuadrada no sigue al ratón
* &lbrack;captura 3D&rbrack; captura 3D no funciona en Windows 11 24H2
* &lbrack;captura 3D&rbrack; Bloqueo al salir de Sampler durante el paso de reconstrucción de la malla
* &lbrack;Vista&amp;rbrack 3D; El tiempo de cálculo a veces se muestra como 0 ms
* &lbrack;Vista&amp;rbrack 3D; Al cambiar la proyección de ortográfica a perspectiva, la ventana gráfica se vuelve gris
* &lbrack;Aplicación&rbrack; Bloqueo al iniciarse al comprobar las capacidades de la GPU
* &lbrack;Aplicación&rbrack; Bloqueo durante la instalación
* &lbrack;Aplicación&rbrack; Bloqueo al salir tras hacer clic con el botón derecho en un campo de metadatos
* &lbrack;Aplicación&rbrack; Falta la luz del entorno al abrir un SBSAR desde el explorador de archivos del sistema operativo
* &lbrack;Aplicación&rbrack; Al abrir un archivo .sbsar mientras se ejecuta Sampler, se cambia la configuración de Mosaico de texturas
* &lbrack;Captis&rbrack; Algunos metadatos pueden no transferirse entre los pasos de captura
* &lbrack;Captis&rbrack; El nombre del activo creado no es el introducido en el campo de metadatos
* &lbrack;Contenido&rbrack; En el proyecto de ejemplo se solicita una actualización del filtro, pero ya está actualizado
* &lbrack;Filters&rbrack; Filtro de ajuste normal/height sin icono
* &lbrack;Capas&rbrack; No se pueden cambiar imágenes en una capa de importación de imágenes
* &lbrack;Capas&rbrack; Se bloquea al utilizar el filtro de ampliación
* &lbrack;Capas&rbrack; La actualización de un proyecto con una imagen antigua a Material vuelve negro el material
* &lbrack;Procesando&rbrack; La modificación de una pila de capas inmediatamente después de crear un activo interrumpe el procesamiento
* &lbrack;Secuencias de comandos&rbrack; El plugin de guardado automático se bloquea cuando no hay ningún recurso en el proyecto
* &lbrack;Herramientas&rbrack; Falta el valor de tamaño de pincel en la barra de herramientas Pincel
* &lbrack;UI&rbrack; Al cambiar el idioma de la aplicación no se actualizan algunas de las etiquetas de la pantalla de inicio
* &lbrack;UI&rbrack; Pulsar Escape o Intro en los campos de texto del regulador no perderá el enfoque
* &lbrack;UI&rbrack; En el panel Propiedades, el botón Restablecer todo y la etiqueta de nombre de recurso se superponen
* &lbrack;UI&rbrack; Problemas al acoplar y desacoplar paneles
* &lbrack;UI&rbrack; El desplazamiento en un panel superpuesto también se desplazará en la ventana subyacente
* &lbrack;UI&rbrack; El cambio a la vista de lista en la sección Proyectos recientes de la pantalla de inicio no funciona
* &lbrack;UI&rbrack; El icono del botón del modo de visualización de la ventana siempre muestra 2D/3D

### **5.0.0 AVELLANA**

*(Lanzado: 20 de febrero de 2025)*

**Agregado**

* &lbrack;Incorporación&rbrack; Nueva página de inicio con acceso rápido a contenido de aprendizaje, proyectos de muestra, acciones rápidas y proyectos recientes.
* &lbrack;Incorporación&rbrack; Comenzar rápidamente con las nuevas acciones rápidas, accesibles desde la página de inicio y desde el panel dedicado
* &lbrack;Incorporación&rbrack; &lbrack;Contenido&rbrack; Las acciones rápidas son flujos de trabajo predefinidos que rellenan la pila de capas con la mayoría de las capas utilizadas
* &lbrack;Incorporación&rbrack; Posibilidad de crear un nuevo proyecto mediante un nuevo menú Inicio rápido, acciones rápidas o Proyecto personalizado
* &lbrack;Incorporación&rbrack; Posibilidad de crear un proyecto vacío directamente desde la página de inicio a través del botón dedicado
* &lbrack;Vista&amp;rbrack 3D; Nuevo rasterizador y trazador de trazadores avanzados que aportan nuevas capacidades de representación (propiedades como el revestimiento, el brillo, la translucidez, la dispersión subsuperficial) y coherencia visual en todo el ecosistema Substance
* &lbrack;Vista&amp;rbrack 3D; Ahora se puede acceder directamente a la configuración del visor en la vista 3D
* &lbrack;Vista&amp;rbrack 3D; Posibilidad de guardar una instantánea de procesamiento en el portapapeles o en archivos
* &lbrack;Vista&amp;rbrack 3D; Visualización de una cuadrícula para visualizar el origen de la escena
* &lbrack;Vista&amp;rbrack 3D; Activar el plano de tierra para capturar sombras y reflejos
* &lbrack;Vista&amp;rbrack 3D; Controla lo reflectante y opaco que es tu plano del suelo
* &lbrack;captura 3D&rbrack; Posición de la malla sobre el suelo
* &lbrack;Aplicación&rbrack; Comprobar la compatibilidad del hardware al iniciar la aplicación
* &lbrack;Aplicación&rbrack; Ahora se abre la ventana Informes de fallos justo después de que se produzca un bloqueo
* &lbrack;Contenido&rbrack; Abra un proyecto de muestra para comenzar fácilmente
* &lbrack;Exportar&rbrack; Exportación del sombreador de Adobe Standard Material en archivos USD
* &lbrack;Inteligencia artificial generativa&rbrack; Marque la etiqueta &quot;No inferir&quot; cuando utilice image como entrada en los flujos de trabajo de Imagen a textura
* &lbrack;Proyecto&rbrack; Las miniaturas se almacenan en el archivo de proyecto para abrir los proyectos más rápido
* &lbrack;Proyecto&rbrack; Configuración en las preferencias para almacenar datos de caché dentro del archivo de proyecto, con diferentes modos (sin caché, caché ligera, caché completa)
* &lbrack;Secuencias de comandos&rbrack; &lbrack;Interrumpir cambio&rbrack; Migración de Qt a Qt6.15: compatibilidad de efectos de los plugins existentes
* &lbrack;Secuencias de comandos&rbrack; Los complementos predeterminados y la carpeta de secuencias de comandos ahora se encuentran en la carpeta Documentos
* &lbrack;Secuencias de comandos&rbrack; Nueva interfaz de usuario para plugins por coherencia visual con los paneles principales de Sampler
* &lbrack;Secuencias de comandos&rbrack; Acceda a 2 ejemplos de plugins para descubrir las funciones de los plugins de Sampler
* &lbrack;Secuencias de comandos&rbrack; Nueva función open_3d_capture()
* &lbrack;Secuencias de comandos&rbrack; Al insertar una capa, controle si se inserta encima o debajo de la posición de destino

**Corregido:**

* &lbrack;captura 3D&rbrack; Bloqueo si no se puede iniciar la captura de objetos en macOS
* &lbrack;Aplicación&rbrack; Bloqueo al salir
* &lbrack;Aplicación&rbrack; Colgar al salir al añadir recursos al panel Proyecto
* &lbrack;Aplicación&rbrack; El cambio de nombre de un recurso de proyecto no funciona a menos que pulse Intro
* &lbrack;Aplicación&rbrack; Las entradas de menú Deshacer y Rehacer no se desactivan cuando deberían
* &lbrack;Assets&rbrack; No se pueden eliminar activos de la sección Todas las bibliotecas del panel Activos
* &lbrack;Contenido&rbrack; Atlas creator - Usar mapa de opacidad existente si existe
* &lbrack;Contenido&rbrack; Fusión de ID de color: corrija la selección de color en el color base
* &lbrack;Capas&rbrack; Evite cálculos inútiles al utilizar generadores
* &lbrack;Capas&rbrack; La modificación de un generador puede provocar la activación de demasiados equipos
* &lbrack;Rendimiento&rbrack; Mejorar la administración de memoria de GPU
* &lbrack;Rendimiento&rbrack; La caché de procesamiento no se puede usar al reiniciar la aplicación
* &lbrack;Resources&rbrack; Los archivos de solo lectura no están visibles en el panel Activos
* &lbrack;Secuencias de comandos&rbrack; Permitir reutilizar una capa después de añadir otra
* &lbrack;Secuencias de comandos&rbrack; El cambio de la estructura de la pila de capas varias veces en una secuencia de comandos puede fallar

**Eliminado:**

* &lbrack;Aplicación&rbrack; Quitar la compatibilidad con archivos de imagen .dng y .nef

## Versión 4

### **4.5.2 GRUYERE**

*(Lanzado: 7 de noviembre de 2024)*

**Corregido:**

* &lbrack;Contenido&rbrack; Filtros de mezclas de recortes, bordados y Heightes

### **4.5.1 GRUYERE**

*(Lanzado: 30 de julio de 2024)*

**Corregido:**

* &lbrack;Capas&rbrack; La pintura de máscaras de escala de grises no funciona, lo que afecta a herramientas como Tampón de clonar, Deformación de pintura y Relleno según el contenido

### **4.5.0 GRUYERE**

*(Lanzado: 18 de julio de 2024)*

**Agregado**

* &lbrack;Interoperabilidad&rbrack; Enviar materiales a UE5, Blender, Maya, 3DsMax Unity
* &lbrack;Contenido&rbrack; Nueva categoría del generador de texturas - Degradados
* &lbrack;Contenido&rbrack; Herramientas HDRI: nuevo filtro de rotación de entorno

**Corregido:**

* &lbrack;Parámetros expuestos&rbrack; La exposición de valores de entrada .sbsar no funciona
* &lbrack;Capas&rbrack; El color base se vuelve rojo con imágenes en escala de grises
* &lbrack;Procesando&rbrack; Las imágenes en escala de grises utilizadas en canales de color tienen un espacio de color incorrecto
* &lbrack;Secuencias de comandos&rbrack; El uso de un ajuste preestablecido de exportación a veces no exporta los canales esperados
* &lbrack;Contenido&rbrack; Dirt : La aplicación de un filtro de Dirt encima de la imagen al material genera una normal de negro
* &lbrack;Contenido&rbrack; Relieve: la escala de un motivo en el filtro de relieve no es lineal entre 0 y 1
* &lbrack;Contenido&rbrack; Hacer mosaico: Mejora la coherencia normal y de height

### **4.4.1 FONDUE**

*(Lanzado: 6 de junio de 2024)*

**Corregido:**

* &lbrack;Contenido&rbrack; Falta el filtro de dirt
* &lbrack;Inteligencia artificial generativa&rbrack; En ocasiones, se producen errores de red al utilizar Imagen para texturizar

### **FUENTE 4.4.0**

*(Lanzado: 23 de mayo de 2024)*

**Agregado:**

* &lbrack;Aplicación&rbrack; La caché de captura 3D ahora se almacena en una subcarpeta independiente
* &lbrack;Inteligencia artificial generativa&rbrack; Imagen a textura (beta)
* &lbrack;Inteligencia artificial generativa&rbrack; Texto a motivo (beta)
* &lbrack;Inteligencia artificial generativa&rbrack; Texto a textura (beta)
* &lbrack;Secuencias de comandos&rbrack; Los activos ahora tienen una propiedad de recurso
* &lbrack;Secuencias de comandos&rbrack; Las capas ahora tienen la propiedad &#39;output_usages&#39;

**Corregido:**

* &lbrack;Aplicación&rbrack; Bloqueo al abrir un archivo de proyecto dañado
* &lbrack;Aplicación&rbrack; Bloqueo cuando el proyecto contiene recursos dañados
* &lbrack;Aplicación&rbrack; Bloqueo al desconectar un monitor en Windows
* &lbrack;Aplicación&rbrack; Icono de aplicación incorrecto en la barra de tareas de Windows
* &lbrack;Aplicación&rbrack; La corrupción del archivo de configuración principal puede provocar la eliminación de archivos
* &lbrack;Aplicación&rbrack; Los paneles aparecen delante de las ventanas emergentes
* &lbrack;Contenido&rbrack; Los generadores de texturas tienen miniaturas borrosas
* &lbrack;Exportar&rbrack; El canal de opacidad generado a partir de una imagen importada se rompe al exportar un archivo .sbs/.sbsar
* &lbrack;Filters&rbrack; La ampliación puede bloquearse en función de las capas de entrada
* &lbrack;Inteligencia artificial generativa&rbrack; Posibles bloqueos al recibir resultados inesperados del servicio
* &lbrack;Secuencias de comandos&rbrack; Bloqueo al cargar automáticamente un complemento desde la variable de entorno
* &lbrack;Secuencias de comandos&rbrack; Posible bloqueo al asignar el uso de salida con la API

### **4.3.3 EMPANADA**

*(Lanzado: 26 de marzo de 2024)*

**Agregado:**

* &lbrack;captura 3D&rbrack; Nuevos parámetros avanzados de UV automático durante el proceso de postproducción
* &lbrack;Filters&rbrack; Filtro de perforación: posibilidad de invertir y cambiar el tamaño del motivo personalizado

**Corregido:**

* &lbrack;captura 3D&rbrack; El color base puede ser incorrecto en macOS
* &lbrack;captura 3D&rbrack; Bloqueo al procesar una nueva versión
* &lbrack;captura 3D&rbrack; El paso posterior al proceso puede bloquearse en macOS
* &lbrack;captura 3D&rbrack; La capa Transformación de malla puede provocar un procesamiento incorrecto
* &lbrack;Aplicación&rbrack; Bloqueo al iniciar Sampler mientras una instancia anterior aún se está exportando
* &lbrack;Aplicación&rbrack; Sampler no responde durante un momento cuando se inicia por primera vez
* &lbrack;Exportar&rbrack; El mapa de ángulo de anisotropía no se exporta
* &lbrack;Filters&rbrack; Añadir tejido de tela a la pila de capas puede producir un bloqueo
* &lbrack;Filters&rbrack; Añadir Relieve a la pila de capas puede producir un bloqueo
* &lbrack;Filters&rbrack; El Relleno según el contenido se bloquea al utilizar imágenes de 32 bits
* &lbrack;Filters&rbrack; Relieve: La opacidad de las capas inferiores no se sobrescribe por completo
* &lbrack;Filters&rbrack; Relleno: El modo de fusión no funciona en Designer y Painter
* &lbrack;Filters&rbrack; Bordado: la selección automática de color está rota
* &lbrack;Preferencias&rbrack; Impedir la configuración de una ruta no compatible para la caché de captura 3D
* &lbrack;Preferencias&rbrack; La preferencia Formato normal no funciona
* &lbrack;Secuencias de comandos&rbrack; Los parámetros de los canales de Asset.export_material distinguen entre mayúsculas y minúsculas

### **4.3.2 EMPANADA**

*(Lanzado: 22 de febrero de 2024)*

**Corregido:**

* &lbrack;Aplicación&rbrack; Guardar un proyecto en un recurso compartido de red en Windows daña el archivo del proyecto

### **4.3.1 EMPANADA**

*(Lanzado: 15 de febrero de 2024)*

**Corregido:**

* &lbrack;captura 3D&rbrack; Bloqueo cuando no se puede acceder a los archivos de imagen al generar máscaras por lotes
* &lbrack;Exportar&rbrack; La exportación de un material con Recortar o relativo a la capa de directiva de entrada produce resultados no válidos
* &lbrack;Capas&rbrack; Bloqueo raro al procesar una pila de capas
* &lbrack;Filters&rbrack; Bordado: Se ha solucionado el problema al utilizar la entrada de material en MacOS.
* &lbrack;Filters&rbrack; Estilización - Soporte de los generadores de texturas
* &lbrack;Filters&rbrack; Patrón: corregir nombres de parámetros
* &lbrack;Localización&rbrack; &quot;Guardar como...&quot; en la ventana información de hardware, en el menú ayuda, aparece sin localizar

### **4.3.0 EMPANADA**

*(Lanzado: 25 de enero de 2024)*

**Agregado**

* &lbrack;Assets&rbrack; Nuevo tipo de activo: Generadores de texturas
* &lbrack;Assets&rbrack; Nuevos materiales incluidos en los Activos iniciales
* &lbrack;Assets&rbrack; Nuevo selector de recursos para parámetros de imagen en el panel Propiedades
* &lbrack;Assets&rbrack; Arrastre y suelte los Generadores de texturas del panel Activos en los selectores de imagen del panel Propiedades
* &lbrack;Assets&rbrack; Arrastre y suelte los generadores de texturas desde el explorador de archivos del sistema operativo
* &lbrack;Assets&rbrack; Los filtros pueden sugerir el montaje de generadores mediante una etiqueta de usuario en la entrada de la imagen
* &lbrack;Assets&rbrack; Los generadores de texturas pueden definir qué filtro debe sugerirlas mediante una etiqueta de usuario
* &lbrack;Contenido&rbrack; Nuevo filtro Recorte con perspectiva
* &lbrack;Contenido&rbrack; Nuevo filtro de estilización
* &lbrack;Contenido&rbrack; Modo de fusión en Filtro de relleno
* &lbrack;Contenido&rbrack; Filtro de bordado actualizado
* &lbrack;Contenido&rbrack; Filtro de Ajuste de pintura actualizado
* &lbrack;Contenido&rbrack; Se han actualizado todos los filtros para admitir los generadores de texturas
* &lbrack;Capas&rbrack; Posibilidad de elegir un canal de salida del generador de texturas al añadirlo a la pila de capas
* &lbrack;Capas&rbrack; Posibilidad de enumerar y aplicar fácilmente ajustes preestablecidos en los generadores de texturas
* &lbrack;Capas&rbrack; Visualización de una vista previa del generador de texturas en los selectores de imágenes
* &lbrack;Capas&rbrack; Los parámetros del generador de texturas se pueden exponer y exportar
* &lbrack;Capas&rbrack; Asignar el uso de color base al importar una sola imagen con la plantilla de creación de importación de textura
* &lbrack;Capas&rbrack; Comentarios al intentar arrastrar y soltar archivos incompatibles en los selectores de imágenes del panel Propiedades
* &lbrack;Capas&rbrack; Generar un canal de opacidad a partir del canal alfa de una imagen importada
* &lbrack;Capas&rbrack; La conversión de imagen a material (IA) es más rápida de calcular al cambiar su categoría
* &lbrack;Capas&rbrack; Seleccione la capa más relevante después de utilizar una plantilla de creación
* &lbrack;Capas&rbrack; Los widgets de posición ahora se pueden retocar con un regulador en el grupo Parámetros avanzados
* &lbrack;Exportar&rbrack; Mostrar un porcentaje en la cola en lugar de números RAW
* &lbrack;Interoperabilidad&rbrack; El canal de opacidad ahora se reconoce como canal alfa al enviar a Painter
* &lbrack;Aplicación&rbrack; Nuevo cuadro de diálogo para mostrar y guardar información de hardware
* &lbrack;Aplicación&rbrack; Nueva preferencia para cambiar la escala de height predeterminada de cada proyecto
* &lbrack;Aplicación&rbrack; Mejorar la forma en que se muestran los activos obsoletos
* &lbrack;Secuencias de comandos&rbrack; Nuevas funciones asset.documentResolution() y asset.setDocumentResolution()
* &lbrack;Secuencias de comandos&rbrack; Nueva función select_asset()
* &lbrack;Secuencias de comandos&rbrack; API de Python para generadores de texturas
* &lbrack;Secuencias de comandos&rbrack; get_project_assets() ahora devuelve objetos 3D
* &lbrack;UI&rbrack; El tamaño de la miniatura del activo se puede cambiar en el panel Activos
* &lbrack;UI&rbrack; Iconos de visualización de ventanilla actualizados

**Corregido:**

* &lbrack;2D View&rbrack; El zoom con la rueda del ratón está bloqueado en un 244 %
* &lbrack;Aplicación&rbrack; Bloqueo al inicio al inicializar la API de gráficos
* &lbrack;Aplicación&rbrack; Bloqueo si el nombre del proyecto contiene el carácter #
* &lbrack;Aplicación&rbrack; Posible bloqueo al abrir un proyecto antiguo
* &lbrack;Aplicación&rbrack; Volver a abrir el proyecto actual puede producir un bloqueo
* &lbrack;Aplicación&rbrack; Algunos cambios de proyecto no se registran y se pierden sin avisar al cerrar el proyecto si no se guardan
* &lbrack;Exportar&rbrack; .sbs/.sbsar problemas de exportación al utilizar varios archivos con el mismo nombre
* &lbrack;Exportar&rbrack; Espacio de color incorrecto para el archivo .sbs/.sbsar de imágenes en escala de grises exportado
* &lbrack;Filters&rbrack; Problemas de comportamiento de fusión de opacidad
* &lbrack;Capas&rbrack; En ocasiones, los archivos .svg no se procesan con la resolución correcta
* &lbrack;Rendimiento&rbrack; No es necesario guardar algunos proyectos en disco
* &lbrack;Proyecto&rbrack; La importación de un proyecto antiguo no carga los ajustes preestablecidos asociados
* &lbrack;Secuencias de comandos&rbrack; No se pueden obtener los parámetros de la primera capa insertada
* &lbrack;UI&rbrack; La ventana emergente de vista previa al pasar el cursor sobre un activo puede aparecer en una ubicación o pantalla equivocadas
* &lbrack;UI&rbrack; Los paneles no acoplados son visibles y se pueden utilizar en la parte superior de la pantalla de bienvenida

### **4.2.2 DORAYAKI**

*(Lanzado: 5 de diciembre de 2023)*

**Agregado:**

* &lbrack;captura 3D&rbrack; Ahora captura 3D es entre un 5 % y un 10 % más rápido en Windows
* &lbrack;captura 3D&rbrack; Mejorar la limpieza de la malla antes de la diezmación
* &lbrack;Motor&rbrack; Actualizar Substance Engine a la versión 9.0.3
* &lbrack;Capas&rbrack; Relleno según el contenido: actualización ascendente, varias correcciones de casos de uso y compatibilidad con Linux

**Corregido:**

* &lbrack;captura 3D&rbrack; Al hacer clic en &quot;Atrás&quot; después de la alineación, &quot;Siguiente&quot; no se actualiza la nube de puntos
* &lbrack;captura 3D&rbrack; Malla mostrada con taladros después de agregarla al proyecto
* &lbrack;Aplicación&rbrack; Bloqueo al salir del modo de pantalla completa después de un Captura 3D
* &lbrack;Aplicación&rbrack; Bloqueo con archivos de imagen creados
* &lbrack;Aplicación&rbrack; Si en &quot;Todas las bibliotecas&quot; al salir de Sampler, el panel Activos se vacía al reiniciar
* &lbrack;Aplicación&rbrack; Pérdida de memoria al exportar material
* &lbrack;Aplicación&rbrack; Abrir un proyecto guardado con versiones anteriores de Sampler puede producir un bloqueo
* &lbrack;Aplicación&rbrack; Posibles bloqueos al no convertir mallas 3D
* &lbrack;Aplicación&rbrack; Bloqueo silencioso al abrir un archivo .sbsar mientras se ejecuta Sampler
* &lbrack;Exportar&rbrack; Bloqueo al exportar un archivo .sbs/.sbsar con un uso personalizado
* &lbrack;Exportar&rbrack; Los mapas normales exportados siempre son DirectX, independientemente de la configuración del usuario
* &lbrack;Exportar&rbrack; La exportación de un objeto 3D a un archivo FBX en macos no funciona
* &lbrack;Exportar&rbrack; Incoherencias al exportar una pila de capas con un filtro de bordado como archivo .sbs/.sbsar
* &lbrack;Exportar&rbrack; En ocasiones, la exportación de archivos .sbs/.sbsar no funciona
* &lbrack;Exportar&rbrack; A veces, al exportar un archivo .sbs/.sbsar, las imágenes no tienen la profundidad de bits correcta
* &lbrack;Capas&rbrack;  Al hacer invisible una capa de salpicaduras, se procesa su primer secundario
* &lbrack;Capas&rbrack; Bloqueo al cargar la máscara en la capa Brillo/Contraste
* &lbrack;Capas&rbrack; Se muestran mensajes de error engañosos después de eliminar la capa
* &lbrack;Capas&rbrack; Posible bloqueo al degradar un activo
* &lbrack;Capas&rbrack; Algunas salidas no están conectadas a las entradas a menos que el uso sea forzado en el panel Configuración de canal
* &lbrack;Tamaño físico&rbrack; El menú desplegable de capas de referencia se puede restablecer por error
* &lbrack;UI&rbrack; Es necesario actualizar los iconos de importación de información de plantilla
* &lbrack;UI&rbrack; La sugerencia de método abreviado de ventana aparece cada vez que cambia el diseño de la ventana gráfica

### **4.2.1 DORAYAKI**

*(Lanzado: 21 de septiembre de 2023)*

**Agregado :**

* &lbrack;Contenido&rbrack; Imagen a material - Mejorar la generación de microdetalles en mapas normales
* &lbrack;Contenido&rbrack; Imagen a material - Nuevo parámetro de intensidad de iluminación
* &lbrack;Capas&rbrack; Se pueden añadir imágenes en las capas de importación de imágenes
* &lbrack;Capas&rbrack; Las imágenes se pueden eliminar en las capas de importación de imágenes
* &lbrack;Capas&rbrack; Ahora se pueden eliminar capas no válidas
* &lbrack;2D View&rbrack; Mayús + C para retroceder por los canales
* &lbrack;captura 3D&rbrack; Mostrar un aviso cuando el usuario importe menos de 20 imágenes
* &lbrack;Aplicación&rbrack; Nuevas preferencias para definir el valor de mosaico de textura de material por defecto
* &lbrack;Incorporación&rbrack; Interfaz de usuario del tutorial actualizada para Imagen a material (IA) y Ampliación de escala
* &lbrack;Secuencias de comandos&rbrack; API de captura 3D: DatasetInfo tiene más datos cuando Capture3dState está establecido en align
* &lbrack;Secuencias de comandos&rbrack; Nuevo argumento select_asset para create_asset(). Nuevas funciones: wait_for_computation() y clear_render_cache()

**Solucionado :**

* &lbrack;Capas&rbrack; Bloqueo cuando la región de recorte es muy pequeña
* &lbrack;Capas&rbrack; Bloqueo al añadir o ajustar el filtro Recortar
* &lbrack;Capas&rbrack; La cuadratura de la región de recorte genera una resolución de salida de material incorrecta
* &lbrack;Capas&rbrack; Las salidas a veces desaparecen cuando varias capas están desactivadas
* &lbrack;Capas&rbrack; Es posible que la caché de procesamiento no se invalide correctamente con los filtros de Imagen a material (AI) y Mejora de escala
* &lbrack;Capas&rbrack; No se puede añadir un filtro de ampliación al seleccionar &quot;No volver a mostrar este mensaje&quot; en la ventana emergente de advertencia
* &lbrack;Capas&rbrack; No se puede restaurar la imagen en el filtro Bordado una vez modificado
* &lbrack;Exportar&rbrack; La resolución de mapa normal exportada cambia al cambiar el formato normal
* &lbrack;Exportar&rbrack; Quitar el sufijo de nombre de archivo &quot;\_environment&quot; al exportar un entorno
* &lbrack;Exportar&rbrack; No se puede exportar un archivo .sbsar cuando hay una capa de transformación de deformación en la pila de capas
* &lbrack;2D View&rbrack; &quot;Ajustar a la pantalla&quot; no funciona cuando cambia la resolución
* &lbrack;Aplicación&rbrack; Después de cerrar la ventana de la aplicación mientras se realiza el cálculo, el proceso de la aplicación podría seguir ejecutándose
* &lbrack;Aplicación&rbrack; Bloqueo al salir
* &lbrack;Aplicación&rbrack; Invalidar la caché de procesamiento al alternar redes neuronales aceleradas por GPU
* &lbrack;Secuencias de comandos&rbrack; Asignar un nombre a un complemento como nombre de panel existente provoca comportamientos inesperados
* &lbrack;UI&rbrack; Al hacer clic en un elemento con información sobre herramientas, esta desaparecerá hasta que se reinicie
* &lbrack;UI&rbrack; El valor de escala de heightes puede cambiar al cambiar de recursos
* &lbrack;UI&rbrack; Margen incorrecto en las combinaciones

### **4.2 DORAYAKI**

*(Lanzado: 5 de septiembre de 2023)*

**Agregado:**

* &lbrack;Contenido&rbrack; Se han mejorado enormemente los filtros de imagen a material (IA) y Delighter
* &lbrack;Contenido&rbrack; Nuevo filtro de ampliación
* &lbrack;Contenido&rbrack; El filtro Recortar ahora tiene una resolución de salida dinámica.
* &lbrack;Plantilla de creación de material&rbrack; Agregar configuración de tamaño de documento.
* &lbrack;Plantilla de creación de material&rbrack; Nuevo botón de alternancia &quot;Añadir un recorte&quot;.
* &lbrack;Plantilla de creación de material&rbrack; Nuevo botón deslizante &quot;Mejorar material&quot;
* &lbrack;Plantilla de creación de material&rbrack; Mostrar tamaño de imagen importado
* &lbrack;Plantilla de creación de material&rbrack; Proporcionar comentarios cuando no se puedan utilizar algunas imágenes importadas
* &lbrack;Plantilla de creación de material&rbrack; Avisar cuando los tamaños de imagen no sean coherentes
* &lbrack;Plantilla de creación de material&rbrack; Nuevas advertencias e información sobre herramientas
* &lbrack;Capas&rbrack; Mostrar la resolución de las capas de la pila de capas
* &lbrack;Capas&rbrack; La resolución de cálculo de capa ahora se puede establecer en Tamaño de documento o Tamaño de entrada
* &lbrack;Capas&rbrack; Mostrar la resolución de las capas en la pila de capas
* &lbrack;Capas&rbrack; Cambiar una directiva de resolución de capa a Documento o Entrada de capa cuando corresponda
* &lbrack;Capas&rbrack; Avisar al usuario cuando se añada manualmente un filtro de ampliación y proporcionar documentación
* &lbrack;Capas&rbrack; Advertencia al usuario al realizar una ampliación lineal y oferta utilizar el filtro Ampliación en su lugar
* &lbrack;Capas&rbrack; El cálculo de una capa de imagen a material (AI) ahora se puede cancelar más rápido, para mejorar los tiempos de procesamiento al ajustar la pila de capas
* &lbrack;Capas&rbrack; El cálculo de una capa de ampliación ahora se puede cancelar más rápido, para mejorar los tiempos de procesamiento al ajustar la pila de capas
* &lbrack;Exportar&rbrack; Permitir resolución de sustitución de texturas exportadas
* &lbrack;Exportar&rbrack; La lista Canales para exportar ahora está ordenada
* &lbrack;Exportar&rbrack; Mostrar la resolución del canal en la lista de canales que exportar
* &lbrack;Aplicación&rbrack; Nueva preferencia para activar o desactivar las redes neuronales aceleradas por GPU
* &lbrack;UI&rbrack; Lista desplegable de resolución mejorada
* &lbrack;UI&rbrack; Nuevos iconos para los filtros Transformación de malla, Posprocesamiento de malla y Tejido
* &lbrack;UI&rbrack; Cambiar el nombre del panel &quot;Compartir&quot; a &quot;Exportar&quot;
* &lbrack;Secuencias de comandos&rbrack; Añadir compatibilidad con la resolución de salida de capa a la API de exportación
* &lbrack;Secuencias de comandos&rbrack; Se ha añadido Recortar, Aumentar y Tamaño de documento a la API de importación de imágenes
* &lbrack;Incorporación&rbrack; Nuevos tutoriales
* &lbrack;Incorporación&rbrack; Actualizar el contenido de la bienvenida y de las pantallas Novedades
* &lbrack;Motor&rbrack; Actualizar Substance Engine a la versión 9.0.1

**Corregido:**

* &lbrack;captura 3D&rbrack; Mejorar opciones de Precisión Nombrar en Parámetros de ajustes de Alineación
* &lbrack;Aplicación&rbrack; La importación de imágenes con no múltiplo de 16 dimensiones puede producir un bloqueo
* &lbrack;Aplicación&rbrack; Bloqueo al duplicar un recurso en el panel Proyecto
* &lbrack;Aplicación&rbrack; Bloqueo al cambiar de recursos en el panel Proyecto
* &lbrack;Contenido&rbrack; Pintar una máscara personalizada para el Snow no funciona correctamente
* &lbrack;Parámetros expuestos&rbrack; Los cambios de parámetros expuestos se pueden perder al cambiar de material
* &lbrack;Interoperabilidad&rbrack; Enviar un material desde el panel Exportar puede producir un bloqueo
* &lbrack;Capas&rbrack; El Relleno según el contenido detiene la informática al cambiar de una entrada de imagen única a una entrada de material
* &lbrack;Capas&rbrack; Bloqueo después de duplicar una luz de entorno que contiene un material
* &lbrack;Capas&rbrack; La capa de importación de imágenes muestra un nombre de imagen incorrecto en el panel Propiedades si se ha cambiado el nombre del archivo de imagen
* &lbrack;Capas&rbrack; En ocasiones, se muestra un control de número en una capa inactiva
* &lbrack;Capas&rbrack; En ocasiones, cambiar el uso de salida de una imagen en una capa de importación de imágenes no funciona
* &lbrack;Capas&rbrack; Tipos de caracteres en la ventana Plantilla de Creación
* &lbrack;UI&rbrack; La información sobre herramientas de incorporación de la ventana gráfica 3D tiene problemas de enfoque
* &lbrack;UI&rbrack; El nombre de imagen puede desbordarse si el nombre de archivo es demasiado largo
* &lbrack;UI&rbrack; Problemas menores de diseño de la barra de herramientas del pincel al utilizar el borrador
* &lbrack;UI&rbrack; Las cadenas se truncan en algunos idiomas en el panel Ajustes del visor
* &lbrack;UI&rbrack; Mientras se muestra la ventana emergente de información sobre herramientas de la ventana gráfica, al pulsar &quot;espacio&quot; se crea un nuevo proyecto

### **4.1.2 CANNOLI**

*(Lanzado: 20 de junio de 2023)*

**Corregido:**

* &lbrack;Capas&rbrack; Pérdida de memoria al ajustar los materiales y filtros del Substance que provocan bloqueos

### **4.1.1 CANNOLI**

*(Lanzado: 06 de junio de 2023)*

**Agregado**

* &lbrack;Motor&rbrack; Actualizar Substance Engine a la versión 9.0
* &lbrack;Interoperabilidad&rbrack; Enviar objetos 3D a Stager y Painter

**Corregido:**

* &lbrack;captura 3D&rbrack; Las aplicaciones se bloquean cuando falla el procesador de captura 3D
* &lbrack;captura 3D&rbrack; Bloqueo cuando no se puede cargar una imagen
* &lbrack;captura 3D&rbrack; Bloqueo al alcanzar el paso de reconstrucción de malla
* &lbrack;captura 3D&rbrack; Bloqueo al cambiar el tamaño del cuadro delimitador
* &lbrack;captura 3D&rbrack; Importar máscaras siguiendo la convención no asigna la máscara correctamente
* &lbrack;captura 3D&rbrack; El procesamiento falla al ajustar el cuadro delimitador
* &lbrack;captura 3D&rbrack; El cambio entre las opciones de procesamiento de la versión y de alternancia durante el posproceso de Captura 3D es lento
* &lbrack;captura 3D&rbrack; El cambio entre versiones durante el paso captura 3D posterior al proceso a veces se interrumpe
* &lbrack;Aplicación&rbrack; Bloqueo al inicio
* &lbrack;Aplicación&rbrack; Bloqueo al duplicar un material cuyo nombre se ha cambiado
* &lbrack;Aplicación&rbrack; Bloqueo al abrir un proyecto .alch heredado sin su carpeta de dependencias
* &lbrack;Aplicación&rbrack; Bloqueo al conectar o desconectar una pantalla, el equipo pasa a la suspensión o se accede de forma remota
* &lbrack;Aplicación&rbrack; Bloqueos y pérdidas de memoria relacionados con la administración de activos no persistentes
* &lbrack;Exportar&rbrack; La selección del formato de material para los tipos de archivo de objeto 3D que incrustan o hacen referencia a texturas debe estar desactivada
* &lbrack;Exportar&rbrack; Bloqueo si se produce un error durante la exportación de objetos 3D
* &lbrack;Exportar&rbrack; Bloqueo al exportar un archivo .sbs/.sbsar
* &lbrack;Exportar&rbrack; Se produce un bloqueo al importar un ajuste preestablecido personalizado que tiene la misma etiqueta pero no el mismo nombre de archivo
* &lbrack;Exportar&rbrack; La exportación de una luz ambiental a un archivo .sbs/.sbsar a veces no funciona
* &lbrack;Exportar&rbrack; La exportación de Gltf/Glb codifica texturas en base64
* &lbrack;Exportar&rbrack; El campo de texto de nombre no funciona al reenfocar
* &lbrack;Exportar&rbrack; Conservar el mosaico no funciona al exportar una capa de imagen a material (con IA) a un archivo .sbs/.sbsar
* &lbrack;Exportar&rbrack; Al exportar gltf y reemplazar archivos, la lista de archivos que se van a reemplazar no es correcta
* &lbrack;Parámetros expuestos&rbrack; La velocidad aleatoria no funciona en archivos .sbs/.sbsar exportados
* &lbrack;Capas&rbrack; El Relleno según el contenido a veces se bloquea cuando se añade por segunda vez
* &lbrack;Capas&rbrack; Bloqueo al calcular una pila de capas
* &lbrack;Capas&rbrack; La caché de disco de imagen a material (AI) no funciona
* &lbrack;Capas&rbrack; Posible bloqueo al ajustar una capa
* &lbrack;Rendimiento&rbrack; Pérdidas de memoria
* &lbrack;Proyecto&rbrack; Bloqueo al guardar un proyecto
* &lbrack;Proyecto&rbrack; Importar el mismo proyecto dos veces seguidas duplica activos
* &lbrack;UI&rbrack; Los botones redondeados con solo un icono no se representan correctamente

### 4.1.0 Cannoli

*(Lanzado: 28 de marzo de 2023)*

**Agregado:**

* &lbrack;Contenido&rbrack; Nuevo filtro de bordado
* &lbrack;Contenido&rbrack; Nuevo filtro Deformación de pintura
* &lbrack;UI&rbrack; Opción Añadir exportación en el menú Archivo
* &lbrack;captura 3D&rbrack; El botón Atrás ahora está disponible en el paso de alineación
* &lbrack;captura 3D&rbrack; Imágenes Manejar JPEG Orientación EXIF
* &lbrack;captura 3D&rbrack; Scripting: nueva propiedad dataset_info.camera
* &lbrack;captura 3D&rbrack; Añadir compatibilidad con Linux (consulte la documentación)
* &lbrack;captura 3D&rbrack; Comprobar el acceso de lectura de las imágenes importadas
* &lbrack;Incorporación&rbrack; Formación - 2 nuevos tutoriales (Bordado y Deformación de pintura)
* &lbrack;Incorporación&rbrack; Contenido actualizado de novedades

**Corregido:**

* &lbrack;captura 3D&rbrack; Mantener la posición de la cámara al cambiar la versión
* &lbrack;captura 3D&rbrack; Fusionar todos los grupos de un objeto en uno
* &lbrack;captura 3D&rbrack; Mallas generadas cuyo nombre ha cambiado a Original
* &lbrack;Aplicación&rbrack; Bloqueo al intentar generar una miniatura de una imagen que no existe
* &lbrack;Assets&rbrack; El icono de papelera no hace nada en el panel Activos
* &lbrack;Contenido&rbrack; La actualización de filtros con ranuras de material no funciona del modo esperado
* &lbrack;Exportar&rbrack; Posible bloqueo al exportar un recurso con filtros específicos
* &lbrack;Exportar&rbrack; Exportación SBS/SBSAR: las capas de importación de imágenes tenían prioridad sobre los parámetros de la imagen
* &lbrack;Exportar&rbrack; El ajuste preestablecido de exportación UE4 no funciona con PNG
* &lbrack;Capas&rbrack; Bloqueo al soltar un material y un filtro al mismo tiempo desde el explorador del sistema operativo
* &lbrack;Capas&rbrack; Bloqueo al arrastrar cualquier archivo SBSAR con cualquier archivo de imagen
* &lbrack;Capas&rbrack; El canal de opacidad del bordado puede ser completamente blanco
* &lbrack;Localización&rbrack; El idioma chino se puede mostrar de forma predeterminada en Linux
* &lbrack;Rendimiento&rbrack; Se ha corregido un problema de memoria al eliminar una capa de un recurso
* &lbrack;Proyecto&rbrack; Posible bloqueo al guardar
* &lbrack;UI&rbrack; Añadir el espaciado que falta en el botón de menú de la versión
* &lbrack;UI&rbrack; El botón Cancelar no se muestra correctamente
* &lbrack;UI&rbrack; Desactivación de la animación de los reguladores para los parámetros de posprocesamiento de captura 3D
* &lbrack;UI&rbrack; La ventana Plantilla de Creación de Materiales no se cierra al pulsar fuera
* &lbrack;UI&rbrack; El descriptor de acceso rápido de filtro se cierra al hacer clic fuera

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 4.0.2 Plátano

*(Lanzado: 9 de marzo de 2023)*

**Agregado:**

* &lbrack;captura 3D&rbrack; Uso del disco muestra la cantidad utilizada
* &lbrack;captura 3D&rbrack; La importación de fotografías es asincrónica y más rápida
* &lbrack;Secuencias de comandos&rbrack; Nuevas clases y funciones para crear scripts de la función de captura 3D
* &lbrack;Secuencias de comandos&rbrack; Nueva clase ExportController para realizar acciones cuando la exportación finaliza, falla o se cancela
* &lbrack;Secuencias de comandos&rbrack; Pase argumentos a los scripts de python ejecutados con —run-script
* &lbrack;UI&rbrack; Comentarios de la interfaz de usuario al arrastrar un recurso sobre el panel Capas
* &lbrack;Contenido&rbrack; El filtro de temperatura de color ahora está trabajando en materiales
* &lbrack;Contenido&rbrack; Normal a los filtros de Height tiene una nueva opción para conservar el mosaico

**Corregido:**

* &lbrack;captura 3D&rbrack; Tamaño de imagen corregido en el paso de alineación del conjunto de datos
* &lbrack;captura 3D&rbrack; Eliminar vértices duplicados después de desajustar UV
* &lbrack;captura 3D&rbrack; MacOS: mejor detección si hay captura 3D disponibles
* &lbrack;captura 3D&rbrack; Bloqueo al cerrar la ventana de Captura 3D al importar imágenes
* &lbrack;captura 3D&rbrack; Bloqueo al generar una nueva versión
* &lbrack;captura 3D&rbrack; Bloqueo al intentar cargar el objeto 3D en el visor
* &lbrack;captura 3D&rbrack; Bloqueo al utilizar una ruta con caracteres que no son UTF8
* &lbrack;captura 3D&rbrack; Errores tipográficos de aciertos y sugerencias
* &lbrack;captura 3D&rbrack; Las mallas ya no se escalan para ajustarse al cubo de unidades
* &lbrack;captura 3D&rbrack; Evitar un bloqueo al cerrar Captura 3D durante el procesamiento
* &lbrack;captura 3D&rbrack; Al quitar una máscara, la imagen desaparece
* &lbrack;Aplicación&rbrack; Bloqueo al importar dos veces un recurso simultáneamente
* &lbrack;Aplicación&rbrack; Hacer una copia de seguridad de la versión anterior de los recursos al abrir un proyecto si nunca se hicieron copias de seguridad
* &lbrack;Aplicación&rbrack; Almacenar mapas con bake correctamente en caché cuando no todos los mapas están procesados correctamente
* &lbrack;Aplicación&rbrack; La pantalla completa se bloquea cuando se muestra un objeto 3D.
* &lbrack;Aplicación&rbrack; El último material se duplica al guardar el proyecto
* &lbrack;Aplicación&rbrack; Evite el bloqueo al cancelar el procesamiento posterior de Mesh durante el paso de procesamiento
* &lbrack;Aplicación&rbrack; La reapertura del proyecto actual no descarta los cambios
* &lbrack;Aplicación&rbrack; Detener la generación de miniaturas para objetos 3D
* &lbrack;2D View&rbrack; Bloqueo al utilizar la herramienta Pincel
* &lbrack;Contenido&rbrack; Relleno según el contenido: el cálculo puede bloquearse
* &lbrack;Contenido&rbrack; El filtro Atlas Creator está reduciendo la escala del canal Opacidad
* &lbrack;Exportar&rbrack; Corregir borrar cola de exportaciones fallidas
* &lbrack;Exportar&rbrack; La exportación OBJ crea un objeto 100 veces más pequeño de lo esperado
* &lbrack;Capas&rbrack; Las imágenes en color importadas como canales en escala de grises ahora se consideran en escala de grises
* &lbrack;Exportar&rbrack; Los archivos FBX no se pueden importar en aplicaciones de terceros
* &lbrack;Exportar&rbrack; Los nombres de salida del sombreador en archivos USD no son correctos
* &lbrack;Capas&rbrack; El nombre de la imagen no se actualiza al cambiar su nombre en el explorador del sistema operativo
* &lbrack;Secuencias de comandos&rbrack; Mostrar un mensaje de error al volver a cargar un script no válido
* &lbrack;UI&rbrack; Botón de material base desactivado cuando no está disponible
* &lbrack;UI&rbrack; Bloqueo al acceder al cuadro de diálogo de archivo en la ventana Plantilla de creación de material
* &lbrack;UI&rbrack; Se puede acceder al descriptor de acceso rápido incluso cuando el panel Capas está cerrado
* &lbrack;UI&rbrack; Los iconos de Enviar a están alineados incorrectamente
* &lbrack;UI&rbrack; El icono de capa cambia al hacer clic en el icono de fusión

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 4.0.1 Plátano

*(Lanzado: 07 de febrero de 2023)*

**Corregido:**

* &lbrack;captura 3D&rbrack; Al utilizar máscaras, la proyección de textura puede romperse
* &lbrack;captura 3D&rbrack; Pueden aparecer artefactos en el objeto
* &lbrack;captura 3D&rbrack; La malla exportada puede ser muy pequeña

**Problemas conocidos:**

* &lbrack;captura 3D&rbrack; Las exportaciones de FBX y OBJ reducen el resultado
* &lbrack;captura 3D&rbrack; captura 3D está disponible en MacOS aunque el hardware no sea compatible. Consulte la documentación.
* &lbrack;captura 3D&rbrack; Bloqueo cuando se realiza la reconstrucción de la malla.
* &lbrack;Capas&rbrack; El Relleno según el contenido se puede bloquear si se ajustan las capas siguientes
* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 4.0.0 Plátano

*(Lanzado: 31 de enero de 2023)*

**Agregado:**

* &lbrack;captura 3D&rbrack; Creación de objetos 3D a partir de imágenes
* &lbrack;captura 3D&rbrack; Asistente para captura 3D dedicadas
* &lbrack;captura 3D&rbrack; Importar o generar máscaras en blanco y negro en el conjunto de datos
* &lbrack;captura 3D&rbrack; Resultado de la alineación: ver todas las funciones coincidentes como una nube de puntos
* &lbrack;captura 3D&rbrack; Resultado de la alineación: vea e interactúe con las cámaras asociadas a cada fotografía alineada
* &lbrack;captura 3D&rbrack; Definir el área de reconstrucción con un widget de cuadro delimitador
* &lbrack;captura 3D&rbrack; Escalar, trasladar y rotar en todos los ejes el widget de cuadro delimitador
* &lbrack;captura 3D&rbrack; Definir la precisión geométrica de la malla reconstruida
* &lbrack;captura 3D&rbrack; Optimice sus mallas y texturas creando una nueva versión
* &lbrack;captura 3D&rbrack; Cada una de las versiones se diezma automáticamente al conjunto de números de caras de destino
* &lbrack;captura 3D&rbrack; El paso posterior al proceso desenvuelve, vuelve a proyectar texturas automáticamente y, a continuación, hornea la información normal de height y AO de la malla de alta densidad de poli
* &lbrack;captura 3D&rbrack; Agregue el resultado original o una versión al proyecto de Sampler
* &lbrack;captura 3D&rbrack; Nueva capa posterior al proceso de malla para diezmar, desenvolver, volver a proyectar texturas y hornear detalles de la capa de malla subyacente de forma automática
* &lbrack;captura 3D&rbrack; Nueva capa de transformación de malla para escalar, rotar o trasladar la capa de malla subyacente
* &lbrack;Exportar&rbrack; Nueva ventana de exportación
* &lbrack;Exportar&rbrack; Ajustes e interfaz de usuario dedicados en función del tipo de activo (material, luz de entorno, malla)
* &lbrack;Exportar&rbrack; Exportar la malla como USD, USDA, USDZ, glTF, glb, obj, fbx, stl
* &lbrack;Exportar&rbrack; Definir el tipo de material al exportar ficheros de Substance (SBSAR, SBS)
* &lbrack;UI&rbrack; Mueva la configuración de la caché a una nueva pestaña en el menú emergente Preferencias
* &lbrack;Aplicación&rbrack; Las ventanas gráficas 2D y 3D ahora se pueden cambiar de tamaño, intercambiar y apilar verticalmente
* &lbrack;Aplicación&rbrack; Nueva variable de entorno SAMPLER_RESOURCES_PATH para añadir recursos de inicio adicionales
* &lbrack;Secuencias de comandos&rbrack; Se han añadido variables de entorno SAMPLER_PLUGIN_PATH y SAMPLER_SCRIPT_PATH para importar complementos y secuencias de comandos al inicio
* &lbrack;Secuencias de comandos&rbrack; Se han añadido funciones de exportación para materiales, luces de entorno y objetos 3D
* &lbrack;Secuencias de comandos&rbrack; Se han añadido a los parámetros identificadores, valores predeterminados, valores mínimos y máximos, etiquetas y valores enum
* &lbrack;Secuencias de comandos&rbrack; Se ha añadido la función import_textures para introducir un uso personalizado al importar imágenes

**Corregido:**

* &lbrack;Aplicación&rbrack; Bloqueo al abrir un proyecto reciente y guardar en el cuadro de diálogo de confirmación
* &lbrack;Aplicación&rbrack; El cuadro de diálogo Archivo impide abrir archivos .ssa
* &lbrack;Aplicación&rbrack; Los cuadros de diálogo de archivo pueden aparecer en una ventana de fondo en macOS
* &lbrack;Aplicación&rbrack; Bloqueo potencial al abrir proyectos de la versión 3.2
* &lbrack;Aplicación&rbrack; Al seleccionar un archivo, se cierra el cuadro de diálogo Archivo antes de mostrar advertencias
* &lbrack;Parámetros expuestos&rbrack; La exportación de luces de entorno paramétricas no funciona
* &lbrack;Capas&rbrack; El vínculo &quot;Haga clic aquí para examinar&quot; de la pila de capas ya no funciona
* &lbrack;Capas&rbrack; En ocasiones, pintar varias imágenes dentro de la misma capa no funciona
* &lbrack;Capas&rbrack; La configuración de una imagen en las propiedades de capa no actualiza la miniatura del selector de imágenes
* &lbrack;Capas&rbrack; La modificación de un recurso de Sampler añadido como capa no funciona
* &lbrack;Proyecto&rbrack; Actualización de recursos no deseada al abrir un proyecto
* &lbrack;Secuencias de comandos&rbrack; Buscar la carpeta del complemento a veces falla en Windows
* &lbrack;Secuencias de comandos&rbrack; Bloqueo al utilizar &#39;open_project()&#39; en un script de Python
* &lbrack;Secuencias de comandos&rbrack; Falta la exportación del JPEG en la API
* &lbrack;Secuencias de comandos&rbrack; El panel de registro no es de solo lectura
* &lbrack;Secuencias de comandos&rbrack; el valor del parámetro image_picker no funciona
* &lbrack;UI&rbrack; Falta el icono de recurso para las luces de entorno en el panel Proyecto
* &lbrack;UI&rbrack; El menú desplegable Enviar a formato Designer del menú emergente Preferencias puede estar vacío
* &lbrack;UI&rbrack; Algunos botones tienen un estilo incorrecto
* &lbrack;UI&rbrack; La etiqueta se superpone a los botones de los widgets de grupo de botones
* &lbrack;UI&rbrack; La posición de la información sobre herramientas es incorrecta para &quot;Herramientas&quot; en el menú Definir tamaño físico
* &lbrack;UI&rbrack; Al cambiar el idioma, el menú Archivo no está alineado correctamente

**Problemas conocidos:**

* &lbrack;captura 3D&rbrack; Al utilizar máscaras, la proyección de textura puede romperse
* &lbrack;captura 3D&rbrack; Pueden aparecer pequeños defectos en el objeto si la escala en la transformación de malla es demasiado pequeña
* &lbrack;captura 3D&rbrack; La malla exportada puede ser muy pequeña. Restablecer la escala de la transformación de malla y volver a exportar
* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

## Versión 3

### 3.4.1 Arancini

*(Lanzado: 6 de octubre de 2022)*

**Agregado:**

* &lbrack;Incorporación&rbrack; Nuevas pantallas de bienvenida y novedades
* &lbrack;Incorporación&rbrack; IU actualizada de la pantalla Inicio
* &lbrack;Incorporación&rbrack; Nuevo contenido de Formación en la pantalla de inicio
* &lbrack;Secuencias de comandos&rbrack; Registrar un error en el panel Registro cuando no se reconoce un método
* &lbrack;Secuencias de comandos&rbrack; Nuevo módulo ssa.helpers para habilitar la impresión en el panel Registro
* &lbrack;Aplicación&rbrack; Compatibilidad con el nuevo widget de botones en paralelo de Substance 3D Designer

**Corregido:**

* &lbrack;Exportar&rbrack; Bloqueo al exportar un archivo .sbsar que hace referencia a una imagen que falta
* &lbrack;Exportar&rbrack; Bloqueo al exportar un recurso que hace referencia a un archivo de imagen dañado
* &lbrack;Exportar&rbrack; Exportar un archivo .sbsar con una capa de bordado produce un material gris
* &lbrack;Exportar&rbrack; La exportación de un material a un archivo .sbs/sbsar puede generar un material totalmente transparente
* &lbrack;Exportar&rbrack; El parámetro Formato normal no se expone correctamente en archivos .sbs/.sbsar
* &lbrack;Exportar&rbrack; La exportación de Sbs/Sbsar de una pila de capas que hace referencia a un archivo .svg está dañada
* &lbrack;Exportar&rbrack; La capa de transformación no se exporta correctamente / Se ha actualizado el ajuste preestablecido de exportación de Enscape - Revit
* &lbrack;Parámetros expuestos&rbrack; Bloqueo al eliminar una capa que contiene un parámetro expuesto
* &lbrack;Parámetros expuestos&rbrack; La actualización de una capa obsoleta en la pila de capas puede generar una lista dañada de parámetros expuestos
* &lbrack;Parámetros expuestos&rbrack; Los parámetros que no se deben exportar se exportan de todos modos
* &lbrack;Parámetros expuestos&rbrack; La eliminación de un filtro de mezcla al eliminar una capa no deja de exponer sus parámetros
* &lbrack;Parámetros expuestos&rbrack; Los parámetros de texto rompen las exportaciones de .sbs/.sbsar
* &lbrack;Capas&rbrack; Bloqueo al soltar una pila de capas en otra pila de capas
* &lbrack;Capas&rbrack; Bloqueo al no cargar un filtro
* &lbrack;Capas&rbrack; No se puede volver a cargar la imagen anterior al restablecer el campo Imagen
* &lbrack;Capas&rbrack; No se pueden deshacer/rehacer los cambios de la herramienta de transformación
* &lbrack;Capas&rbrack; La capa Tampón de clonar se bloquea tras hacer clic en &quot;Restablecer todas las configuraciones&quot;
* &lbrack;Capas&rbrack; El uso de cualquiera de los botones de restablecimiento impide dibujar en el campo Imagen
* &lbrack;Capas&rbrack; El botón Restablecer no borra la máscara de dibujo en el campo Imagen
* &lbrack;Capas&rbrack; El botón Restablecer del campo Imagen no hace nada si el usuario ha pintado algo
* &lbrack;Capas&rbrack; La caché de procesamiento no funciona cuando se utiliza la herramienta Pincel
* &lbrack;Capas&rbrack; La capa eliminada puede seguir apareciendo en el panel Propiedades
* &lbrack;Capas&rbrack; El cálculo de capas se puede detener al cambiar entre recursos del proyecto
* &lbrack;Proyecto&rbrack; En ocasiones, Sampler no puede abrir un proyecto desde el disco
* &lbrack;2D View&rbrack; La vista 2D siempre vuelve por defecto a Salida de material

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.4.0 Arancini

*(Lanzado: 6 de septiembre de 2022)*

**Agregado:**

* &lbrack;Parámetros expuestos&rbrack; Nuevo Panel Parámetros expuestos
* &lbrack;Parámetros expuestos&rbrack; Botón Nuevo en los parámetros al pasar por encima para exponer y desexponer parámetros en el panel Propiedades
* &lbrack;Parámetros expuestos&rbrack; Nuevo menú contextual del botón derecho del ratón sobre parámetros para exponer y desexponer parámetros en el panel Propiedades
* &lbrack;Parámetros expuestos&rbrack; Los parámetros expuestos se enumeran en el Panel Parámetros expuestos
* &lbrack;Parámetros expuestos&rbrack; Los puntos de color y los discos de color se añaden en varios lugares para identificar fácilmente los parámetros expuestos
* &lbrack;Parámetros expuestos&rbrack; Las etiquetas de parámetros se pueden editar en el Panel Parámetros expuestos
* &lbrack;Parámetros expuestos&rbrack; Mostrar una advertencia para los parámetros no exportables
* &lbrack;Parámetros expuestos&rbrack; Mostrar una advertencia al mover una capa con parámetros de fusión expuestos a un lugar donde se oculten
* &lbrack;Parámetros expuestos&rbrack; Los parámetros expuestos se exportan en formatos SBS y SBSAR
* &lbrack;Metadatos&rbrack; Compatibilidad con plantillas de metadatos personalizadas
* &lbrack;Metadatos&rbrack; Nueva plantilla de metadatos de propiedades físicas de CLO
* &lbrack;Metadatos&rbrack; Añadir iconos al pasar el ratón para añadir o quitar metadatos personalizados
* &lbrack;API de Python; Nueva API de Python
* &lbrack;API de Python; API para creación de activos
* &lbrack;API de Python; API para la gestión de capas
* &lbrack;API de Python; API para la administración de parámetros
* &lbrack;API de Python; API para la administración de proyectos
* &lbrack;API de Python; Se puede activar y desactivar un complemento.
* &lbrack;API de Python; Documentación de la API de Python accesible en el menú Ayuda
* &lbrack;Secuencias de comandos&rbrack; La sección Nuevos complementos y scripts en el elemento emergente Preferencias
* &lbrack;Secuencias de comandos&rbrack; Crear e importar complementos para personalizar la interfaz de Sampler con sus propios paneles
* &lbrack;Secuencias de comandos&rbrack; Los complementos pasan a formar parte de la interfaz de Sampler y se pueden acoplar y mover como paneles estándar de Sampler
* &lbrack;Secuencias de comandos&rbrack; Barra de botones dedicada para los complementos en la barra de herramientas de la derecha de Sampler
* &lbrack;Secuencias de comandos&rbrack; Crear e importar scripts para realizar una lista de tareas determinadas
* &lbrack;Secuencias de comandos&rbrack; Inicio de scripts de Python a través del menú Scripts
* &lbrack;Secuencias de comandos&rbrack; Los complementos y los scripts se pueden eliminar, reordenar y volver a cargar desde la ventana Preferencias
* &lbrack;Secuencias de comandos&rbrack; Se han añadido parámetros de línea de comandos —run-script
* &lbrack;Logs&rbrack; Nuevo panel Registros
* &lbrack;Logs&rbrack; Habilitar el panel Registros desde la ventana Preferencias
* &lbrack;Logs&rbrack; Nueva barra de acciones para borrar, copiar y pegar registros y exportarlos
* &lbrack;Propiedades&rbrack; Botón Nuevo en el cursor de los parámetros para restablecer el valor del parámetro
* &lbrack;Propiedades&rbrack; Nuevo menú contextual del botón derecho del ratón sobre parámetros para restablecer el valor del parámetro
* &lbrack;Contenido&rbrack; Imagen a material (con tecnología de IA) ahora funciona en MacOS
* &lbrack;Motor&rbrack; Actualizar el motor de Substance a v8.6.0

**Corregido:**

* &lbrack;Aplicación&rbrack; La aplicación podía bloquearse al salir cuando estaba en curso una generación de miniaturas
* &lbrack;Aplicación&rbrack; La aplicación puede bloquearse al utilizar Guardar como al salir
* &lbrack;Aplicación&rbrack; La aplicación se podría bloquear durante el apagado en MacOS
* &lbrack;Aplicación&rbrack; Al guardar con el cuadro de diálogo de color abierto, no se guardan los cambios
* &lbrack;Exportar&rbrack; La convención de nomenclatura de uso no es correcta al exportar
* &lbrack;Capas&rbrack; La colocación de un material sobre un filtro podría bloquearse
* &lbrack;Capas&rbrack; La actualización de una pila de capas obsoleta podría actualizar pilas de capas no relacionadas
* &lbrack;Metadatos&rbrack; Se exportan los campos vacíos
* &lbrack;Metadatos&rbrack; Cuando solo hay un elemento de metadatos, la interfaz de usuario le permite intentar reordenarlo
* &lbrack;Proyecto&rbrack; La computación nunca termina después de duplicar un material
* &lbrack;Proyecto&rbrack; El recurso del proyecto se duplica después de guardar el proyecto inicial
* &lbrack;Proyecto&rbrack; Cálculos innecesarios al cambiar de recurso
* &lbrack;Procesando&rbrack; Algunas pilas de capas no se procesan correctamente después de eliminar una capa
* &lbrack;Seguridad&rbrack; Corrección de CVE-2015-20107
* &lbrack;UI&rbrack; Las salidas 2D pueden ser borrosas dependiendo del tamaño de la ventana
* &lbrack;UI&rbrack; La vista previa de activos puede permanecer abierta en la parte superior cuando la aplicación pierde el enfoque
* &lbrack;UI&rbrack; Las esquinas redondeadas de la pantalla de bienvenida tienen un fondo opaco cuadrado

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.3.2 Calabacín

*(Lanzado: 28 de junio de 2022)*

**Corregido:**

* &lbrack;Aplicación&rbrack; Solucionar un posible bloqueo al abrir un proyecto
* &lbrack;Exportar&rbrack; Al reiniciar Sampler, se rompe la lista de ajustes preestablecidos de exportación personalizados importados
* &lbrack;Interoperabilidad&rbrack; Solucionar bloqueo cuando se elimina un material enviado desde Designer y luego se vuelve a enviar desde Designer
* &lbrack;Proyecto&rbrack; No es posible eliminar el último material o luz ambiental si es el último recurso del proyecto
* &lbrack;Proyecto&rbrack; Al hacer clic con el botón derecho en una luz ambiental, aparece el asterisco &quot;modificaciones no guardadas&quot;

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.3.1 Calabacín

*(Lanzado: 07 de junio de 2022)*

**Agregado:**

* &lbrack;Aplicación&rbrack; Compatibilidad nativa con Apple Silicon (M1)
* &lbrack;UI&rbrack; Nuevo método abreviado, tecla &quot;C&quot;, para desplazarse por los canales en la vista 2D
* &lbrack;Herramientas&rbrack; Campo numérico para editar el valor de color de escala de grises en la barra de herramientas Pincel

**Corregido:**

* &lbrack;Herramientas&rbrack; El uso de la herramienta Pincel en Windows con una escala de IU fraccional (150 %) desplaza los trazos
* &lbrack;Rendimiento&rbrack; Mejorar el consumo de memoria
* &lbrack;Tamaño físico&rbrack; Puede faltar información de tamaño físico al habilitar la función
* &lbrack;UI&rbrack; El desplazamiento del ratón a veces no funciona del modo esperado al pulsar la tecla Alt
* &lbrack;Aplicación&rbrack; La aplicación puede bloquearse al abrir un proyecto guardado
* &lbrack;Aplicación&rbrack; Bloqueo al arrastrar y soltar varias imágenes y utilizar la importación de texturas en la ventana Plantilla de creación de material
* &lbrack;Aplicación&rbrack; Bloqueo potencial al guardar un proyecto que contiene un filtro personalizado
* &lbrack;Aplicación&rbrack; En ocasiones, el estado de la tecla Control se pierde al cambiar de aplicación
* &lbrack;Assets&rbrack; Bloqueo al cambiar el nombre de una carpeta local

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.3.0 Calabacín

*(Lanzado: 17 de mayo de 2022)*

**Agregado:**

* &lbrack;Contenido&rbrack; Nuevo filtro Relleno según el contenido (Windows y Mac)
* &lbrack;Contenido&rbrack; El Relleno según el contenido (Content Aware Fill) está trabajando en imágenes, materiales PBR y luces de entorno
* &lbrack;Contenido&rbrack; Añada el parámetro &quot;Conservar segmentación&quot; a Imagen a material (con tecnología de IA)
* &lbrack;Contenido&rbrack; El filtro Transformación de perspectiva puede mostrar una cuadrícula entre sus cuatro puntos
* &lbrack;Interoperabilidad&rbrack; Enviar materiales a Adobe Substance 3D Stager
* &lbrack;Herramientas&rbrack; Centrar la transformación pulsando Ctrl al cambiar el tamaño de las herramientas Transformar o Recortar
* &lbrack;Herramientas&rbrack; Bloquee la proporción al cuadrado presionando Mayús al cambiar el tamaño de las herramientas Transformar o Recortar
* &lbrack;Herramientas&rbrack; El cursor del tampón de clonar ofrece una vista previa de lo que se sellará
* &lbrack;Herramientas&rbrack; Previsualización del contenido original en el cursor del Borrador al utilizar el Tampón de clonar
* &lbrack;Herramientas&rbrack; Ctrl+Clic crea un nuevo sello en la capa Tampón de clonar
* &lbrack;Herramientas&rbrack; Los sucesivos sellos de clonación ahora se agrupan en una sola capa
* &lbrack;Herramientas&rbrack; Revampación de IU de barras de pinceles
* &lbrack;Herramientas&rbrack; La posición de la barra de herramientas Pincel es persistente durante una sesión
* &lbrack;Herramientas&rbrack; Nuevas opciones de mosaico de pinceles por eje
* &lbrack;Herramientas&rbrack; Ocultar/mostrar la superposición sobre la vista 2D al pintar
* &lbrack;Herramientas&rbrack; Nuevo método abreviado, tecla &quot;X&quot;, para alternar entre Pincel y Borrador
* &lbrack;Herramientas&rbrack; Nuevo método abreviado, &quot;&brack;&quot; &quot;&brack;&quot; para cambiar el tamaño del pincel
* &lbrack;Herramientas&rbrack; Nuevo método abreviado, tecla &quot;E&quot;, para cambiar el Borrador
* &lbrack;2D View&rbrack; Nuevo modo de Proyección esférica al crear luz ambiental
* &lbrack;2D View&rbrack; La herramienta Pincel es compatible con el modo de proyección esférica
* &lbrack;2D View&rbrack; La herramienta Posición es compatible con el modo de proyección esférica
* &lbrack;2D View&rbrack; La función Deshacer/Rehacer es compatible con el modo de proyección esférica
* &lbrack;2D View&rbrack; En Proyección esférica, defina la posición predeterminada para que mire al centro del entorno
* &lbrack;2D View&rbrack; Nuevo control de exposición
* &lbrack;UI&rbrack; En el panel Propiedades, el ajuste de imagen muestra el origen del contenido (imagen o de una capa)
* &lbrack;UI&rbrack; Se ha mejorado el fondo desplegable de las salidas de capa/material
* &lbrack;UI&rbrack; Nueva posición de la información de resolución en la vista 2D
* &lbrack;UI&rbrack; Nueva información sobre herramientas con métodos abreviados de los controles de navegación de la vista 3D
* &lbrack;UI&rbrack; Nueva información sobre herramientas con controles de pincel
* &lbrack;UI&rbrack; Nueva información sobre herramientas con métodos abreviados de controles de navegación de proyección
* &lbrack;Filtros compuestos&rbrack; Los filtros compuestos controlan las variaciones para trabajar con imágenes, materiales PBR y luces de entorno
* &lbrack;Filtros compuestos&rbrack; El orden de los ajustes coincide con el orden de la lista de nodos en el filtro compuesto
* &lbrack;Filtros compuestos&rbrack; Los ajustes de nodos diferentes con el mismo grupo se combinarán en un solo grupo en el panel Propiedades
* &lbrack;Aplicación&rbrack; Tener una configuración de visor dedicada por tipo de activo

**Corregido:**

* &lbrack;Aplicación&rbrack; La aplicación puede bloquearse al cambiar a la vista 2D
* &lbrack;Aplicación&rbrack; Solucionar un posible interbloqueo o bloqueo al exportar varias veces
* &lbrack;Aplicación&rbrack; Hacer que los valores predeterminados de los canales sean coherentes con Substance 3D Designer
* &lbrack;Aplicación&rbrack; La carga de un proyecto no activa el recálculo de material
* &lbrack;Aplicación&rbrack; Se ha actualizado la URL de la documentación de importación de texturas
* &lbrack;Contenido&rbrack; Cuando se utiliza un filtro compuesto, solicita que se actualice cuando no debería, al volver a cargar
* &lbrack;Contenido&rbrack; Los detalles del mapa de height desaparecen al utilizar la fusión de opacidad
* &lbrack;UI&rbrack; En el cuadro de diálogo Color, es posible salirse del rango mediante los campos de texto del regulador
* &lbrack;UI&rbrack; La lista de uso tiene una barra de desplazamiento vertical inútil

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente
* &lbrack;Contenido&rbrack; El widget de luz de forma no funciona en el modo de proyección esférica
* &lbrack;Interoperabilidad&rbrack; El material con el desplazamiento enviado a Stager perderá los controles de desplazamiento

### 3.2.1 Yakitori

*(Lanzado: 08 de marzo de 2022)*

**Agregado:**

* &lbrack;Exportar&rbrack; Exportación de metadatos de ppp en archivos de imagen
* &lbrack;Tamaño físico&rbrack; Mantener la proporción con texturas no cuadradas al editar dimensiones físicas
* &lbrack;Tamaño físico&rbrack; Los metadatos de tamaño físico se aplican inmediatamente cuando cambia el tamaño físico
* &lbrack;UI&rbrack; Ajuste el regulador Escala de Height máxima para que pueda influir en cualquier tipo de material cuando el Tamaño físico está activado
* &lbrack;UI&rbrack; Nuevas sugerencias sobre filtros de búsqueda en el panel Activos
* &lbrack;UI&rbrack; Utilice información sobre herramientas para explicar cuándo están desactivados los botones en el panel Activos
* &lbrack;Contenido&rbrack; Actualización del filtro de contraste de brillo

**Corregido:**

* &lbrack;2D View&rbrack; El botón de rotación de 90 grados de las herramientas Recortar y Transformar no funciona del modo esperado
* &lbrack;2D View&rbrack; El widget de recorte a veces desaparece
* &lbrack;Aplicación&rbrack; Borrar un parámetro de imagen no vuelve a conectar la capa subyacente
* &lbrack;Aplicación&rbrack; Bloqueo al salir después de guardar un proyecto
* &lbrack;Aplicación&rbrack; Se produce un bloqueo al arrastrar y soltar el material actual en una colección del panel Activos
* &lbrack;Aplicación&rbrack; La acción de arrastrar y soltar un recurso en la ventana gráfica puede bloquearse
* &lbrack;Contenido&rbrack; La mezcla normal tiene una modificación aleatoria de la semilla
* &lbrack;Contenido&rbrack; El filtro Snow tiene una salida normal incorrecta en función de los valores de los parámetros de nieve fresca y derretida
* &lbrack;Contenido&rbrack; Filtro de parquet: costuras inesperadas fijas
* &lbrack;Contenido&rbrack; Filtro de bordado: quitar rosca en mapa metálico
* &lbrack;Contenido&rbrack; Filtro de azulejos de piso: corregir el recuento de mosaicos x e y
* &lbrack;Contenido&rbrack; Filtro de pared de ladrillo: salida normal y height a 16 bits
* &lbrack;Exportar&rbrack; El nombre de archivo predeterminado en la ventana emergente de exportación no es el nombre de material actual
* &lbrack;Exportar&rbrack; La exportación con una proporción física con un ajuste preestablecido de exportación produce dimensiones incorrectas
* &lbrack;Exportar&rbrack; Falta Metallic en el ajuste preestablecido de exportación de CLO
* &lbrack;Exportar&rbrack; Al reemplazar un ajuste personalizado de exportación, el nombre para mostrar no se actualiza
* &lbrack;Capas&rbrack; No se descubren los canales personalizados de la primera capa insertada
* &lbrack;Capas&rbrack; El material se vuelve a evaluar al cambiar los ajustes de una capa oculta
* &lbrack;Localización&rbrack; La información sobre herramientas no se localiza en el panel Exportar
* &lbrack;Tamaño físico&rbrack; Al deshabilitar el Tamaño físico de un recurso no se elimina la escala física
* &lbrack;Tamaño físico&rbrack; El valor Escala de height no se puede establecer fuera de los límites del regulador la primera vez
* &lbrack;Tamaño físico&rbrack; Importar una imagen sin tamaño físico impide abrir el proyecto
* &lbrack;Tamaño físico&rbrack; El tamaño físico se establece erróneamente en cero cuando falta
* &lbrack;Tamaño físico&rbrack; El estado de la casilla de verificación Escala física de tamaño físico no se actualiza la primera vez que se muestra
* &lbrack;UI&rbrack; Material base y Normal al Height no tienen una categoría
* &lbrack;UI&rbrack; El cursor a veces es invisible al pintar una imagen
* &lbrack;UI&rbrack; Deshabilite las opciones &quot;Copiar todo&quot; y &quot;Cortar todo&quot; en el menú de edición de un campo de texto si está vacío
* &lbrack;UI&rbrack; Los nombres de filtro tienen caracteres incorrectos
* &lbrack;UI&rbrack; El botón de bloqueo del tamaño físico no tiene el estilo correcto
* &lbrack;UI&rbrack; El botón Cerrar de la barra de búsqueda del panel Activos no borra la cadena de búsqueda

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.2.0 Yakitori

*(Lanzado: 25 de enero de 2022)*

**Agregado:**

* &lbrack;Tamaño físico&rbrack; Nuevo panel Tamaño físico
* &lbrack;Tamaño físico&rbrack; Añadir opciones de Tamaño físico a la ventana Plantilla de Creación de Material
* &lbrack;Tamaño físico&rbrack; Herramienta Agregar medida de Tamaño físico
* &lbrack;Tamaño físico&rbrack; Herramienta Agregar medida automática de Tamaño físico
* &lbrack;Tamaño físico&rbrack; Herramienta Agregar diagnóstico de Tamaño físico
* &lbrack;Tamaño físico&rbrack; Permitir la configuración del valor z del Tamaño físico
* &lbrack;Tamaño físico&rbrack; Widget desplegable para establecer el nivel de zoom en la vista 2D
* &lbrack;Tamaño físico&rbrack; Nueva opción &quot;Mostrar con proporción física&quot; en el menú desplegable de nivel de zoom
* &lbrack;Tamaño físico&rbrack; Nueva opción &quot;Ajustar al tamaño físico&quot; en el menú desplegable de nivel de zoom
* &lbrack;Tamaño físico&rbrack; Mostrar el Tamaño físico en la vista 2D
* &lbrack;Tamaño físico&rbrack; Mostrar el Tamaño físico en la ventana gráfica 3D
* &lbrack;Tamaño físico&rbrack; En el cuadro de diálogo de importación de imágenes, muestre la profundidad de tamaño físico si hay un mapa de height importado
* &lbrack;Tamaño físico&rbrack; Mostrar el Tamaño físico en el menú contextual del recurso
* &lbrack;Tamaño físico&rbrack; Defina la unidad de longitud en Preferencias
* &lbrack;Tamaño físico&rbrack; Exportación de texturas respetando la proporción física
* &lbrack;Metadatos&rbrack; Posibilidad de añadir metadatos personalizados a un activo creado por el usuario
* &lbrack;Exportar&rbrack; Exportación de metadatos personalizados a archivos .sbs(ar)
* &lbrack;Exportar&rbrack; Exportar descripción, categoría, autor y etiquetas de metadatos a archivos .sbs(ar)
* &lbrack;Exportar&rbrack; Exporte el Tamaño físico a archivos .sbs(ar)
* &lbrack;Exportar&rbrack; Establecer la configuración de compresión de archivos .sbsar
* &lbrack;Exportar&rbrack; Exporte la miniatura del activo a archivos .sbs(ar)
* &lbrack;Exportar&rbrack; Definir el tipo de gráfico al exportar un archivo .sbs(ar)
* &lbrack;Aplicación&rbrack; El motor en tiempo real 2021 ya no está disponible
* &lbrack;Aplicación&rbrack; Ahora, Deshacer/Rehacer admite cambios de segmentación (U,V) y de escala de height
* &lbrack;Procesando&rbrack; Generar caché de disco al guardar el activo creado
* &lbrack;Assets&rbrack; Utilice Ctrl+clic para activar varios filtros de tipo de recurso en el panel Recursos
* &lbrack;UI&rbrack; Posibilidad de bloquear los reguladores de Mosaico (U,V)
* &lbrack;UI&rbrack; Añadir un menú contextual con &quot;Copiar&quot;, &quot;Cortar&quot;, &quot;Pegar&quot;, &quot;Copiar todo&quot; y &quot;Cortar todo&quot; en los campos de texto
* &lbrack;UI&rbrack; Unidad de longitud (metros, pulgadas, parsecs, ...) compatibilidad con etiquetas y campos de texto
* &lbrack;UI&rbrack; El usuario puede establecer la precisión decimal utilizada para mostrar los números
* &lbrack;UI&rbrack; Utilice las unidades en las ventanas emergentes de medida en todas partes que sea relevante
* &lbrack;Localización&rbrack; El nombre del nuevo recurso predeterminado ahora está localizado
* &lbrack;Contenido&rbrack; Nuevo generador de tejido de tela
* &lbrack;Contenido&rbrack; Nuevo filtro de cambio de canal
* &lbrack;Contenido&rbrack; Todos los filtros relevantes son ahora conscientes del Tamaño físico
* &lbrack;Contenido&rbrack; Nuevos iconos para Acabado en Madera
* &lbrack;Contenido&rbrack; Todos los filtros son ahora compatibles con los canales de Adobe de materiales estándar (ASM)
* &lbrack;Contenido&rbrack; Los filtros ahora pueden tener una variación de &quot;entorno&quot;

**Corregido:**

* &lbrack;2D View&rbrack; El canal permanece en la lista cuando se elimina
* &lbrack;Aplicación&rbrack; No se puede duplicar un recurso cargado desde el explorador de archivos del sistema operativo
* &lbrack;Aplicación&rbrack; Bloqueo al salir
* &lbrack;Aplicación&rbrack; Se produce un bloqueo al hacer clic en &quot;Activos iniciales&quot; en el panel Activos
* &lbrack;Aplicación&rbrack; Bloqueo al eliminar un material
* &lbrack;Aplicación&rbrack; La variable de entorno &quot;SUBSTANCE_DISABLE_SPECIFIC_FEATURES&quot; sigue activa cuando se define en &quot;0&quot; o &quot;&quot;.
* &lbrack;Aplicación&rbrack; Bloqueo al guardar un proyecto con varios materiales
* &lbrack;Aplicación&rbrack; Importar una imagen puede provocar un bloqueo
* &lbrack;Aplicación&rbrack; Faltan algunos recursos de inicio en el primer inicio
* &lbrack;Exportar&rbrack; La exportación de un activo a veces produce un bloqueo
* &lbrack;Capas&rbrack; No se pueden importar imágenes cuando el panel Capa está cerrado o es invisible
* &lbrack;Capas&rbrack; Al cambiar el idioma, se vuelve a calcular el activo actual
* &lbrack;Capas&rbrack; Al cambiar el uso de una imagen importada, no se actualiza la variación de filtro que se debe utilizar
* &lbrack;Capas&rbrack; A veces, la imagen a material (IA) no se calcula al ajustar capas por debajo de ella
* &lbrack;Capas&rbrack; A veces, la imagen a material (IA) se vuelve a calcular cuando no es necesario
* &lbrack;Capas&rbrack; No se sugiere ninguna actualización cuando se actualiza un filtro personalizado en el disco
* &lbrack;Capas&rbrack; El canal normal a veces tiene un formato de píxel incorrecto
* &lbrack;Capas&rbrack; Algunas capas aún se calculan incluso cuando no están visibles
* &lbrack;Capas&rbrack; Las herramientas de la vista 2D pueden romperse al cambiar la visibilidad de una capa
* &lbrack;Capas&rbrack; La interfaz de usuario se bloquea al utilizar Imagen a material (AI)
* &lbrack;Capas&rbrack; Al cambiar la visibilidad de la capa de filtro Transformar, se rompe la herramienta de vista 2D y puede producirse un bloqueo
* &lbrack;Capas&rbrack; Demasiados cálculos al eliminar una capa de la pila de capas
* &lbrack;Capas&rbrack; Cuando un filtro compuesto contiene una entrada/salida inusual o personalizada, Sampler no la calcula
* &lbrack;Rendimiento&rbrack; El panel Activos tarda en abrirse
* &lbrack;Rendimiento&rbrack; Evite algunos cálculos innecesarios de la pila de capas
* &lbrack;Rendimiento&rbrack; La carga de recursos del proyecto tarda demasiado tiempo
* &lbrack;Rendimiento&rbrack; No se puede usar la caché de procesamiento en el disco
* &lbrack;Rendimiento&rbrack; El cambio entre capas es lento
* &lbrack;Rendimiento&rbrack; La modificación de un material o un filtro es lenta
* &lbrack;Proyecto&rbrack; Guardar un proyecto al salir puede producir un bloqueo
* &lbrack;Procesando&rbrack; Al quitar una imagen, es posible que se eliminen todas las salidas
* &lbrack;Procesando&rbrack; El tiempo de procesamiento mostrado en la ventana gráfica es incorrecto al realizar ajustes
* &lbrack;UI&rbrack; No se puede desplazar verticalmente en la ventana emergente de exportación cuando es necesario
* &lbrack;UI&rbrack; Es posible abrir la ventana emergente de exportación cuando no hay nada que exportar
* &lbrack;UI&rbrack; Algunas ventanas emergentes no se desplazan si su contenido se desborda
* &lbrack;UI&rbrack; Los campos de texto no se seleccionan al hacer clic en ellos o abrir un menú
* &lbrack;UI&rbrack; El nombre del modo de fusión en el panel de propiedades a veces no es correcto
* &lbrack;UI&rbrack; La opción Guardar del menú Archivo a veces está atenuada
* &lbrack;UI&rbrack; El campo de texto no desaparece después de cambiar el nombre de dos materiales
* &lbrack;UI&rbrack; Error tipográfico en la ventana emergente de preferencias

**Problemas conocidos:**

* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.1.2 Xocoatl

*(Lanzado: 14 de diciembre de 2021)*

**Corregido:**

* &lbrack;Interoperabilidad&rbrack; El archivo .sbsar abierto con Substance 3D Sampler desde Bridge puede fallar en Windows
* &lbrack;Capas&rbrack; Si mueve la única capa por debajo de sí misma, se producirá un bloqueo
* &lbrack;UI&rbrack; El botón Configuración de canal desaparece al cambiar el idioma
* &lbrack;UI&rbrack; El nombre del material en el panel Propiedades desaparece después de guardar el proyecto
* &lbrack;Assets&rbrack; Hacer clic en &quot;Todas las bibliotecas&quot; puede provocar un bloqueo

**Problemas conocidos:**

* &lbrack;Motor en tiempo real 2021&rbrack; El cálculo intensivo puede bloquear la aplicación
* &lbrack;Motor en tiempo real 2021&rbrack; Realtime Engine 2021 se bloqueará en un equipo Windows con la CPU AMD y la GPU NVIDIA instaladas
* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.1.1 Xocoatl

*(Lanzado: 24 de noviembre de 2021)*

**Agregado:**

* &lbrack;Interoperabilidad&rbrack; Enviar recursos (SBS o SBSAR) a Substance 3D Designer
* &lbrack;Interoperabilidad&rbrack; Defina en las preferencias el formato predeterminado para la interoperabilidad con Substance 3D Designer
* &lbrack;Interoperabilidad&rbrack; Recibir varios recursos de Adobe Bridge
* &lbrack;UI&rbrack; Nuevo widget Raíz aleatoria
* &lbrack;UI&rbrack; Actualización del menú contextual
* &lbrack;Assets&rbrack; Arrastrar y soltar imágenes desde el panel Activos al panel Propiedades
* &lbrack;Proyecto&rbrack; Los nombres de los activos se corrigen para evitar algunos caracteres específicos
* &lbrack;Marca&rbrack; Icono Actualizar archivo para archivos SBSAR
* &lbrack;Motor&rbrack; Actualizar Substance Engine versión 8.3.0

**Corregido:**

* &lbrack;Contenido&rbrack; Recortar: conservar proporción al recortar imágenes no cuadradas
* &lbrack;Contenido&rbrack; Transformar: la transformación horizontal no se invierte al utilizar el widget
* &lbrack;Contenido&rbrack; Grava: corrija la pintura de máscara personalizada en todos los canales
* &lbrack;Contenido&rbrack; Baldosas de suelo: solucione problemas con el azulejo de motivos y la repetición
* &lbrack;Assets&rbrack; Opción Gris hacia fuera en Adobe Bridge si no está instalada
* &lbrack;Selector de color&rbrack; La tecla Escape cierra el Selector de color
* &lbrack;Procesando&rbrack; Corrección de la escala de distancia de dispersión al utilizar la entrada de escala de grises
* &lbrack;Compartir&rbrack; Las opciones Enviar a solo están disponibles con licencias de Adobe
* &lbrack;Proyecto&rbrack; Solucionar un problema de rendimiento de memoria

**Problemas conocidos:**

* &lbrack;Motor en tiempo real 2021&rbrack; El cálculo intensivo puede bloquear la aplicación
* &lbrack;Motor en tiempo real 2021&rbrack; Realtime Engine 2021 se bloqueará en un equipo Windows con la CPU AMD y la GPU NVIDIA instaladas
* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.1.0 Xocoatl

*(Lanzado: 28 de septiembre de 2021)*

**Agregado:**

* &lbrack;Selector de color&rbrack; Nueva interfaz de usuario del selector de color
* &lbrack;Selector de color&rbrack; Vista previa de los colores actuales y anteriores en paralelo
* &lbrack;Selector de color&rbrack; Introducir el color en hexadecimal
* &lbrack;Selector de color&rbrack; Nuevo cuentagotas con previsualización de color
* &lbrack;Selector de color&rbrack; El cuentagotas puede seleccionar un color fuera de Sampler
* &lbrack;Selector de color&rbrack; Ajustar el color en espacios de color RGB o HSV
* &lbrack;Selector de color&rbrack; Almacenamiento y gestión de muestras
* &lbrack;Interoperabilidad&rbrack; Editar imágenes en Illustrator desde la capa de importación de imágenes o los parámetros de imagen
* &lbrack;Interoperabilidad&rbrack; Editar imágenes en Photoshop desde la capa de importación de imágenes o los parámetros de imagen
* &lbrack;Widget&rbrack; Nuevo widget de recorte
* &lbrack;Widget&rbrack; Pulsa la tecla Entrar para validar el recorte
* &lbrack;Widget&rbrack; El widget Recortar lee el tamaño de la imagen para que se ajuste al widget y mantiene la proporción al cambiar el tamaño
* &lbrack;UI&rbrack; Nueva interfaz de usuario del regulador de escala de grises
* &lbrack;Aplicación&rbrack; Añadir la selección de formato normal en las preferencias
* &lbrack;Aplicación&rbrack; El formato normal de las capas de importación de imágenes sigue el formato normal predeterminado establecido en las preferencias
* &lbrack;Aplicación&rbrack; En la vista 2D, la normal se muestra según el formato normal definido en las preferencias
* &lbrack;Aplicación&rbrack; La normal se exporta en el formato normal definido en las preferencias
* &lbrack;Exportar&rbrack; Agregar un parámetro de formato normal a las exportaciones de archivos SBS y SBSAR
* &lbrack;Exportar&rbrack; Añadir configuración de sombreado a las exportaciones de archivos SBS y SBSAR
* &lbrack;Exportar&rbrack; Definir la resolución predeterminada de los gráficos SBS exportados
* &lbrack;Filtros compuestos&rbrack; Empaquetar filtros SSA con 7z
* &lbrack;Filtros compuestos&rbrack; Adición de metadatos de categoría en filtros compuestos
* &lbrack;Filtros compuestos&rbrack; Los filtros compuestos pueden tener una miniatura incrustada
* &lbrack;Filtros compuestos&rbrack; Se ha añadido la extensión Filtros compuestos (.ssafilter) al cuadro de diálogo Obtener contenido del archivo
* &lbrack;Filtros compuestos&rbrack; Importar filtros compuestos (.ssafilter) en el panel Activos
* &lbrack;Motor&rbrack; Actualizar el motor de Substance a la versión 8.2.0

**Corregido:**

* &lbrack;Aplicación&rbrack; Las carpetas locales conectadas pueden bloquearse
* &lbrack;Aplicación&rbrack; Bloqueo al salir
* &lbrack;Aplicación&rbrack; Bloqueo al iniciar dos instancias de Sampler
* &lbrack;Contenido&rbrack; El filtro Recortar tiene un ajuste aleatorio de la velocidad
* &lbrack;Contenido&rbrack; Algunos materiales de Substance a veces no se actualizan
* &lbrack;Exportar&rbrack; Bloqueo al exportar con un ajuste preestablecido personalizado recién añadido
* &lbrack;Exportar&rbrack; Falta el tamaño estimado del paquete en la ventana emergente de exportación
* &lbrack;Exportar&rbrack; Corregir pérdidas de memoria al exportar archivos SBS y SBSAR
* &lbrack;Filtros compuestos&rbrack; Los filtros compuestos pueden tener entradas duplicadas
* &lbrack;Filtros compuestos&rbrack; Bloqueo si un filtro tiene referencias no satisfechas
* &lbrack;Filtros compuestos&rbrack; Bloqueo al reordenar una pila de capas con un filtro compuesto
* &lbrack;Filtros compuestos&rbrack; El renderizado a veces se bloquea
* &lbrack;Importación de imágenes&rbrack; Importar una imagen activa varias representaciones
* &lbrack;Capas&rbrack; Bloqueo al deshacer o rehacer
* &lbrack;Capas&rbrack; Bloqueo al añadir un Material base
* &lbrack;Capas&rbrack; Bloqueo al utilizar una imagen no válida como luz de entorno
* &lbrack;Capas&rbrack; Corregir la importación duplicada al insertar un filtro con varios gráficos
* &lbrack;Capas&rbrack; La reordenación de capas no siempre funciona
* &lbrack;Proyecto&rbrack; Bloqueo al cargar un archivo de proyecto incompleto
* &lbrack;Proyecto&rbrack; Bloqueo al abrir un proyecto dañado
* &lbrack;Proyecto&rbrack; Algunos recursos pueden desaparecer de un proyecto
* &lbrack;Propiedades&rbrack; Corregir los ajustes preestablecidos de filtros que faltan
* &lbrack;UI&rbrack; No se pueden establecer parámetros de ángulo
* &lbrack;UI&rbrack; Visualización de metadatos de filtros en el panel Activos
* &lbrack;UI&rbrack; Agrupar por categoría oculta filtros
* &lbrack;UI&rbrack; Problema de desplazamiento en el panel Activos
* &lbrack;UI&rbrack; El panel Exportar ahora tiene una barra de desplazamiento
* &lbrack;UI&rbrack; La miniatura no se muestra para algunos formatos de imagen en el selector de imágenes

**Problemas conocidos:**

* &lbrack;Motor en tiempo real 2021&rbrack; El cálculo intensivo puede bloquear la aplicación
* &lbrack;Motor en tiempo real 2021&rbrack; Realtime Engine 2021 se bloqueará en un equipo Windows con la CPU AMD y la GPU NVIDIA instaladas
* &lbrack;Selector de color&rbrack; Es posible que no funcione seleccionar un color en un segundo monitor con una resolución diferente

### 3.0.1 Waffle

*(Lanzado: 27 de julio de 2021)*

**Agregado:**

* &lbrack;Brush&rbrack; Activar colores en la herramienta Pincel si la entrada de imagen lo admite
* &lbrack;Brush&rbrack; Si mantiene pulsada la tecla Mayús en la herramienta Pincel, se dibujarán líneas rectas
* &lbrack;Brush&rbrack; Mostrar una previsualización de línea al mantener pulsada la tecla Mayús en la herramienta Pincel
* &lbrack;Brush&rbrack; La herramienta Pincel ahora admite deshacer y rehacer
* &lbrack;2D View&rbrack; El color predeterminado de entrada de imagen se utiliza al pintar
* &lbrack;Capas&rbrack; Leer el valor predeterminado de entrada del Substance en archivos SBSAR
* &lbrack;Procesando&rbrack; Permitir combinar el height con normal
* &lbrack;Procesando&rbrack; Compatibilidad con la dispersión subsuperficial (no disponible en MacOS)
* &lbrack;Assets&rbrack; Usar el tipo de gráfico SBSAR para determinar el tipo de activo
* &lbrack;Assets&rbrack; Mejor rendimiento para la búsqueda y la detección de activos en el panel Activos
* &lbrack;Assets&rbrack; Se ha añadido la entrada &quot;Todas las bibliotecas&quot; en el panel Activos, que muestra todos los activos de todas las bibliotecas
* &lbrack;Assets&rbrack; El usuario ahora puede elegir agrupar activos por categoría o tipo
* &lbrack;Importar&rbrack; Detección automática de texturas de anisotropía, capa, brillo y specular edge color en la importación
* &lbrack;UI&rbrack; Sustitución del título del panel protegido por un icono
* &lbrack;UI&rbrack; Actualización de estilo de Textfields
* &lbrack;UI&rbrack; Nuevo texto de descripción en la ventana Creación de plantillas de luz de entorno
* &lbrack;Aplicación&rbrack; Exportar recursos con la resolución actual al enviarlos a una aplicación externa
* &lbrack;Aplicación&rbrack; La resolución predeterminada del material es ahora 2048\*2048 (1024\*1024 en macos)
* &lbrack;Contenido&rbrack; Nuevos patrones en el filtro de azulejos de piso
* &lbrack;Contenido&rbrack; Nuevo modo de color dual en el filtro de reemplazo de color

**Corregido:**

* &lbrack;2D View&rbrack; El primer trazo de la herramienta Pincel a veces se rompe
* &lbrack;2D View&rbrack; Recursos libres cuando la herramienta Pincel no está visible
* &lbrack;2D View&rbrack; Usar el cursor de cambio de tamaño adecuado en el widget de transformación
* &lbrack;2D View&rbrack; Los widgets no se muestran si el usuario ha realizado una panorámica en la vista 2D antes
* &lbrack;Aplicación&rbrack; Bloqueo al abrir un proyecto con un flujo de trabajo interrumpido
* &lbrack;Aplicación&rbrack; Solucionar el cierre de la aplicación para evitar que el registro se llene de errores inútiles
* &lbrack;Aplicación&rbrack; Los métodos abreviados de teclado para rehacer, eliminar y guardar no funcionan en algunos sistemas operativos
* &lbrack;Aplicación&rbrack; El cambio de deshacer/rehacer del uso de la imagen en la capa de importación no funciona
* &lbrack;Exportar&rbrack; Las imágenes exportadas con color de emisión tienen un nombre incorrecto
* &lbrack;Exportar&rbrack; El entorno es de 8 bits al utilizar la exportación SBSAR
* &lbrack;Exportar&rbrack; Eliminación de espacios adicionales en los nombres de archivos de imagen exportados
* &lbrack;Exportar&rbrack; La sustitución o eliminación de un ajuste preestablecido de exportación personalizado se bloquea
* &lbrack;Capas&rbrack; Evite el bloqueo cuando haya una discrepancia en el recuento de entradas
* &lbrack;Capas&rbrack; Bloqueo al insertar una capa de Material base
* &lbrack;Capas&rbrack; El recuento de entrada de filtro se limita al valor predeterminado
* &lbrack;Capas&rbrack; Rehacer cambia erróneamente el tipo de fusión a fusión de Height
* &lbrack;Capas&rbrack; Quitar zona de colocación encima de los encabezados de entrada
* &lbrack;Capas&rbrack; Las capas se insertan en el lugar incorrecto alrededor de los encabezados de entrada
* &lbrack;Capas&rbrack; El botón Restablecer todos los ajustes no restablece los valores de los widgets desplegables
* &lbrack;Capas&rbrack; Deshacer/rehacer al cambiar una imagen en la capa de importación de imágenes marca el proyecto como modificado y, por lo tanto, para guardarlo
* &lbrack;Capas&rbrack; Las capas de mezcla pueden detener los usos
* &lbrack;Proyecto&rbrack; Bloqueo al cargar un proyecto heredado con la carpeta de dependencias que faltan
* &lbrack;Proyecto&rbrack; Bloqueo al utilizar deshacer/rehacer después de guardar
* &lbrack;Proyecto&rbrack; Al abrir un archivo SBSAR que contiene una luz ambiental, se crea un activo material
* &lbrack;Proyecto&rbrack; Cambiar el nombre de un material puede desencadenar la generación de miniaturas
* &lbrack;Proyecto&rbrack; Guardar después de cambiar el nombre de un material marca el proyecto como no modificado
* &lbrack;Proyecto&rbrack; Algunos cambios realizados después de cambiar el nombre de un material no se guardan
* &lbrack;Procesando&rbrack; Los puntos brillantes se ven en el entorno con el motor en tiempo real de 2020
* &lbrack;Procesando&rbrack; Bloqueo al cambiar el tamaño con Real Time Engine 2021
* &lbrack;Procesando&rbrack; Calcular sombras al cambiar el nivel del height
* &lbrack;Assets&rbrack; Las carpetas conectadas dejan de indizar nuevos recursos al agregar un archivo no válido
* &lbrack;Assets&rbrack; Bloqueo al conectar una carpeta local con muchos materiales
* &lbrack;UI&rbrack; Faltan descripciones emergentes de los botones de vista 2D/3D
* &lbrack;UI&rbrack; Todos los activos del panel Activos aparecen resaltados al iniciarse
* &lbrack;UI&rbrack; A veces, las rutas de navegación desaparecen en el panel Activos al importar materiales
* &lbrack;UI&rbrack; Cambiar el idioma no afecta al panel Proyecto
* &lbrack;UI&rbrack; El panel Configuración de canal muestra información del flujo de trabajo heredado
* &lbrack;UI&rbrack; Alinear correctamente el texto &quot;Sin configuración para este elemento&quot; para filtros sin ajustes en el panel Propiedades
* &lbrack;UI&rbrack; Los elementos se desalinean en la pantalla de bienvenida y aparecen las preferencias
* &lbrack;UI&rbrack; Los títulos del panel tienen un ancho incorrecto
* &lbrack;UI&rbrack; El desplazamiento a veces se interrumpe en el panel Propiedades
* &lbrack;UI&rbrack; La pantalla de bienvenida tiene una proporción incorrecta y está borrosa
* &lbrack;UI&rbrack; El modo de pantalla completa no es de pantalla completa
* &lbrack;UI&rbrack; Los paneles no acoplados siempre están en la parte superior, incluso cuando la aplicación no está activa en MacOS
* &lbrack;UI&rbrack; Imagen del banner de la pantalla de bienvenida
* &lbrack;Contenido&rbrack; El filtro de segmentación no procesa el canal de oclusión de ambiente
* &lbrack;Contenido&rbrack; Problema de puntada de tejido con la selección de la costura del conjunto de soldadura y el patrón de diamante
* &lbrack;Contenido&rbrack; El filtro de relieve funciona en 256 x 256 px
* &lbrack;Contenido&rbrack; Corregir el problema de mosaico con los mosaicos de suelo cuando el desplazamiento es mayor que 0

**Problemas conocidos:**

* &lbrack;Motor en tiempo real 2021&rbrack; Cálculo intenso, bloqueo de la aplicación
* &lbrack;Motor en tiempo real 2021&rbrack; Realtime Engine 2021 se bloquea en equipos Windows con CPU AMD y GPU NVIDIA

### 3.0.0 Waffle

*(Lanzado: 23 de junio de 2021)*

**Agregado:**

* &lbrack;Marca&rbrack; Substance Alchemist se convierte en Adobe Substance 3D Sampler
* &lbrack;Marca&rbrack; Nuevos iconos de aplicación
* &lbrack;UI&rbrack; Nueva experiencia de usuario e interfaz de usuario
* &lbrack;UI&rbrack; Nueva pantalla de presentación
* &lbrack;UI&rbrack; Los paneles son desacoplables y acoplables en la interfaz
* &lbrack;UI&rbrack; Acoplar hasta 3 paneles en la misma columna
* &lbrack;UI&rbrack; Acoplar hasta 3 paneles en el mismo panel (pestañas)
* &lbrack;UI&rbrack; Desacoplar paneles para crear una ventana independiente en la misma pantalla o en otra distinta
* &lbrack;UI&rbrack; Los paneles cerrados aparecen al hacer clic en sus iconos
* &lbrack;UI&rbrack; Reorganización de la barra izquierda y derecha moviendo los iconos de los paneles
* &lbrack;UI&rbrack; Nueva barra de herramientas para acceder directamente a filtros específicos (Recortar, Transformar, Transformación de perspectiva, Tampón de clonar)
* &lbrack;UI&rbrack; Nuevo botón &quot;Obtener contenido&quot; en la barra izquierda
* &lbrack;UI&rbrack; Importar archivos directamente en los activos con el botón Obtener contenido
* &lbrack;UI&rbrack; Importa archivos directamente a tus capas con el botón Obtener contenido
* &lbrack;UI&rbrack; Acceder directamente al sitio web de Adobe Substance 3D Assets con el botón Obtener contenido
* &lbrack;UI&rbrack; Ahora se puede acceder directamente al widget de resolución en la ventana gráfica
* &lbrack;UI&rbrack; Todos los elementos de la interfaz de usuario ahora se cargan dinámicamente
* &lbrack;UI&rbrack; Método abreviado: utilice &quot;2&quot; para cambiar la visibilidad de la vista 2D
* &lbrack;UI&rbrack; Método abreviado: utilice &quot;3&quot; para cambiar la visibilidad de la vista 3D
* &lbrack;Pantalla de bienvenida&rbrack; Crear un proyecto con un solo clic con el botón Nuevo
* &lbrack;Pantalla de bienvenida&rbrack; Banner de nueva ilustración
* &lbrack;Proyecto&rbrack; Todos los proyectos se asocian ahora a un archivo único
* &lbrack;Proyecto&rbrack; Nueva extensión de archivo de proyecto .ssa
* &lbrack;Proyecto&rbrack; Guardar como proyecto le pedirá que seleccione dónde guardar el proyecto
* &lbrack;Proyecto&rbrack; Al cerrar Sampler, se le pedirá que guarde el proyecto si no se ha guardado
* &lbrack;Proyecto&rbrack; Al cerrar Sampler, se le pedirá que guarde el proyecto si hay modificaciones desde la última operación de guardado
* &lbrack;Proyecto&rbrack; El nombre del proyecto se muestra encima de la ventana gráfica
* &lbrack;Proyecto&rbrack; El nombre del proyecto aparece en cursiva con una estrella si no se ha guardado o si contiene modificaciones desde la última operación de guardado
* &lbrack;Proyecto&rbrack; Abra un archivo de proyecto .ssa directamente desde el explorador del sistema operativo
* &lbrack;Proyecto&rbrack; Si abre un archivo .sbsar desde el explorador del sistema operativo, Sampler se iniciará con un nuevo proyecto que ya podrá utilizar
* &lbrack;Proyecto&rbrack; Abra un archivo .alch (archivo Substance Alchemist heredado) desde el explorador del sistema operativo
* &lbrack;Panel Proyecto&rbrack; Nuevo panel que contendrá todos los recursos creados dentro de un proyecto
* &lbrack;Panel Proyecto&rbrack; Cree un activo (material o luz ambiental) mediante el icono +
* &lbrack;Panel Proyecto&rbrack; Al hacer clic con el botón derecho en un recurso, se abre un menú contextual
* &lbrack;Panel Proyecto&rbrack; En el menú contextual que se muestra al hacer clic con el botón derecho, puede eliminar un activo
* &lbrack;Panel Proyecto&rbrack; En el menú contextual que se muestra al hacer clic con el botón derecho, puede duplicar un activo
* &lbrack;Panel Proyecto&rbrack; En el menú contextual que se muestra al hacer clic con el botón derecho, puede cambiar el nombre de un activo
* &lbrack;Panel Proyecto&rbrack; Cambiar entre activos no perderá modificaciones
* &lbrack;Resolución&rbrack; Ahora puede establecer una resolución no cuadrada para todos sus activos
* &lbrack;Resolución&rbrack; El valor de resolución se guarda por recurso dentro de un proyecto
* &lbrack;Luz del entorno&rbrack; Crear luz ambiental en Substance 3D Sampler
* &lbrack;Luz del entorno&rbrack; Al crear una luz de entorno, al arrastrar y soltar imágenes se mostrará la ventana Plantilla de creación de luz de entorno
* &lbrack;Luz del entorno&rbrack; En Plantilla de creación de luz de entorno, seleccione Importar entorno para asignar la imagen al entorno en la vista 3D
* &lbrack;Luz del entorno&rbrack; En la plantilla de creación de luz de entorno, seleccione la combinación HDR para crear una luz de entorno a partir de varias imágenes de 360 grados con diferente exposición
* &lbrack;Luz del entorno&rbrack; En la plantilla de creación de luz ambiental, seleccione &quot;Usar como mapa de bits&quot; para editar las imágenes antes de crear una luz ambiental
* &lbrack;Luz del entorno&rbrack; Asigne el uso del entorno en la capa de importación de imágenes para asignar directamente la imagen al entorno en la vista 3D
* &lbrack;Luz del entorno&rbrack; En la vista 2D del canal de entorno, existe una corrección de color automática para que el procesamiento tenga el mismo aspecto que en la vista 3D
* &lbrack;Luz del entorno&rbrack; Nuevo contenido dedicado para la creación de luz ambiental
* &lbrack;Panel de recursos&rbrack; Los paneles Recursos y Filtros se combinan en un nuevo panel Activos
* &lbrack;Panel de recursos&rbrack; El panel Activos ahora admite los siguientes tipos de activos: materiales, filtros e imágenes
* &lbrack;Panel de recursos&rbrack; Se puede acceder a todos los Activos iniciales en la sección Activos iniciales
* &lbrack;Panel de recursos&rbrack; La sección Activos iniciales es de solo lectura
* &lbrack;Panel de recursos&rbrack; Nueva sección &quot;Sus activos&quot;
* &lbrack;Panel de recursos&rbrack; La sección &quot;Sus activos&quot; es el lugar donde puede importar todos sus recursos
* &lbrack;Panel de recursos&rbrack; Todos los activos de &quot;Sus activos&quot; se añaden a una carpeta específica de sus Documentos
* &lbrack;Panel de recursos&rbrack; Conectar carpetas locales en el panel Activos para añadir nuevas secciones
* &lbrack;Panel de recursos&rbrack; La búsqueda buscará en la carpeta actual y sus subcarpetas
* &lbrack;Panel de recursos&rbrack; Desplazarse entre carpetas y subcarpetas con rutas de exploración
* &lbrack;Panel de recursos&rbrack; Filtrar la carpeta actual por material, filtro o imagen
* &lbrack;Panel de recursos&rbrack; Combina varios filtros para obtener solo materiales e imágenes
* &lbrack;Panel de recursos&rbrack; Cambiar la visualización cambiando entre una cuadrícula o una lista
* &lbrack;Panel de recursos&rbrack; Los filtros se representan con su icono
* &lbrack;Panel de recursos&rbrack; Las imágenes se representan con su previsualización
* &lbrack;Panel de recursos&rbrack; Al aumentar la anchura, se cambiará el diseño del panel con una vista específica para desplazarse por las carpetas
* &lbrack;Panel de recursos&rbrack; En las secciones que no sean de solo lectura, elimine un recurso arrastrándolo y soltándolo en el icono de la papelera
* &lbrack;Panel de recursos&rbrack; Al hacer clic con el botón derecho en un recurso, se abre un menú contextual
* &lbrack;Panel de recursos&rbrack; En el menú contextual del botón derecho, acceda a los metadatos del activo (nombre, categoría, ubicación)
* &lbrack;Panel de recursos&rbrack; En el menú contextual, elimine el activo (solo disponible en las secciones de no solo lectura)
* &lbrack;Panel de recursos&rbrack; En el menú contextual del botón derecho, examine el contenido en Adobe Bridge
* &lbrack;Panel Capas&rbrack; Nuevo icono para añadir directamente un material base encima de las capas
* &lbrack;Panel Capas&rbrack; Método abreviado : Mayús + B añadirá un material base encima de las capas
* &lbrack;Panel Capas&rbrack; Las capas ahora tienen una vista previa en miniatura (miniatura de material, icono de filtro o vista previa de imagen)
* &lbrack;Panel Propiedades&rbrack; Nuevo diseño del título del panel Propiedades con el nombre del recurso y la miniatura del recurso
* &lbrack;Panel Propiedades&rbrack; Las capas de filtro ahora admiten ajustes preestablecidos
* &lbrack;Panel Propiedades&rbrack; En Capa de importación de imágenes, haga clic con el botón derecho en la vista previa de la imagen para editarla en Photoshop
* &lbrack;Adobe Bridge&rbrack; Examine el recurso en Adobe Bridge; Bridge se iniciará en la ubicación del recurso
* &lbrack;Adobe Photoshop&rbrack; Editar en Adobe Photoshop abrirá la imagen en Photoshop lista para editarse
* &lbrack;Adobe Photoshop&rbrack; En cada operación de guardar en Adobe Photoshop, la imagen editada se volverá a cargar en Sampler
* &lbrack;Substance 3D Designer&rbrack; Los contenidos enviados desde Adobe Substance 3D Designer aparecerán directamente en la sección &quot;Sus contenidos&quot; del panel de contenidos
* &lbrack;Exportar&rbrack; Enviar recursos directamente a Adobe Substance 3D Painter y Adobe Substance 3D Stager
* &lbrack;Exportar&rbrack; Enviar materiales y luces de entorno a Adobe Substance 3D Painter
* &lbrack;Exportar&rbrack; Enviar luces de entorno a Adobe Substance 3D Stager
* &lbrack;Procesando&rbrack; Las nuevas propiedades de material ahora son compatibles y se representan en 3D
* &lbrack;Procesando&rbrack; Adición de la compatibilidad de brillo (Color de brillo, opacidad de brillo y rugosidad de brillo)
* &lbrack;Procesando&rbrack; Añadir soporte de recubrimiento (Color de la capa, Rugosidad de la capa, Normal de la capa, Specular level de la capa y IOR de la capa)
* &lbrack;Procesando&rbrack; Adición de compatibilidad de Anisotropía (nivel de Anisotropía y ángulo de Anisotropía)
* &lbrack;Procesando&rbrack; Adición de compatibilidad con Speculares edges color
* &lbrack;Procesando&rbrack; Active estas nuevas propiedades en el panel Configuración de canal
* &lbrack;Procesando&rbrack; Introducción de un nuevo procesador de Realtime Engine (2021) en la versión beta
* &lbrack;Procesando&rbrack; Cambiar entre las dos versiones de procesador en el panel Configuración del visor
* &lbrack;Procesando&rbrack; El procesador del motor en tiempo real (2021) admite las propiedades de translucidez, absorción y dispersión de materiales
* &lbrack;Procesando&rbrack; El procesador del motor en tiempo real (2021) presenta una nueva forma de calcular las sombras a partir de la luz del entorno
* &lbrack;Procesando&rbrack; El procesador del motor en tiempo real (2021) calcula en tiempo real la irradiancia de la luz del entorno
* &lbrack;Panel Configuración del sombreador&rbrack; Nuevo panel Ajustes del sombreado para ajustar parámetros específicos del sombreado de material
* &lbrack;Panel Configuración del sombreador&rbrack; Nuevos parámetros (Escala normal, Escala de height, Nivel de height, Intensidad de emisión, IOR, Intensidad normal de capa y IOR de capa)
* &lbrack;Panel Configuración del sombreador&rbrack; Parámetros específicos para el motor en tiempo real 2021 (dispersión subsuperficial, distancia de dispersión, desplazamiento rojo y dispersión de Rayleigh)
* &lbrack;Panel Configuración del sombreador&rbrack; Los valores de configuración se guardan por recurso
* &lbrack;Panel de configuración del visor&rbrack; Se ha añadido una previsualización de las luces de entorno predeterminadas
* &lbrack;Panel de configuración del visor&rbrack; Se ha añadido una vista previa de las mallas predeterminadas
* &lbrack;Panel de configuración del visor&rbrack; Nuevo parámetro de opacidad del entorno
* &lbrack;Panel de configuración del visor&rbrack; Nuevo parámetro de desenfoque de entorno (específico del procesador de Realtime Engine 2021)
* &lbrack;Localización&rbrack; Nuevas traducciones en alemán y francés
* &lbrack;Contenido&rbrack; Nuevos materiales de inicio predeterminados
* &lbrack;Contenido&rbrack; Nuevas luces de entorno predeterminadas
* &lbrack;Contenido&rbrack; Todos los filtros se han actualizado, limpiado y optimizado
* &lbrack;Contenido&rbrack; El filtro Ajuste se ha dividido en varios filtros
* &lbrack;Contenido&rbrack; Nuevo filtro Brillo/contraste
* &lbrack;Contenido&rbrack; Nuevo filtro Tono/Saturación
* &lbrack;Contenido&rbrack; Nuevo filtro de intensidad
* &lbrack;Contenido&rbrack; Nuevo filtro Enfocar
* &lbrack;Contenido&rbrack; Nuevo ajuste Normal/Height
* &lbrack;Contenido&rbrack; Nuevo filtro de paneles
* &lbrack;Contenido&rbrack; Nuevo filtro de difuminado
* &lbrack;Contenido&rbrack; Nuevo filtro de Tejidos
* &lbrack;Contenido&rbrack; Nuevo filtro de transformación de deformación
* &lbrack;Contenido&rbrack; Nuevo Height para el filtro AO
* &lbrack;Contenido&rbrack; Nuevo Height a filtro normal
* &lbrack;Contenido&rbrack; Sustitución de color: Reemplazar en nuevos canales compatibles (brillo, capa, Anisotropía, etc.)
* &lbrack;Contenido&rbrack; Variación de color: modo manual para seleccionar exactamente los colores que desea cambiar
* &lbrack;Contenido&rbrack; Mosaico - opción para visualizar las costuras cortadas
* &lbrack;Contenido&rbrack; Mosaico - opción para pintar las costuras cortadas para un azulejo perfecto
* &lbrack;Contenido&rbrack; Coincidencia : Opción para añadir un material para que coincida con su color y su rugosidad
* &lbrack;Contenido&rbrack; Coincidencia : ahora funciona en imágenes para que coincidan con el color de otra imagen
* &lbrack;Contenido&rbrack; Luz de ambiente - Nuevo filtro de temperatura de color
* &lbrack;Contenido&rbrack; Luz ambiental - Nuevo filtro de exposición
* &lbrack;Contenido&rbrack; Luz de entorno: nuevo filtro de previsualización de exposición
* &lbrack;Contenido&rbrack; Luz ambiental - Nuevo filtro de Nadir patch
* &lbrack;Contenido&rbrack; Luz ambiental - Nuevo filtro de Nadir extract
* &lbrack;Contenido&rbrack; Luz ambiental: nuevos filtros de luces (esfera, línea, forma, plano)
* &lbrack;Contenido&rbrack; Luz de entorno: nuevo filtro de parche de panorama
* &lbrack;Contenido&rbrack; Luz ambiental - Nuevo filtro Enderezar horizonte
* &lbrack;Contenido&rbrack; Luz de entorno: nuevo filtro de combinación HDR

**Problemas conocidos:**

* &lbrack;Motor en tiempo real 2021&rbrack; Al cambiar el diseño, se bloquea la aplicación
* &lbrack;Motor en tiempo real 2021&rbrack; Cálculo intenso, bloqueo de la aplicación
* &lbrack;Panels&rbrack; MacOS : los paneles no acoplados se encuentran delante de todas las aplicaciones
* &lbrack;Widgets&rbrack; Los widgets Transformar y Posiciones pueden desaparecer. Ocultar y mostrar la capa para que aparezcan.
* &lbrack;Exportar&rbrack; La exportación SBSAR de una luz ambiental pierde la precisión de 32 profundidades de bits
* &lbrack;Panel de recursos&rbrack; Los recursos se pueden resaltar al abrir una carpeta
* &lbrack;Panel Propiedades&rbrack; El restablecimiento de los parámetros no restablece la interfaz de usuario del cuadro combinado
* &lbrack;Localización&rbrack; El cambio de idioma no afecta al panel Proyecto hasta que se vuelva a crear

## Versión 2

### 2.3.2 (2020.3.2) Vermicelli

*(Lanzado: 23 de febrero de 2021)*

**Agregado:**

* &lbrack;Localización&rbrack; Compatibilidad con japonés

**Corregido:**

* &lbrack;Capas&rbrack; Al retocar un material en el filtro de bordado, se pierde la imagen del bordado

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### 2.3.1 (2020.3.1) Vermicelli

*(Lanzado: 17 de diciembre de 2020)*

**Agregado:**

* &lbrack;Motor&rbrack; Actualización del Substance Engine
* &lbrack;Aplicación&rbrack; Variable de entorno para desactivar funciones específicas
* &lbrack;Contenido&rbrack; Reemplazar color: nueva opción de segmentación avanzada
* &lbrack;Contenido&rbrack; Azulejos de piso - nuevos patrones y opciones disponibles
* &lbrack;Contenido&rbrack; Bordado - Completa renovación del filtro
* &lbrack;Contenido&rbrack; Ajuste: nuevo parámetro metálico + corrección de transformación segura de opacidad

**Corregido:**

* &lbrack;Capas&rbrack; No se puede importar dos veces el mismo filtro personalizado
* &lbrack;Capas&rbrack; No se puede utilizar la entrada de imagen con la herramienta Pincel
* &lbrack;Exportar&rbrack; Exportar .jpg en lugar de .jpeg
* &lbrack;UI&rbrack; Actualizar créditos de imagen de pantalla de bienvenida
* &lbrack;UI&rbrack; Corregir separador invisible en los menús
* &lbrack;UI&rbrack; Los botones de opción muestran información sobre herramientas cuando se truncan
* &lbrack;UI&rbrack; Tipografía: Materiales de inicio
* &lbrack;Aplicación&rbrack; Los caracteres UTF-8 en los nombres de recursos no funcionan
* &lbrack;Localización&rbrack; Deshabilitar el estilo de fuente en cursiva para la configuración regional china
* &lbrack;Localización&rbrack; Cadena localizada dividida en 2 líneas
* &lbrack;Localización&rbrack; Ajustar el nombre de la carpeta y reemplazarlo por puntos suspensivos si es demasiado largo
* &lbrack;Localización&rbrack; Formatear números con separador de miles
* &lbrack;Localización&rbrack; Localizar la visualización de fecha y hora
* &lbrack;Localización&rbrack; Localizar el selector de color en Windows
* &lbrack;Contenido&rbrack; Transformar : Con la transformación segura activada, la normal gira correctamente cada 45°
* &lbrack;Contenido&rbrack; Relieve de superficie: Solución del problema de segmentación con el ruido fractal perlin (ruido avanzado)
* &lbrack;Contenido&rbrack; Patrón de pared de ladrillo - entrada de Height en 16 bits
* &lbrack;Contenido&rbrack; Procesamiento de iconos de material: problema de reflejos de Specular
* &lbrack;Contenido&rbrack; Variación de color : No hay cambio de color entre las entradas de color y el resultado
* &lbrack;Contenido&rbrack; Variación de color: actualización de rendimiento

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### 2.3.0 (2020.3.0) Vermicelli

*(Lanzado: 26 de octubre de 2020)*

**Agregado:**

* &lbrack;Imagen a material&rbrack; Compatibilidad con NVIDIA RTX serie 3000
* &lbrack;Imagen a material&rbrack; Nuevos parámetros para controlar los detalles de geometría
* &lbrack;Imagen a material&rbrack; Nuevos parámetros para controlar la rugosidad
* &lbrack;Imagen a material&rbrack; Nuevos parámetros para controlar la intensidad del deleite
* &lbrack;Miniaturas&rbrack; Nuevo generador de miniaturas basado en el procesador PBR de Substance Designer
* &lbrack;Miniaturas&rbrack; Actualizar materiales base y atlas para incrustar su miniatura
* &lbrack;Miniaturas&rbrack; Recupere la miniatura del archivo .sbsar si existe
* &lbrack;Miniaturas&rbrack; Cambiar la calidad de la miniatura en Preferencias
* &lbrack;Motor&rbrack; Actualizado a la versión 8 de Substance Engine
* &lbrack;Localización&rbrack; Localización en chino
* &lbrack;UI&rbrack; Selector de tintas planas experimental
* &lbrack;Contenido&rbrack; Nuevo mapa de entorno - Studio 06
* &lbrack;Contenido&rbrack; Añadir el filtro Generador de Atlas
* &lbrack;Contenido&rbrack; Añadir filtro de Atlas splitter
* &lbrack;Contenido&rbrack; Añadir filtro de encías descartadas
* &lbrack;Contenido&rbrack; Agregar filtro de huellas dactilares
* &lbrack;Contenido&rbrack; Añadir Scratches, filtro
* &lbrack;Contenido&rbrack; Añadir filtro de Relieve de superficie (reemplazar filtro de modulación de height)
* &lbrack;Contenido&rbrack; Añadir filtro de deformación
* &lbrack;Contenido&rbrack; Añadir filtro Invertir
* &lbrack;Contenido&rbrack; Añadir filtro Colorear
* &lbrack;Contenido&rbrack; Añadir filtro Reemplazar color
* &lbrack;Contenido&rbrack; Transformar : añada la posibilidad de desactivar la transformación en un canal específico
* &lbrack;Contenido&rbrack; Transformar : añadir rotación cuando se activa la transformación segura
* &lbrack;Contenido&rbrack; Variación de color : añada una opción de segmentación para elegir cómo distribuir los colores

**Corregido:**

* &lbrack;Capas&rbrack; Actualizar correctamente la interfaz de usuario al realizar varias acciones de deshacer/rehacer
* &lbrack;Capas&rbrack; Evitar bloqueos al realizar varias acciones de deshacer/rehacer
* &lbrack;Capas&rbrack; Bloqueo al utilizar Imagen a material (con tecnología de IA), con registro: ordinal de dispositivo no válido
* &lbrack;Filters&rbrack; Mejorar la detección de tarjetas gráficas NVIDIA para funciones específicas de NVIDIA
* &lbrack;Aplicación&rbrack; Bloqueo al cerrar la aplicación
* &lbrack;Aplicación&rbrack; Corrección de la detección de VRAM en MacOS
* &lbrack;Exportar&rbrack; A veces, faltan algunos ajustes preestablecidos de exportación
* &lbrack;Contenido&rbrack; Efecto Pintura al óleo - Fijar rango de height con alta amplitud de desplazamiento
* &lbrack;Contenido&rbrack; Hacer que el azulejo sea avanzado: no hay color base lavado en la exportación
* &lbrack;Contenido&rbrack; Make It Tile Advanced - Máscara blanca en el color base cuando el AO es demasiado fuerte
* &lbrack;Contenido&rbrack; Ajuste: ahora funciona en imágenes (scan1, ...)

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### 2.2.1 (2020.2.1) Udon

*(Lanzado: 21 de julio de 2020)*

**Agregado:**

* &lbrack;Capas&rbrack; Mensaje de error de In App cuando se agota la memoria de una imagen a material (impulsada por IA)

**Corregido:**

* &lbrack;Capas&rbrack; Imagen a material (con tecnología de IA) no funciona con flujos de trabajo de Specular/brillo
* &lbrack;Capas&rbrack; Se bloquea cuando se queda sin memoria de vídeo al utilizar Imagen a material (con tecnología de IA)
* &lbrack;Capas&rbrack; La caché de disco no se utiliza para la visualización al abrir una pila
* &lbrack;Capas&rbrack; Detección de NVIDIA RTX 8000
* &lbrack;Capas&rbrack; A veces es imposible mover una capa fuera de una entrada de Splatter
* &lbrack;Capas&rbrack; La caché de disco no se utiliza al insertar una pila en una pila
* &lbrack;Capas&rbrack; Algunos usos de canal se calculan aunque no se utilizan
* &lbrack;Capas&rbrack; En ocasiones, se crean salidas en blanco al importar imágenes
* &lbrack;2D View&rbrack; Cambiar a otra capa con el modo Dibujo activado bloquea la panorámica y el zoom
* &lbrack;Contenido&rbrack; Snow: problema de 8 bits en el mapa normal
* &lbrack;Contenido&rbrack; Patrón de pavimento - emisión de 8 bits en el mapa normal
* &lbrack;Contenido&rbrack; Ecualizador: problema de 8 bits en el mapa normal
* &lbrack;Contenido&rbrack; Generador de grava - 8 bits problema en el mapa normal
* &lbrack;Contenido&rbrack; Azulejos de piso - Manejar la opacidad y el specular level
* &lbrack;Contenido&rbrack; Ciclos de fusión aún exportar ajuste preestablecido - invertir mapa normal
* &lbrack;Contenido&rbrack; Corregir el problema con imágenes enormes con Imagen a material (con tecnología de IA)
* &lbrack;Aplicación&rbrack; Bloqueo al elegir &quot;Copia de seguridad y reinicio&quot; en el error de base de datos
* &lbrack;Aplicación&rbrack; Bloqueo al hacer clic rápidamente en el mismo activo
* &lbrack;Aplicación&rbrack; Bloqueos raros al salir
* &lbrack;Aplicación&rbrack; Bloqueo al colocar archivos en la pantalla de bienvenida
* &lbrack;Aplicación&rbrack; Bloqueo al cargar un archivo de entorno dañado
* &lbrack;Aplicación&rbrack; Bloqueo raro al cambiar rápidamente de recurso procesado
* &lbrack;Aplicación&rbrack; Bloqueo al salir mientras se está calculando un activo
* &lbrack;Aplicación&rbrack; Bloqueo raro al inicio en macOS
* &lbrack;Aplicación&rbrack; Interbloqueo al cerrar la aplicación poco después del inicio
* &lbrack;Procesando&rbrack; La vista 3D a veces parpadea
* &lbrack;UI&rbrack; El selector de color y los widgets de semilla aleatoria no están alineados con el resto de los ajustes
* &lbrack;Procesando&rbrack; Se muestra un tiempo de cálculo incorrecto
* &lbrack;Exportar&rbrack; A veces, faltan algunos ajustes preestablecidos de exportación

**Problemas conocidos:**

* El uso de Imagen a material (con IA) en imágenes de alta resolución puede ser lento
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* Los filtros de relleno según el contenido son lentos en alta resolución
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* Imposible guardar dos veces la misma pila de capas de material

### Udon 2.2.0 (2020.2.0)

*(Lanzado: 15 de junio de 2020)*

**Agregado:**

* &lbrack;Crear&rbrack; Nuevo filtro de imagen a material (con tecnología de IA) disponible en Windows y Linux
* &lbrack;Crear&rbrack; Cambiar nombre de mapa de bits de material a imagen a material (B2M)
* &lbrack;Importación de imágenes&rbrack; Ventana emergente Plantilla de creación de material nuevo
* &lbrack;Importación de imágenes&rbrack; Nueva opción &quot;Añadir un material base&quot;
* &lbrack;Importación de imágenes&rbrack; Posibilidad de arrastrar y soltar imágenes adicionales en la plantilla Creación de material
* &lbrack;Importación de imágenes&rbrack; Posibilidad de eliminar imágenes en la plantilla Creación de material
* &lbrack;Importación de imágenes&rbrack; Asignar automáticamente un canal a mapas de bits importados en función del nombre de archivo
* &lbrack;Importación de imágenes&rbrack; Ser capaz de invertir mapas normales
* &lbrack;2D View&rbrack; Introducción de un modo de pintura
* &lbrack;2D View&rbrack; Los azulejos de pintura
* &lbrack;2D View&rbrack; Establecer un valor de escala de grises para el color del pincel
* &lbrack;2D View&rbrack; Panorámica y zoom al pintar
* &lbrack;2D View&rbrack; Método abreviado X para invertir el valor de escala de grises del pincel
* &lbrack;2D View&rbrack; &lbrack; y &brack; métodos abreviados para cambiar el tamaño del pincel
* &lbrack;2D View&rbrack; Ctrl (o Cmd) + Rueda del ratón para cambiar el tamaño del pincel
* &lbrack;2D View&rbrack; Ahora es posible modificar la posición de origen al utilizar el parche de clonación
* &lbrack;Capas&rbrack; Mayús + arrastrar y soltar en atlas de dispersión automática
* &lbrack;Capas&rbrack; Alt + arrastrar y soltar inserta un material como una pegatina
* &lbrack;Capas&rbrack; Exponga fácilmente los transformares matrices de Substance Designer
* &lbrack;Capas&rbrack; La colocación de texturas en una pila no vacía se asigna automáticamente a los canales correctos
* &lbrack;Capas&rbrack; Nuevo tipo de capa: Filtros compuestos
* &lbrack;Parámetros&rbrack; Admitir entradas de cadena de Substance
* &lbrack;UI&rbrack; Se han añadido sombras paralelas para ventanas emergentes y menús
* &lbrack;UI&rbrack; Nuevo widget de color con opciones de clic derecho (borrar, copiar, pegar)
* &lbrack;UI&rbrack; Opción Nuevo widget de imagen con la herramienta de pintura
* &lbrack;UI&rbrack; Pintar sobre una imagen importada en un widget de imagen
* &lbrack;Procesando&rbrack; Nueva posición de cámara predeterminada
* &lbrack;Exportar&rbrack; Los archivos de Substance se exportan para Substance Designer 2020.1.2 (10.1.2)
* &lbrack;Rendimiento&rbrack; Mejor tiempo de inicio de la aplicación
* &lbrack;Rendimiento&rbrack; Mejorar la gestión de tareas asincrónicas
* &lbrack;Rendimiento&rbrack; Mejorar el rendimiento de la pila de capas al añadir, eliminar o mover capas
* &lbrack;Rendimiento&rbrack; De imagen a material (con tecnología de IA) se ejecuta más rápido en las GPU RTX
* &lbrack;Contenido&rbrack; Nuevas mallas: Camiseta de mujer, Camiseta de hombre, Zapato
* &lbrack;Contenido&rbrack; Nuevo modo de fusión: fusión por canal
* &lbrack;Contenido&rbrack; Corrección del height de mezcla de opacidad con 2 nuevos parámetros (posición de height y escala de height)
* &lbrack;Contenido&rbrack; Añadir ajustes de Height en el modo Fusión de Height
* &lbrack;Contenido&rbrack; Opción Usar información de Height en Fusión de máscara personalizada
* &lbrack;Contenido&rbrack; Nueva herramienta de corrección de perspectiva
* &lbrack;Contenido&rbrack; Generador de motivos: añada un parámetro para invertir el motivo
* &lbrack;Contenido&rbrack; Generador de motivos - Añadir un nuevo parámetro Anular detalles de material
* &lbrack;Contenido&rbrack; Nuevo filtro de pegatinas
* &lbrack;Contenido&rbrack; Nuevo filtro de musgo
* &lbrack;Contenido&rbrack; Nuevo filtro de Grietas
* &lbrack;Contenido&rbrack; Nuevo filtro de Validación PBR
* &lbrack;Contenido&rbrack; Nuevo filtro de azulejos de piso
* &lbrack;Contenido&rbrack; Nuevo filtro Costura de tejido
* &lbrack;Contenido&rbrack; Atlas scatter: Añadir entrada de máscara personalizada para activar la opción de pintura
* &lbrack;Contenido&rbrack; Dirt: Añadir entrada de máscara personalizada para activar la opción de pintura
* &lbrack;Contenido&rbrack; Ajuste preestablecido de exportación CLO
* &lbrack;Contenido&rbrack; Ajuste preestablecido de exportación de VStitcher
* &lbrack;Contenido&rbrack; Los ajustes preestablecidos de HDRP de Unity exportan un detailMap

**Corregido:**

* &lbrack;Capas&rbrack; Las imágenes importadas se cargan demasiadas veces
* &lbrack;Capas&rbrack; Bloqueo al crear un parche de clonación en la parte inferior de la pila
* &lbrack;Capas&rbrack; Añadir un material en la parte inferior de la pila hace que sea inestable
* &lbrack;Capas&rbrack; Filtrar tras importar imágenes no funciona correctamente
* &lbrack;Capas&rbrack; el valor workflow_type no se actualiza al cambiar el flujo de trabajo entre proyectos con un filtro personalizado
* &lbrack;Capas&rbrack; Desactivar el botón &quot;Eliminar capa&quot; cuando no hay ninguna capa seleccionada
* &lbrack;Capas&rbrack; Bloqueo al cargar un recurso que contiene un parche de clonación
* &lbrack;Capas&rbrack; El filtro Normal a Height se bloquea en MacOs
* &lbrack;Aplicación&rbrack; Bloqueo al cargar mapas de entorno hacia delante y hacia atrás
* &lbrack;Aplicación&rbrack; Problemas de rendimiento cuando se instala un controlador de la tableta gráfica
* &lbrack;Aplicación&rbrack; La importación de archivos EXR de 32 bits es negra
* &lbrack;Aplicación&rbrack; Se bloquea al cargar y descargar recursos
* &lbrack;Aplicación&rbrack; Bloqueo al cambiar de explorar a crear
* &lbrack;Aplicación&rbrack; La colección de destino al guardar un material no es del proyecto actual
* &lbrack;Aplicación&rbrack; Corregir copia de seguridad y reiniciar
* &lbrack;Importación de imágenes&rbrack; Importar correctamente imágenes en escala de grises
* &lbrack;Contenido&rbrack; Nuevos filtros para el nuevo control de matrices
* &lbrack;Contenido&rbrack; Los filtros personalizados importados son visibles en la barra de acceso rápido
* &lbrack;Contenido&rbrack; Corrección del cambio de color con el filtro avanzado Hacer azulejo
* &lbrack;Rendimiento&rbrack; Abrir un cuadro de diálogo de color es lento y vuelve a calcular la capa actual
* &lbrack;UI&rbrack; Los métodos abreviados de teclado a veces no funcionan
* &lbrack;2D View&rbrack; El Relleno según el contenido necesita un primer clic inútil para funcionar
* &lbrack;Resources&rbrack; En las carpetas de los discos locales se sigue buscando actualizaciones después de quitarlas
* &lbrack;Resources&rbrack; Al eliminar una carpeta vinculada del sistema de archivos, no se elimina
* &lbrack;Exportar&rbrack; Los usos personalizados en los ajustes preestablecidos de exportación personalizados no se exportan
* &lbrack;Exportar&rbrack; No se puede exportar el archivo .sbsar con caracteres especiales en la ruta

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

* &lbrack;Proyecto&rbrack; Exportación e importación de metadatos
* &lbrack;Aplicación&rbrack; Ctrl+S ahora guarda un ajuste preestablecido en Explorar
* &lbrack;Rendimiento&rbrack; Utilice la caché de procesamiento en lugar de volver a calcular los materiales guardados para resoluciones de hasta 2k

**Corregido:**

* &lbrack;UI&rbrack; Indicador de computación fija en la ventana gráfica
* &lbrack;UI&rbrack; La introducción de valores negativos en los reguladores es fija
* &lbrack;UI&rbrack; Cuadros combinados: las flechas del teclado y la barra de desplazamiento ahora funcionan
* &lbrack;UI&rbrack; Mantenga el canal seleccionado al cambiar entre &quot;salidas de material&quot; y &quot;entradas de capa&quot; en la vista 2D
* &lbrack;Capas&rbrack; Se ha corregido el bloqueo al añadir canales personalizados en Material base
* &lbrack;Capas&rbrack; Bloqueo al manipular capas
* &lbrack;Capas&rbrack; Los canales personalizados no se muestran con un material guardado
* &lbrack;Aplicación&rbrack; Se ha corregido un bloqueo raro al importar un activo
* &lbrack;Aplicación&rbrack; Bloqueo al salir
* &lbrack;Aplicación&rbrack; Los cuadros combinados ahora muestran los valores correctos al cambiar los ajustes preestablecidos
* &lbrack;Exportar&rbrack; Ajuste preestablecido de Enscape renombrado a Enscape Revit
* &lbrack;Exportar&rbrack; La importación de un ajuste preestablecido de exportación después de eliminarlo funciona
* &lbrack;Exportar&rbrack; Bloqueo al exportar
* &lbrack;Procesando&rbrack; Se ha corregido el procesamiento cuando el color base está en formato de flotador medio de 16 bits
* &lbrack;Proyecto&rbrack; No se bloquea al importar un paquete dañado
* &lbrack;Proyecto&rbrack; Controle la migración de 2019.1.4 a 2.x.x cuando Create nunca se ha abierto
* &lbrack;Proyecto&rbrack; Solucionar un bloqueo al importar el mismo proyecto dos veces
* &lbrack;Proyecto&rbrack; Solucionar un bloqueo al importar proyectos
* &lbrack;Resources&rbrack; Los filtros personalizados importados en versiones anteriores funcionan
* &lbrack;Resources&rbrack; Los materiales con el mismo nombre ya no se borran entre sí
* &lbrack;Resources&rbrack; Bloqueo al vincular una carpeta local
* &lbrack;Resources&rbrack; Las carpetas creadas por el usuario de materiales de inicio ya no se eliminan después de reiniciar
* &lbrack;Inspire&rbrack; Corregir el área de colocación de material/colección y agregar un mensaje de advertencia si se utiliza un material no guardado

**Problemas conocidos:**

* Los filtros de relleno según el contenido son lentos en alta resolución
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador

### 2.1.0 (2020.1.0) Tiramisu

*(Lanzado: 12 de marzo de 2020)*

**Agregado:**

* &lbrack;Exportar&rbrack; Exportar selección de ajustes preestablecidos para empaquetar texturas para procesadores y motores de juegos
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Unreal Engine 4
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Unity Standard
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Unity HDRP
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Ciclos de fusión/Eve
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Arnold 5
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido al procesador de Corona
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Enscape
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Keyshot 9
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Redshift
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Vray Siguiente
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Lens Studio
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Spark AR Studio
* &lbrack;Exportar&rbrack; Exportar ajuste preestablecido a Brillo de Specular PBR desde Rugosidad metálica PBR
* &lbrack;Exportar&rbrack; Nueva interfaz de exportación
* &lbrack;Exportar&rbrack; Recordar ajustes de exportación
* &lbrack;Exportar&rbrack; Importar y administrar los ajustes preestablecidos de exportación personalizados
* &lbrack;Exportar&rbrack; Eliminar y reemplazar los ajustes preestablecidos de exportación personalizados
* &lbrack;Exportar&rbrack; Cambie el nombre de los ajustes preestablecidos de exportación personalizados
* &lbrack;Exportar&rbrack; Establecer la resolución de exportación predeterminada en la resolución actual
* &lbrack;Exportar&rbrack; Añada la opción de crear una subcarpeta a la ubicación de exportación
* &lbrack;Exportar&rbrack; Mensaje de advertencia antes de reemplazar archivos existentes
* &lbrack;Aplicación&rbrack; Nuevo esquema de numeración de versiones
* &lbrack;Aplicación&rbrack; Abra Crear al iniciar y cambie el orden de los laboratorios
* &lbrack;Pantalla de bienvenida&rbrack; Nuevo banner de bienvenida
* &lbrack;Proyecto&rbrack; Abrir el último proyecto al iniciar
* &lbrack;UI&rbrack; Nuevo estilo de cuadro combinado
* &lbrack;2D view&rbrack; Método abreviado F para enfocar en la vista 2D
* &lbrack;Filters&rbrack; Se ha agregado la compatibilidad con la etiqueta alchemist::parameterVisibility en los gráficos de Substance
* &lbrack;Filters&rbrack; Realizar un ajuste global para administrar la visibilidad de los parámetros en función del flujo de trabajo
* &lbrack;Resources&rbrack; Nueva opción de línea de comandos para configurar recursos y carpetas vinculadas con un archivo de configuración
* &lbrack;Comprobador de versiones&rbrack; Configuración de la comprobación de la versión
* &lbrack;Contenido&rbrack; Nuevos materiales de arranque
* &lbrack;Contenido&rbrack; Bitmap para material: añada la posibilidad de definir el canal metálico (importación de imágenes uniforme y personalizada, selección de color).
* &lbrack;Contenido&rbrack; Ajuste : añada la compatibilidad con el flujo de trabajo de specular/brillo de PBR
* &lbrack;Contenido&rbrack; Atlas scatter - Nuevos parámetros

**Corregido:**

* &lbrack;Proyecto&rbrack; Bloqueo al importar el mismo proyecto dos veces
* &lbrack;Proyecto&rbrack; Se ha corregido el bloqueo al importar y abrir proyectos varias veces
* &lbrack;Aplicación&rbrack; Bloqueo al cargar un material sin nombre
* &lbrack;Aplicación&rbrack; Reconocer los archivos que faltan al volver a importarlos
* &lbrack;Aplicación&rbrack; Solucionar bloqueo aleatorio al apagar
* &lbrack;Aplicación&rbrack; Se ha corregido un raro bloqueo al descargar un material en Crear
* &lbrack;Aplicación&rbrack; Se ha corregido un bloqueo aleatorio al utilizar controles de IU
* &lbrack;Aplicación&rbrack; Se ha corregido la exportación de archivos de registro al escritorio en Windows 10
* &lbrack;UI&rbrack; El panel Exportar tiene un tamaño incorrecto al abrirlo en Crear
* &lbrack;UI&rbrack; Abrir proyecto con un solo clic
* &lbrack;UI&rbrack; Definición correcta de los valores mínimo y máximo del regulador
* &lbrack;UI&rbrack; Mostrar la etiqueta de los usos del canal en lugar de los ID
* &lbrack;UI&rbrack; Al hacer clic en un material, siempre se abre o cierra el panel de ajustes
* &lbrack;UI&rbrack; Corregir colores de capas ocultas
* &lbrack;UI&rbrack; Mejoras en los botones de pantalla de bienvenida
* &lbrack;Capas&rbrack; Menos cálculos innecesarios
* &lbrack;Capas&rbrack; Se bloquea al utilizar el parche de clonación
* &lbrack;Capas&rbrack; La selección de una capa de importación de imágenes ya no activa un equipo
* &lbrack;Capas&rbrack; Las capas Clonar parche y Relleno según el contenido ya no se vuelven a calcular cuando se seleccionan
* &lbrack;Configuración del canal&rbrack; La activación o desactivación de usos ahora activa un procesamiento
* &lbrack;Resources&rbrack; Evitar el bloqueo al hacer clic de forma masiva en una pila de la biblioteca
* &lbrack;Resources&rbrack; Se produce un impacto en el rendimiento al volver a añadir una carpeta vinculada previamente añadida
* &lbrack;Resources&rbrack; Se ha corregido un bloqueo al intentar abrir un archivo .sbsar eliminado.
* &lbrack;Rendimiento&rbrack; Evite cargar materiales para acceder a sus parámetros
* &lbrack;Rendimiento&rbrack; Realizar copia de seguridad de activos solo cuando se utilizan en un proyecto o en un material creado
* &lbrack;Exportar&rbrack; En ocasiones, los materiales corregidos de la cola de exportación se omiten o se exportan con parámetros incorrectos
* &lbrack;2D View&rbrack; Panorámica y zoom restaurados
* &lbrack;Contenido&rbrack; Parquet Patrón tiene en cuenta el canal de Oclusión ambiental
* &lbrack;Contenido&rbrack; Paint: muestra la entrada de máscara al activar la máscara personalizada
* &lbrack;Contenido&rbrack; Patrón de Stonewall - Eliminar posibles efectos de bandas en el mapa normal
* &lbrack;Contenido&rbrack; Modulación de height: Corregir entradas de color de base doble en la vista 2D

**Problemas conocidos:**

* Los filtros de relleno según el contenido son lentos en alta resolución
* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador

## Versión 1

### 1.1.4 (2019.1.4) Sésamo

*(Lanzado: 30 de enero de 2020)*

**Agregado:**

* &lbrack;Resources&rbrack; Mensaje de confirmación al borrar una carpeta de recursos

**Corregido:**

* &lbrack;Capas&rbrack; Mover capas a dos o más capas superiores o inferiores
* &lbrack;Crear&rbrack; Asignación de suficiente presupuesto de VRAM para tener un buen rendimiento

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

* &lbrack;Flujo de trabajo&rbrack; Compatibilidad con varios flujos de trabajo
* &lbrack;Flujo de trabajo&rbrack; Compatibilidad con el flujo de trabajo Brillo de Specular PBR
* &lbrack;Flujo de trabajo&rbrack; Nuevo panel Configuración de canal
* &lbrack;Flujo de trabajo&rbrack; Selección de flujo de trabajo en la creación de proyectos
* &lbrack;Configuración de canal&rbrack; Activar o desactivar cálculo de canal específico
* &lbrack;Configuración de canal&rbrack; Mostrar la lista de canales personalizados disponibles en el material actual
* &lbrack;Configuración de canal&rbrack; Cálculo automático de canales personalizados cuando sea necesario
* &lbrack;Configuración de canal&rbrack; Forzar/Bloquear el cálculo de canales personalizados
* &lbrack;Capas&rbrack; Nueva interfaz de usuario del marcador de posición de entrada de material en los filtros de Atlas scatter y salpicaduras
* &lbrack;Capas&rbrack; El parámetro de entrada de imagen de un filtro se puede alimentar debajo de las capas
* &lbrack;Capas&rbrack; Mostrar una notificación cuando algunas capas no estén actualizadas
* &lbrack;Capas&rbrack; Posibilidad de actualizar a la última versión de las capas obsoletas a través de la notificación
* &lbrack;Proyecto&rbrack; Nuevos campos de metadatos en la creación de proyectos
* &lbrack;Inspire&rbrack; Las variaciones generadas son específicas de un proyecto
* &lbrack;2D View&rbrack; Cambiar entre las entradas de capa, las salidas de capa y las salidas de material
* &lbrack;Pantalla de bienvenida&rbrack; Opción Agregar proyecto de importación (.alch)
* &lbrack;Preferencias&rbrack; Nueva ventana Preferencias para definir la configuración de privacidad de análisis y ubicación de la caché
* &lbrack;UI&rbrack; Nuevos botones de IU
* &lbrack;Rendimiento&rbrack; Mejora global del sistema de paralelización
* &lbrack;Rendimiento&rbrack; Optimización del número de equipos de materiales
* &lbrack;Motor&rbrack; Actualización del Substance Engine
* &lbrack;Framework&rbrack; Actualización a Qt 5.13
* &lbrack;MacOS&rbrack; Mejoras globales de la compatibilidad con macOS Catalina
* &lbrack;Contenido&rbrack; Filtro de ajuste: intensidad normal y parámetros de inversión

**Corregido:**

* &lbrack;Capas&rbrack; Anular la configuración del parámetro Entrada de imagen al eliminar la capa
* &lbrack;Capas&rbrack; Corrección de un bloqueo al añadir una capa de parche de clonación
* &lbrack;Capas&rbrack; Solucionar algunos bloqueos al mezclar capas y apilar materiales en otros materiales de pila de capas
* &lbrack;Exportar&rbrack; Ahora se respeta la selección de canales para la exportación
* &lbrack;Resources&rbrack; No se bloquea al navegar por el panel Recursos
* &lbrack;Resources&rbrack; Solucionar bloqueo al importar archivos de Substance dañados
* &lbrack;Resources&rbrack; Reducir el número de bloqueos al cargar carpetas grandes
* &lbrack;Miniatura&rbrack; El cálculo de miniaturas no bloquea la interfaz
* &lbrack;Importación de imágenes&rbrack; Uniformización del tipo de imagen compatible en toda la aplicación
* &lbrack;Preset&rbrack; Guardar la descripción al crear un ajuste preestablecido desde una SBSAR
* &lbrack;Inspire&rbrack; Corrección de arrastrar y soltar imágenes
* &lbrack;Aplicación&rbrack; Solucionar bloqueos al salir
* &lbrack;Aplicación&rbrack; Solucionar bloqueos al salir al exportar materiales
* &lbrack;UI&rbrack; Correcciones y mejoras
* &lbrack;UI&rbrack; Cambiar el nombre del activo temporal a &quot;material no guardado&quot;
* &lbrack;Contenido&rbrack; Actualización global y limpieza de todos los filtros

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

* &lbrack;Capas&rbrack; Se puede acceder a las opciones Guardar y Guardar como desde la interfaz de la barra de herramientas de la pila de capas
* &lbrack;Resources&rbrack; Limpieza de la ruta de exploración en el panel Recursos para desplazarse por las carpetas
* &lbrack;Resources&rbrack; Botón Mantener atrás pulsado para acceder a todas las carpetas superiores
* &lbrack;Resources&rbrack; Opción Añadir recarga de materiales importados para actualizarlos a la última versión
* &lbrack;Capas&rbrack; Posibilidad de cambiar la imagen en la capa de importación de imágenes
* &lbrack;Capas&rbrack; Posibilidad de definir una imagen como canal (color base, normal, height,...) en la capa de importación de imágenes
* &lbrack;Contenido&rbrack; Nuevo filtro de Atlas scatter para la dispersión de nuevos elementos de atlas desde Substance Source
* &lbrack;Contenido&rbrack; Nuevo filtro Efecto Pintura al óleo
* &lbrack;Contenido&rbrack; Nuevo filtro Generación de canales para generar height, oclusión de ambiente y rugosidad a partir de mapas normales y de color base

**Corregido:**

* &lbrack;UI&rbrack; Reactivar información sobre herramientas en la barra de herramientas de la pila Capas
* &lbrack;UI&rbrack; Solucionar problema al escribir dos decimales en un valor del regulador
* &lbrack;Rendimiento&rbrack; Solucionar bloqueo al cambiar rápidamente de un material a otro
* &lbrack;Exportar&rbrack; El cambio a otro material antes del final de una exportación ya no se bloquea
* &lbrack;Resources&rbrack; El menú contextual se muestra en la parte superior del material al hacer clic con el botón derecho en él
* &lbrack;Capas&rbrack; El vínculo &quot;Haga clic aquí&quot; funciona cuando la pila de capas está vacía
* &lbrack;Ajustes preestablecidos&rbrack; El botón Quitar guardar del panel de ajustes cuando se trata de un material creado en Alchemist
* &lbrack;Tweak&rbrack; Mensaje de información que se muestra cuando es un material creado en Alchemist
* &lbrack;Viewport&rbrack; El valor predeterminado de la textura del Specular level se corrige a 0,04
* &lbrack;Menú Archivo&rbrack; Opción Corregir y cambiar nombre Guardar y guardar como
* &lbrack;Motor&rbrack; Actualice la versión del motor de Substance para evitar el bloqueo de algunos archivos SBSAR durante la importación.
* &lbrack;Contenido&rbrack; El filtro de mosaico funciona en el canal de oclusión ambiente
* &lbrack;Contenido&rbrack; El filtro Recortar funciona en el canal de oclusión de ambiente
* &lbrack;Contenido&rbrack; Filtro de agua modifica el mapa de height
* &lbrack;Contenido&rbrack; Mosaico correcto del material superior en el modo de fusión de opacidad
* &lbrack;Contenido&rbrack; El height del material superior se conserva en el modo de fusión de opacidad
* &lbrack;Contenido&rbrack; Posibilidad de añadir una máscara personalizada, un motivo personalizado o un mapa de escala en el filtro de perforación
* &lbrack;Contenido&rbrack; Height El filtro de modulación fuerza el height y los mapas normales en 16 bits
* &lbrack;Contenido&rbrack; El filtro de ajuste fuerza el height y los mapas normales en 16 bits

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

* &lbrack;Fusionar&rbrack; Nuevo modo de fusión de opacidad
* &lbrack;Motor&rbrack; Nueva versión de Substance Engine

**Corregido:**

* &lbrack;Capas&rbrack; Solucionar el bloqueo al eliminar una capa que aún se está calculando
* &lbrack;Capas&rbrack; Solucionar el bloqueo al eliminar la capa inferior
* &lbrack;Capas&rbrack; Solucionar bloqueo mientras el nombre del material contiene caracteres especiales
* &lbrack;Capas&rbrack; Detener el cálculo de todos los filtros que utilizan un widget
* &lbrack;Capas&rbrack; Evite el bloqueo al utilizar los filtros Clonar parche y Relleno según el contenido
* &lbrack;Capas&rbrack; Solucionar el bloqueo al arrastrar y soltar un filtro en ranuras de entrada de salpicaduras
* &lbrack;Resources&rbrack; Solucionar el bloqueo al vincular carpetas locales o importar recursos en Substance Alchemist
* &lbrack;Colección&rbrack; Solucionar el bloqueo al cambiar rápidamente de un material a otro
* &lbrack;UI&rbrack; Se ha solucionado el bloqueo si el valor es nulo o no es válido en los reguladores de mosaico y desplazamiento de la ventana gráfica.
* &lbrack;Inspire&rbrack; Solucionar el bloqueo al acceder a la pestaña Inspirar
* &lbrack;Inspire&rbrack; Solucionar el bloqueo al inspirar en un material de pila de capas recién guardado
* &lbrack;Rendimiento&rbrack; Los materiales y filtros Substance pesados (segmentación) calculan más rápido
* &lbrack;Ayuda&rbrack; Corregir archivo de registro de exportación
* &lbrack;Contenido&rbrack; El filtro aleatorio funciona en todos los canales
* &lbrack;Contenido&rbrack; El flujo de trabajo multiangular tiene en cuenta todas las digitalizaciones
* &lbrack;Contenido&rbrack; Mezcla correcta de AO
* &lbrack;Contenido&rbrack; Fusión de curvatura fusión correcta
* &lbrack;Contenido&rbrack; Fusión correcta de fusión de ID de color
* &lbrack;Contenido&rbrack; Fusión de máscara personalizada fusión correcta
* &lbrack;Contenido&rbrack; Corregir filtro de ajuste para modificación de rugosidad
* &lbrack;Contenido&rbrack; Corregir filtro de Material base para la carga de canales normales personalizados
* &lbrack;Contenido&rbrack; Corregir el patrón de importación personalizado del filtro Relieve

**Problemas conocidos:**

* No se recomienda el uso de varios encantadores en un solo material
* Delighter se bloquea con controladores NVIDIA antiguos (menos de 400.x)
* La coma o el punto se pueden ignorar al escribir un valor específico en un regulador
* El filtro Normal a Height puede bloquearse en MacOS

### 1.1.0 (2019.1.0) Sésamo

*(Lanzado: 04 de noviembre de 2019)*

**Agregado:**

* &lbrack;Proyecto&rbrack; Creación de un proyecto
* &lbrack;Proyecto&rbrack; Introducción al formato de archivo .alch que contiene los datos del proyecto
* &lbrack;Proyecto&rbrack; Exportar un proyecto .alch que contenga las colecciones y sus materiales
* &lbrack;Proyecto&rbrack; Importar un proyecto .alch
* &lbrack;Proyecto&rbrack; Abrir proyectos recientes
* &lbrack;Pantalla de bienvenida&rbrack; Se muestra una pantalla de bienvenida al iniciar
* &lbrack;Pantalla de bienvenida&rbrack; Crear un proyecto desde la pantalla de bienvenida
* &lbrack;Pantalla de bienvenida&rbrack; Acceda a la lista de todos sus proyectos en la pantalla de bienvenida
* &lbrack;Pantalla de bienvenida&rbrack; Enlaces rápidos para acceder a la documentación, la información acerca de la gestión de licencias y ventanas emergentes
* &lbrack;Menú Archivo&rbrack; Integración de un menú de archivo
* &lbrack;Menú Archivo&rbrack; Acceda a los comandos del proyecto desde la pestaña Archivo y guarde la pila de capas
* &lbrack;Menú Archivo&rbrack; Acceder a los comandos de deshacer y rehacer desde la pestaña Editar
* &lbrack;Menú Archivo&rbrack; El menú Ayuda anterior se trasladó al menú Archivo de la ficha Ayuda
* &lbrack;Capas&rbrack; Nueva arquitectura de la pila de capas
* &lbrack;Capas&rbrack; Nueva interfaz de usuario de la pila de capas
* &lbrack;Capas&rbrack; Seleccione el modo de fusión directamente en la barra de herramientas
* &lbrack;Capas&rbrack; Acceda por separado a los parámetros de mezcla y a los parámetros de material
* &lbrack;Capas&rbrack; Añade materiales directamente en entradas dedicadas del filtro Salpicadura en la pila de capas
* &lbrack;Capas&rbrack; Cambiar el orden de digitalización directamente en la capa de importación de imágenes
* &lbrack;Viewport&rbrack; Control del campo de visión de la cámara
* &lbrack;Viewport&rbrack; Posibilidad de cambiar entre cámara ortográfica o de perspectiva
* &lbrack;Viewport&rbrack; Mostrar la información de resolución y profundidad de bits de cada canal
* &lbrack;Resources&rbrack; Materiales base se abre de forma predeterminada
* &lbrack;Caché&rbrack; Localizar la carpeta de caché de miniaturas
* &lbrack;Caché&rbrack; Localizar la carpeta de caché de procesamiento
* &lbrack;Panels&rbrack; El panel Ajustes de material está oculto temporalmente
* &lbrack;Flujo de trabajo&rbrack; Specular/Brillo desactivado temporalmente
* &lbrack;MacOS&rbrack; Notarización de la versión del sistema operativo Catalina
* &lbrack;Contenido&rbrack; Nueva versión del filtro Delighter
* &lbrack;Contenido&rbrack; Nuevo filtro Relleno según el contenido de imagen
* &lbrack;Contenido&rbrack; Nuevo filtro Relleno según el contenido de material
* &lbrack;Contenido&rbrack; El filtro Transformar tiene una opción de transformación segura

**Corregido:**

* Todos los errores anteriores relacionados con Create no son válidos hoy con la nueva versión de la interfaz de usuario y la arquitectura
* La información sobre herramientas no oculta los iconos de la barra superior (3D, 2D, 2D/3D)
* &lbrack;Contenido&rbrack; Splatter filter acepta Atlas con mapa de height completo
* &lbrack;Contenido&rbrack; El filtro de transformación funciona en imágenes (scan1, scan2,...)

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

* &lbrack;Crear&rbrack; Algunos filtros se enumeraron en el descriptor de acceso rápido, pero no en el panel de filtros
* &lbrack;MacOS&rbrack; Se han solucionado algunos bloqueos al salir

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

* &lbrack;Resources&rbrack; Conectar y reflejar las carpetas de materiales en los discos locales
* &lbrack;Resources&rbrack; Examine las carpetas de materiales y sus subcarpetas
* &lbrack;Resources&rbrack; Separe el panel de recursos materiales en una ventana independiente para ver los recursos en pantalla completa
* &lbrack;Resources&rbrack; Nuevo diseño del panel Recursos para admitir la navegación por carpetas y subcarpetas
* &lbrack;Resources&rbrack; Utilizar la ruta de exploración para desplazarse por las carpetas
* &lbrack;Resources&rbrack; Fuerce la sincronización de la carpeta local con la opción Sincronizar accesible haciendo clic con el botón derecho
* &lbrack;Resources&rbrack; Desconectar la carpeta local con la opción Desconectar disponible haciendo clic con el botón derecho
* &lbrack;Administrar&rbrack; Visualización de etiquetas incrustadas de archivos de Substance
* &lbrack;Administrar&rbrack; Añade, edita y elimina etiquetas de tus materiales
* &lbrack;Administrar&rbrack; Califica tus materiales
* &lbrack;Capas&rbrack; Salida de panorama de soporte
* &lbrack;Capas&rbrack; Puede eliminar las entradas de imagen en la capa de importación de imágenes
* &lbrack;Capas&rbrack; Selección automática de la nueva capa añadida
* &lbrack;Capas&rbrack; Selección automática de la capa inferior después de eliminar una capa
* &lbrack;UX&rbrack; Mantener la visibilidad de los paneles izquierdos al cambiar a otro laboratorio
* &lbrack;UX&rbrack; No cree una capa base ni abra la ventana emergente de flujo de trabajo de material al importar imágenes en una pila de capas no vacías
* &lbrack;UI&rbrack; Nuevo estilo de TextField
* &lbrack;UI&rbrack; Nuevo estilo de SearchBox
* &lbrack;UI&rbrack; Nuevo estilo de encabezado de panel
* &lbrack;UI&rbrack; Nuevo estilo de indicador Ocupado
* &lbrack;UI&rbrack; Nuevo estilo de fondo de pila de capas
* &lbrack;UI&rbrack; Usar fuente de Adobe Clean
* &lbrack;UI&rbrack; Eliminar marcador de posición del icono de cuentagotas del parámetro de entrada de color
* &lbrack;Rendimiento&rbrack; Optimización del indicador Ocupado
* &lbrack;Contenido&rbrack; Nuevo filtro Generador de motivos
* &lbrack;Contenido&rbrack; Nuevo filtro de desenfoque

**Corregido:**

* &lbrack;Inspire&rbrack; Solucionar bloqueo al utilizar más de 10 colores
* &lbrack;2D View&rbrack; Corrección de la barra de desplazamiento en la lista de canales de la vista 2D
* &lbrack;Visor&rbrack; Solucionar bloqueo al importar un mapa de entorno que no es de alimentación 2
* &lbrack;Contenido&rbrack; Corrección en la importación de PNG para el patrón personalizado de filtros de relieve y perforación
* &lbrack;Exportar&rbrack; Corrección de la exportación normal y de height de 16 bits por canal
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

* &lbrack;Filters&rbrack; Acceda rápidamente a los filtros pulsando la barra espaciadora
* &lbrack;Filters&rbrack; Nuevo panel dedicado para administrar, examinar e importar sus filtros
* &lbrack;Metadatos&rbrack; Haga clic con el botón derecho en un material para ver sus metadatos
* &lbrack;Metadatos&rbrack; Haga clic con el botón derecho en un material para ver su ubicación en el disco
* &lbrack;Reguladores&rbrack; Animación de los controles deslizantes al pasar el puntero sobre ellos pulsando Ctrl
* &lbrack;Reguladores&rbrack; Detenga y reinicie la animación de los reguladores pulsando P
* &lbrack;Exportar&rbrack; La exportación SBSAR sigue las directrices del Substance Source
* &lbrack;Licencia&rbrack; Activar Substance Alchemist mediante una variable de entorno
* &lbrack;UX&rbrack; El cuadro de diálogo Archivo recuerda la última ruta de archivo seleccionada
* &lbrack;UX&rbrack; El cuadro de diálogo Carpeta recuerda la última ruta de carpeta seleccionada
* &lbrack;UI&rbrack; Actualizar IU del panel Recursos
* &lbrack;UI&rbrack; Actualizar IU de la barra de búsqueda
* &lbrack;UI&rbrack; Se actualiza el icono Crear nuevo material
* &lbrack;Ayuda&rbrack; Las direcciones URL se actualizan al dominio substance3d.com
* &lbrack;Malla&rbrack; Ya hay disponible una malla de tela
* &lbrack;Contenido&rbrack; Nuevo filtro de corrosión
* &lbrack;Contenido&rbrack; Nuevo filtro de oxidación
* &lbrack;Contenido&rbrack; Nuevo filtro de musgo
* &lbrack;Contenido&rbrack; Nuevo filtro de Dust
* &lbrack;Contenido&rbrack; Nuevo filtro de patrón de pared metálica
* &lbrack;Contenido&rbrack; Nuevo filtro de patrón de Stonewall
* &lbrack;Contenido&rbrack; Nuevo filtro de acabado de madera
* &lbrack;Contenido&rbrack; Nuevo filtro de acabado metálico
* &lbrack;Contenido&rbrack; Nuevo filtro de Snow
* &lbrack;Contenido&rbrack; Nuevo filtro aleatorio
* &lbrack;Contenido&rbrack; Ahora puede importar sus texturas directamente en el filtro de Material base

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

* &lbrack;Motor&rbrack; La actualización de Substance Engine será compatible con la última versión de Substance Designer
* &lbrack;Licencia&rbrack; Actualizar la carpeta de licencias para las primeras instalaciones
* &lbrack;Capas&rbrack; Vuelva a cargar en cualquier momento la pila de capas para actualizar los filtros personalizados

**Corregido:**

* &lbrack;Compatibilidad de datos&rbrack; Corrección preventiva para limitar la corrupción de datos en el momento de la actualización

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

* &lbrack;Metadatos&rbrack; Ver y rellenar metadatos de materiales en una pestaña dedicada
* &lbrack;Colección&rbrack; Crear una colección directamente desde los resultados de búsqueda
* &lbrack;Publicación de medios&rbrack; Exportación de un tablero de una colección
* &lbrack;UX&rbrack; Deshacer un cambio de ajuste o importación de imágenes pulsando Ctrl+Z
* &lbrack;UX&rbrack; Rehacer un cambio de ajuste o importación de imágenes pulsando Ctrl+Mayús+Z
* &lbrack;UI&rbrack; Nuevos iconos con un nuevo estilo
* &lbrack;Rendimiento&rbrack; Nuevo Administrador de sesiones para gestionar mejor el cambio de pestañas
* &lbrack;Rendimiento&rbrack; Apertura más rápida de la capa de importación de imágenes
* &lbrack;Contenido&rbrack; Nuevo material genérico de metal
* &lbrack;Contenido&rbrack; Nuevo material de Óxido
* &lbrack;Contenido&rbrack; Nuevo material genérico de piedra
* &lbrack;Contenido&rbrack; Actualización del filtro de relieve
* &lbrack;Contenido&rbrack; Actualización del filtro de bordado
* &lbrack;Contenido&rbrack; Actualización del filtro de pintura
* &lbrack;Contenido&rbrack; Actualización del filtro Delighter

**Corregido:**

* &lbrack;Contenido&rbrack; El filtro de agua funciona en el flujo de trabajo Specular/Brillo
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

* &lbrack;Pila&rbrack; Bloqueo al eliminar una capa de salpicaduras
* &lbrack;Datos&rbrack; La base de datos de activos se daña cuando la aplicación se bloquea
* &lbrack;Datos&rbrack; El Substance Alchemist no se puede iniciar si la base de datos de recursos está dañada
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
* &lbrack;UI&rbrack; Herramienta Clonar nueva interfaz de usuario con visualización del tamaño del pincel
* &lbrack;UI&rbrack; Selección y eliminación de etapas ocultas
* &lbrack;UI&rbrack; Nueva interfaz de usuario de TextField
* &lbrack;Ayuda&rbrack; Acceder a los sitios web de Substance Source, Substances shares y academias de Substance
* &lbrack;Contenido&rbrack; Nuevos materiales predeterminados con generadores y atlas
* &lbrack;Contenido&rbrack; Actualización de mapa de bits a material
* &lbrack;Contenido&rbrack; Actualización de dirt
* &lbrack;Contenido&rbrack; Actualización de óxido
* &lbrack;Contenido&rbrack; Nuevo filtro de relieve
* &lbrack;Contenido&rbrack; Nuevo filtro de bordado
* &lbrack;Contenido&rbrack; Nuevo Filtro erosionado
* &lbrack;Contenido&rbrack; Nuevo generador de grava
* &lbrack;Contenido&rbrack; Nuevo filtro de pintura
* &lbrack;Contenido&rbrack; Nuevo filtro de motivo de parquet
* &lbrack;Contenido&rbrack; Nuevo filtro de motivo de pavimento
* &lbrack;Contenido&rbrack; Nuevo filtro de perforación
* &lbrack;Contenido&rbrack; Nuevo filtro de salpicaduras
* &lbrack;Contenido&rbrack; Nuevo filtro de desgaste textil
* &lbrack;Contenido&rbrack; Nuevo filtro Transformar

**Corregido:**

* &lbrack;Viewport&rbrack; Malla de esfera con mosaico x2 en X
* &lbrack;Viewport&rbrack; Bloqueo al cargar su propio entorno
* &lbrack;Viewport&rbrack; Los mapas de entorno están utilizando ahora el valor de exposición también
* &lbrack;Viewport&rbrack; El método abreviado F no restablece el ángulo de la cámara
* &lbrack;Exportar&rbrack; La exportación de SBS funciona con la última versión de Substance Designer 2018.3.3
* &lbrack;Exportar&rbrack; La exportación SBSAR respeta las mismas directrices que los materiales de Substance Source
* &lbrack;UI&rbrack; Las barras de desplazamiento se pueden arrastrar
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

* &lbrack;Pila de capas&rbrack; Reordenación de capas
* &lbrack;Pila de capas&rbrack; Eliminación de una capa oculta
* &lbrack;Pila de capas&rbrack; Importe un material directamente en la posición que desee
* &lbrack;Pila de capas&rbrack; Entrada de material como un nuevo tipo de parámetro de filtro
* &lbrack;Rendimiento&rbrack; El presupuesto del Substance Engine es dinámico para un mejor rendimiento
* &lbrack;Rendimiento&rbrack; Rendimiento de OpenGL mejorado especialmente en MacOS
* &lbrack;Datos&rbrack; Actualización de datos más rápida después del lanzamiento de una nueva versión
* &lbrack;Contenido&rbrack; AI Delighter disponible en Windows 7 y Windows 8
* &lbrack;Contenido&rbrack; AI Delighter disponible en la GPU RTX

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

* &lbrack;Exportar&rbrack; exportación del archivo de Substance (sbsar) de su colección
* &lbrack;Exportar&rbrack; exportación de archivos de Substance (sbs) de su colección
* &lbrack;Exportar&rbrack; Cola de exportación visible en el panel Exportar
* &lbrack;Exportar&rbrack; Asignar un nombre a la colección o material antes de la exportación
* &lbrack;Datos&rbrack; Guardar como material pulsando Ctrl+Mayús+S
* &lbrack;Datos&rbrack; Guarde el material pulsando Ctrl+S
* &lbrack;Datos&rbrack; Las colecciones y los materiales son compatibles entre versiones
* &lbrack;Datos&rbrack; Actualizar la pila de capas de material con filtros actualizados
* &lbrack;Datos&rbrack; Recarga en caliente de filtros personalizados importados
* &lbrack;UI&rbrack; Retroalimentación visual en la ventana gráfica mientras se está computando
* &lbrack;UI&rbrack; Nuevo estilo de botón
* &lbrack;UI&rbrack; La ventana emergente Guardar muestra el nombre de la colección activa
* &lbrack;UI&rbrack; Modificación de imágenes de origen de una capa de importación de imágenes
* &lbrack;Contenido&rbrack; Ahora se admiten usos personalizados
* &lbrack;Contenido&rbrack; Se admiten más formatos de imagen en los parámetros de entrada de imagen.
* &lbrack;Contenido&rbrack; Nuevo filtro de mosaico llamado Make It Tile Advanced
* &lbrack;Contenido&rbrack; Actualización del filtro de agua

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

* &lbrack;Exportar&rbrack; Nueva ventana emergente de exportación
* &lbrack;Exportar&rbrack; Exportar una colección completa
* &lbrack;Exportar&rbrack; Exportar mapas de bits en el formato deseado
* &lbrack;Exportar&rbrack; Exporte mapas de bits con la resolución que desee
* &lbrack;Exportar&rbrack; Exporte solo los canales que desee
* &lbrack;Exportar&rbrack; Previsualizar el tamaño estimado de la exportación
* &lbrack;Exportar&rbrack; Previsualice el tamaño disponible en el disco antes de exportar
* &lbrack;UX&rbrack; Acciones en una colección accesibles haciendo clic con el botón derecho
* &lbrack;UX&rbrack; Permitir la desconfiguración de una imagen o un recurso en Inspire
* &lbrack;UX&rbrack; Substance Alchemist se inicia maximizado
* &lbrack;Assets&rbrack; Nueva forma de guardar tus materiales para mantenerlos persistentes con las próximas versiones
* &lbrack;Ayuda&rbrack; Acceso a la documentación en línea a través del menú de ayuda
* &lbrack;Rendimiento&rbrack; Variaciones de color más rápidas en materiales complejos creados con Substance Alchemist
* &lbrack;Rendimiento&rbrack; Reducir pérdidas de memoria al cambiar de laboratorio
* &lbrack;Contenido&rbrack; Comprobador de escala para diagnosticar el tamaño físico del material
* &lbrack;Contenido&rbrack; Actualizar Italien Venecia Mosaico material de baldosas
* &lbrack;Contenido&rbrack; Actualizar la salpicadura de musgo

**Corregido:**

* Se acabó el nombre predeterminado al guardar un material
* Los parámetros de filtros se pierden después de guardar un material y volver a abrir el Substance Alchemist
* &lbrack;Contenido&rbrack; Corrección desde la lógica inferior y superior para la fusión de AO y curvatura

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
* &lbrack;Registro&rbrack; Exportar archivo de registro a través del menú Ayuda
* &lbrack;UI&rbrack;Nuevo estilo de controles deslizantes
* &lbrack;UI&rbrack;Se han combinado los paneles Ajustes preestablecidos y Retoque
* &lbrack;UI&rbrack;Nuevo estilo de miniaturas
* Configuración de desplazamiento, Mosaico y Sombras accesible directamente en la ventana gráfica
* &lbrack;Contenido&rbrack; Nuevos materiales predeterminados
* &lbrack;Contenido&rbrack; Actualización de Moss Splatter
* &lbrack;Framework&rbrack; Actualizar Substance Engine Framework

**Corregido:**

* Se ha solucionado la eliminación de la pila de capas al cambiar de laboratorio
* Los valores de tiempo de carga mostrados en la ventana gráfica son correctos
* Los canales predeterminados del flujo de trabajo de material se inicializan correctamente
* Desactivar importación de malla personalizada
* Exportación de mapa de bits
* &lbrack;MacOS&rbrack; El Substance Alchemist de cierre puede necesitar un &quot;Forzar el cierre&quot;

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
* &lbrack;MacOS&rbrack; El Substance Alchemist se puede configurar en pantalla completa
* &lbrack;Filtro&rbrack; Importar máscara personalizada para administrar la fusión entre dos materiales
* &lbrack;Filtro&rbrack; Escala de control de musgo
* &lbrack;Filtro&rbrack; Actualización del parche de clonación

**Corregido:**

* Añadir una imagen en una entrada de imagen en la lista de parámetros actualiza las salidas
* Importar El filtro personalizado no agrega una Oclusión ambiental negra ni una opacidad negra

**Problemas conocidos:**

* Los materiales creados con una versión anterior no estarán disponibles en la nueva versión.
* &lbrack;MacOS&rbrack; El Substance Alchemist de cierre puede necesitar un &quot;Forzar el cierre&quot;
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
