---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/pipeline-and-integrations/hp-z-captis-support/faq-hp-z-captis-support-in-sampler.html"
breadcrumb-title: ''
description: Acceda a preguntas frecuentes sobre la compatibilidad con HP Z Captis en Substance 3D Sampler para encontrar respuestas sobre la integración y el uso del hardware.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Preguntas frecuentes sobre la compatibilidad con HP Z Captis en Sampler
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '1547'
ht-degree: 0%

---


# Preguntas más frecuentes

## Muestras de material

+++¿Qué casos prácticos cubre Captis?
La solución abarca casos prácticos de varios sectores (automoción, confección, diseño de productos, medios y entretenimiento, arquitectura...). El modo Studio permite la captura de escritorio (repetible, eficiente y simple) mientras que el modo Explorer permite la captura móvil &quot;flexible, en cualquier parte, adaptándose a cada situación&quot;.

+++

+++¿Qué tipos de materiales se pueden escanear y capturar con Captis?
Se pueden escanear y capturar cualquier tipo de material, excepto con varias capas transparentes (las pinturas de coches no se incluyen en el ámbito de Captis). Algunos materiales específicos pueden requerir un procesamiento adicional en Sampler para optimizar los resultados. Tenga en cuenta que los algoritmos de procesamiento se optimizarán continuamente con el tiempo.

+++

+++¿Cuáles son las restricciones sobre el tamaño o la forma de la muestra de material? ¿Es necesario que las muestras sean planas?
Captis puede escanear una gran variedad de muestras de material de tamaño o forma. Se suministra con imanes para aplanar las muestras en la bandeja de muestras. Existen varios modos de capturar una muestra de material con Captis:

* Modo de estudio: con la base de estudio en su escritorio, en el estudio o en la fábrica, Captis tomará muestras de hasta 30cm x 30cm, con iluminación de fondo para la opacidad. La profundidad de la bandeja de muestra es de 1,8 CM.

* Modo Explorador: puede utilizar el anillo del explorador en el campo, en el set o en entornos únicos y permitir una captura flexible para muestras de más de 30 cm x 30 cm. Limitación actual: tenga en cuenta que el modo Explorador sigue siendo una versión anterior y que aún no se ha optimizado (a partir del 29 de julio de 2024).

+++

## Software

+++¿Requiere el dispositivo HP Z Captis una suscripción de software o licencia para su uso?
El dispositivo Captis requiere una licencia activa de Substance 3D Sampler para empresas, equipos o universidades, disponible en Substance 3D Collection en las mismas condiciones y términos de uso que cualquier suscripción a Substance 3D.

El dispositivo (HP Z Captis) y la licencia (Substance 3D Sampler) se venden por separado.

+++

+++¿Qué nivel de integración existe con el conjunto de Substance de Adobe?
El dispositivo HP Z Captis está totalmente controlado y funciona a través de Adobe Substance 3D Sampler: puede previsualizar e iniciar la captura desde Substance 3D Sampler y, una vez completada la captura, se cargarán automáticamente los canales PBR como una capa y se creará un material 3d. Puedes seguir procesando tus materiales con todas las herramientas y filtros disponibles en Sampler.

Una vez que el material capturado esté en Substance 3D Sampler, puede exportarlo a cualquier aplicación del conjunto de Substance 3D (Substance 3D Designer, Painter, Stager) y a cualquier Substance compatible con aplicaciones de terceros, incluidos 3DS Max, Maya, Blender, Unreal Engine, CLO, Browzwear, VRED, Rhino, Cinema4D y muchos más (consulte la lista completa aquí: <https://www.adobe.com/es/products/substance3d/plugins.html>).

+++

+++¿Cuáles son las especificaciones recomendadas para utilizar Substance 3D Sampler con Captis?
Las especificaciones de hardware de Sampler están disponibles [aquí](system-requirements-to-use-hp-z-captis.md).

+++

+++¿El flujo de trabajo de HP Z Captis está disponible tanto en Windows como en Mac?
A partir de la versión del 20 de febrero de 2025, el flujo de trabajo de Sampler con HP Z Captis solo está disponible en Windows.

+++

+++¿Dónde puedo encontrar la versión de Substance 3D Sampler con flujo de trabajo HP Z Captis?
A partir de la versión del 20 de febrero de 2025, podrá acceder al flujo de trabajo de Adobe Substance 3D Sampler con Captis como parte de las compilaciones normales de Substance 3D Sampler, que se descargan desde la aplicación de escritorio de Creative Cloud. Ya no es necesario descargarlos desde la versión previa de Adobe.

+++

+++¿Qué no está disponible todavía?
*Limitaciones en agosto de 2025 (versión Sampler 5.1.0):*

* El flujo de trabajo de Sampler con HP Z Captis solo está disponible en Windows por ahora.

* Los cinco mapas que se exportan hoy son el color base, Rugosidad, Normal, Height, Opacidad.

* El modo Explorador sigue siendo una versión anterior y no se ha optimizado todavía.

* El mosaico se realiza en la pila de capas de Sampler mediante los filtros de mosaico actuales.

+++

+++¿Qué canales de PBR hay disponibles?
A partir del 7 de agosto de 2025, los cinco mapas que se exportan son Color base, Rugosidad, Normal, Height y Opacidad. La canalización de procesamiento actual aún no gestiona el mapa de Metalness.

+++

+++¿El mosaico se realiza automáticamente?
El mosaico se realiza en la pila de capas de Sampler mediante los filtros de mosaico actuales.

El filtro de mosaico automático se puede utilizar para mosaico automáticamente de materiales con una estructura repetitiva definida o patrones pequeños, con un mínimo de 3 patrones en cada dirección. Obtenga más información sobre este filtro en la [sección dedicada de la documentación](../../filters/tools/auto-tiling.md).

+++

+++¿En qué formatos se pueden exportar los materiales digitalizados?
HP Z Captis es operado de forma nativa por Adobe Substance 3D Sampler. HP Z Captis captura 64 imágenes sin procesar (que se pueden recuperar de la carpeta local) y mapas PBR (que se procesan a partir de las imágenes capturadas sin procesar y que se cargan automáticamente en Substance 3D Sampler). Substance 3D Sampler creará un material 3D basado en los canales PBR que se cargan automáticamente en la pila de capas de Sampler después de la captura.

Desde Adobe Substance 3D Sampler, puede exportar el material digital en cualquier formato de exportación disponible en Substance 3D Sampler: como archivos de Substance (archivos .SBS y .SBSAR) o como texturas de mapa de bits, incluidos .PNG, .JPG, .TIFF... (consulte los detalles en la página web de documentación de Sampler: [https://helpx.adobe.com/es/substance-3d-sampler/getting-started/export.html](../../getting-started/export/export.md)).

+++

+++¿Cuál es la diferencia entre LDR y HDR durante la captura?
Durante la previsualización, puede elegir el tipo de salida entre LDR (bajo rango dinámico) y HDR (alto rango dinámico).\
Incluso si se elige LDR, los mapas HDR se capturarán y guardarán en el dispositivo.\
Se aconseja que seleccione el LDR, ya que esto hará que el tamaño del proyecto sea más manejable en Sampler y en cualquier aplicación de terceros donde se utilizará el archivo sbsar.

+++

## Procesamiento

+++¿Cómo puedo usar Captis en mi canal 3D actual si uso formatos de archivo, estándares y especificaciones específicos o aplicaciones de terceros?
HP Z Captis es operado de forma nativa por Adobe Substance 3D Sampler. Una vez que haya capturado y digitalizado su muestra de material en Substance 3D Sampler, puede exportar sin problemas sus materiales digitales:

En cualquier aplicación del ecosistema de Substance 3D (incluidos Substance 3D Designer o Substance 3D Painter que admitan varios formatos de exportación): https://experienceleague.adobe.com/es/docs/substance-3d/general-knowledge/ecosystem/import-and-export-formats).

En cualquier aplicación que integre el formato de archivo Substance como 3DS Max, Maya, Blender, C4D, Rhino, Browzwear, CLO... (ver la lista completa aquí: <https://www.adobe.com/es/products/substance3d/plugins.html>). Si utilizas una aplicación que no figure en la lista, siempre puedes exportar imágenes de texturas PBR y conectarlas manualmente a cualquier aplicación que no admita el formato de archivo de Substance de forma nativa.

+++

+++¿Cuántas fotos se están tomando para crear los mapas?
[8 paneles de luz + 1 luz de fondo] x [8 estados de polarización] x [8 exposiciones de horquillado para HDR] x [4 sobredibuja para reducir el ruido] = 2048 + 256 (para luz de fondo)

+++

## Administración de dispositivos

Obtén más información sobre el dispositivo y sus especificaciones en el [sitio web de HP](https://www.hp.com/us-en/workstations/z-captis.html "HP Z Captis").

+++¿Puedo cambiar la dirección IP del dispositivo?
Para cambiar la dirección IP del dispositivo, puede modificar el archivo de Windows C:\Windows\System32\drivers\etc\hosts.txt by añadiendo una línea adicional:

Por ejemplo, puede agregar 192.168.55.1 captis-device y, a continuación, en <b>Configuración de Sampler > Almacenamiento y caché > Captura de material > Dirección de captis</b>, reemplazar la dirección IP por captis-device

+++

## Problemas de uso

+++Sampler no detecta los HP Z Captis.
Asegúrese de que el HP Z Captis esté conectado a un puerto USB 3.0.

Asegúrese de que el cable USB esté conectado a la base del HP Z Captis, no al cono.

+++

+++Mi vista previa está completamente negra en la ventana de Sampler.
Asegúrese de que ha eliminado la protección de la cámara.

+++

+++Copiar archivos de HP Z Captis en mi ordenador es lento.
Asegúrese de que el HP Z Captis esté conectado a un puerto USB 3.0.

Si ha solicitado recuperar tanto el material como las imágenes de fotometría, es normal que la copia tarde más tiempo.

+++

+++Sampler no copió las imágenes en mi equipo. ¿Tengo que reiniciar el análisis?
No, tú no. Puede examinar el contenido del dispositivo y copiar las imágenes que se encuentren en la carpeta del Adobe mediante el explorador de archivos de su sistema operativo.

+++

+++El menú indica que el dispositivo está en modo de recuperación.
Presione el botón de encendido durante unos segundos para apagarlo. Vuelve a encenderlo.

+++

+++Moví el cono desde su base al anillo del explorador y ya no puedo escanear.
Se recomienda desactivar el HP Z Captis antes de desenchufarlo de su base o del anillo del explorador.

+++

+++La exportación de mi material en SBSAR es lenta.
Asegúrese de que las imágenes no estén en formato flotante de 32 bits en el panel Propiedades.

También puede definir el nivel de compresión en &quot;ninguno&quot; para agilizar la exportación.

+++

+++Deseo cambiar la ruta de almacenamiento de los materiales capturados y las imágenes de fotometría.
Ahora es posible editar la ubicación en la que se guardarán los materiales capturados y las imágenes de fotometría, en Edición > Preferencias > Almacenamiento y caché > Captura de material.

+++

+++La ventana es más grande que mi pantalla y no puedo cambiar su tamaño.
La ventana Captis no se puede cambiar de tamaño. Es posible que esté utilizando una ampliación de pantalla no controlada. Captis admite lo siguiente:

* Resolución: 1920 x 1080
  * Ampliación máxima: 100 %

* Ampliación máxima: 100 %

* Resolución: 2560 x 1440
  * Ampliación máxima: 125 %

* Ampliación máxima: 125 %

* Resolución: 3840 x 2160
  * Ampliación máxima: 200 %

* Ampliación máxima: 200 %

* Las resoluciones inferiores a 1920 x 1080 no son compatibles.



+++
