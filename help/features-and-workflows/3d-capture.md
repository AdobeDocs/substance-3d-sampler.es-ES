---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/3d-capture.html"
breadcrumb-title: ''
description: Aprende a usar Captura 3D en Substance 3D Sampler para crear materiales a partir de objetos del mundo real mediante técnicas de fotogrametría.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > 3D Capture
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Captura 3D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '2364'
ht-degree: 0%

---


# Captura 3D

## Procedimientos iniciales

## ¿Qué es la fotogrametría?

Sampler utiliza la fotogrametría para transformar imágenes en una malla con texturas. La fotogrametría es la ciencia de hacer mediciones a partir de imágenes. Se utiliza para extraer información de fotografías y crear texturas y modelos en 3D. El proceso implica tomar varias fotografías de un objeto desde diferentes ángulos y, a continuación, procesar las imágenes para extraer información sobre la forma y la ubicación de las características en las imágenes.

El objetivo es hacer coincidir las características correspondientes entre las imágenes para establecer las posiciones relativas de la cámara para cada imagen. A partir de las funciones coincidentes, se reconstruye un modelo 3D del objeto. El paso final es proyectar las texturas en el modelo 3D.

## Requisitos de hardware

El captura 3D está disponible en Windows y MacOS Monterey o Ventura.

Windows/Linux

Recomendamos lo siguiente:

* GPU con 8 Gb de VRAM
* 16 Gb de RAM. Idealmente, 32 Gb y 64 Gb.
* 10 Gb como mínimo de espacio en disco

[Configuración de Linux](https://helpx.adobe.com/substance-3d/unlisted/documentation/sadoc/3d-capture-set-up-on-linux-255426606.html)

Mac

* Se recomienda encarecidamente utilizar dispositivos con Apple Silicon (M1 o M2)
* GPU AMD y basada en Intel con al menos 4 Gb de VRAM y compatibilidad con trazado de rayos

## Iniciar una nueva Captura 3D

![](../assets/main-window-empty-screen.png)

## Importar el conjunto de datos

## Preparación del conjunto de datos

Arrastre y suelte sus fotos o haga clic para examinar el explorador del sistema operativo.

>[!NOTE]
>
> **Recomendaciones del conjunto de datos**
> 
> Se recomienda tener un conjunto de datos que contenga al menos <b>20 imágenes</b> para que el captura 3D se ejecute sin problemas.

![](../assets/main-window-import-dataset-empty.png)

Para los usuarios de iPhone, el formato .HEIC aún no es compatible. Puede utilizar Lightroom para convertir a .jpeg.

En MacOS, puedes usar [Acciones rápidas](https://support.apple.com/en-gb/guide/mac-help/mchl97ff9142/mac) para convertir tus imágenes.

En el caso de las cámaras con formatos RAW, se recomienda utilizar Lightroom para convertir las fotografías en archivos .jpeg.

>[!NOTE]
>
> **Limitaciones del conjunto de datos**
> 
> **Windows**: El conjunto de datos debe ser menor que 6 GB de píxeles (6 000 000 000 píxeles) en total. Representa 500 fotos de 12M píxeles

![](../assets/main-window-dataset-imported.png)

Una vez importadas las fotos, puedes hacer clic en una foto para verla completa.

![](../assets/main-window-photo-panel.png)

Definición de fotogrupo:

El conjunto de datos se puede dividir en varios grupos de fotografías. Fotogrupos agrupa las fotografías por propiedades (tamaño del sensor, distancia focal, rotación,...)

## Enmascaramiento

El uso de máscaras tiene muchas ventajas. Permite que el proceso de fotogrametría detecte características y reconstruya solo áreas no enmascaradas.

Esto también permite mover el objeto durante la captura, ya que las máscaras ocultarán el fondo en todas las fotografías.

Para usar máscaras, selecciona un fotogrupo y abre la pestaña **Máscara** de la derecha.

![](../assets/main-window-masking-panel.png)

Puede importar máscaras respetando una convención de nombres:

* [image\_name].file\_extension
* [image\_name]\_mask.file\_extension

Puedes generar máscaras automáticamente con fotos mediante nuestra tecnología de IA.

![](../assets/main-window-masking-result.png)

## Alineación

La alineación consiste en procesar todas las imágenes para extraer y hacer coincidir las características correspondientes para establecer las posiciones relativas de la cámara para cada imagen.

## Configuración

![](../assets/main-window-alignment-settings.png)

Precisión

Hay dos opciones, baja y alta.

* Baja: recomendado para la mayoría de los conjuntos de datos.
* Alta: aumente el número de puntos, se aconseja hacer coincidir más fotos en casos en los que el sujeto no tenga textura suficiente o las fotos sean pequeñas. Esta configuración hace que el procesamiento sea más lento. Le recomendamos que pruebe la opción baja primero.

Orden de fotos

Hay dos opciones: predeterminada y secuencia.

Esto se puede calcular utilizando diferentes algoritmos de coincidencia de funciones:

* Predeterminado: la selección se basa en varios criterios, entre los que se encuentra la similitud entre imágenes.
* Secuencia: utilice solo imágenes adyacentes dentro de la distancia dada, recomendado para procesar una sola secuencia de fotos si el modo predeterminado ha fallado. El orden de inserción de la fotografía debe corresponder al orden de secuencia.

## Nube de puntos y posición de cámaras

El resultado del paso de alineación es una nube de puntos dispersos con todas las funciones detectadas y la posición de todas las cámaras.

Si el contorno de la imagen es verde, la imagen se ha alineado correctamente.

Si el contorno de la imagen es naranja, significa que la imagen no se ha alineado correctamente y que no se ha extraído ninguna función de la imagen.

![](../assets/3d-capture-alignment-results.png)

Puede hacer clic en la imagen del panel izquierdo para encuadrar la nube de puntos en la cámara asociada.

Puede hacer clic en una cámara para encuadrar la nube de puntos en ella.

## Reconstrucción

El paso de reconstrucción genera un modelo 3D del objeto a partir de las funciones coincidentes al proyectar las texturas en el modelo 3D.

## Configuración

Detalles de la geometría Esta opción especifica el nivel de precisión en las fotografías de entrada, lo que resulta más o menos detallado en el modelo 3D calculado.

## Región de interés

Antes de generar el modelo 3D, puede definir la región que se reconstruirá alrededor de la nube de puntos con el cuadro delimitador.

Puede trasladar, escalar y rotar el cuadro en el eje 3.

Si pulsa Mayús al escalar, cambiará la escala del cuadro desde el centro.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../assets/3d-capture-bounding-box-original.png)

</td>
<td style="border: 0;" valign="top">

![](../assets/3d-capture-bounding-box-modified.png)

</td>
</tr>
</table>

## Posprocesamiento

El procesamiento posterior le ayuda a adaptar y optimizar su malla y texturas a sus necesidades y a cómo desea usarlas.

El resultado de la reconstrucción puede generar una malla con millones de polígonos y hasta 16K de texturas. A menudo, esto no se optimiza para el procesamiento, el tiempo real o la experiencia de realidad aumentada.

Deberá procesar el resultado posteriormente para reducir el número de polígonos sin perder detalles.

El paso posterior al procesamiento encadena 4 pasos automáticamente:

* Diezmación: Reduzca el número de polígonos definiendo el número de caras que desea
* Desempaquetado UV: Define automáticamente las costuras, desenvuelve y empaqueta las UV de la malla diezmada
* Reproyección: Volver a proyectar la textura de color de la malla de fotogrametría en la malla diezmada
* Horneado: Hornee los detalles normales, de height y de AO de la malla de fotogrametría en la malla diezmada. Esto asegurará transferir todos los detalles de malla perdidos durante la diezmación en mapas de textura.

![](../assets/3d-capture-original-version-post-processing.png)

## Versión

Para iterar y probar fácilmente diferentes opciones de postproceso, puede crear varias versiones y seleccionar la que desee agregar al proyecto.

Para ayudarle, puede visualizar la malla en diferentes modos.

Modo sólido

![](../assets/3d-capture-post-processing-solid.png)

modo malla metálica

![](../assets/3d-capture-post-processing-wireframe.png)

Modo de cuadrícula UV

![](../assets/3d-capture-post-processing-uv-grid.png)

## Flujo de trabajo no destructivo

![](../assets/main-window-add-to-project.png)

Una vez agregada una versión al proyecto, se crea una pila de capas con varias capas.

La primera capa es el resultado de la reconstrucción.

La segunda capa (si ha realizado algún postprocesamiento) es la capa de postprocesamiento de malla con los valores definidos en la ventana captura 3D. Puede seguir editando los parámetros en este paso si desea utilizar otros ajustes.

La tercera capa es una capa de transformación de malla para escalar, trasladar y rotar el objeto 3D.

En esta fase, puede añadir filtros que se utilizan para aplicar en materiales para editar las texturas en el objeto 3D.

![](../assets/main-window-texturing.png)

## Exportar

En la ventana de exportación, puede definir el formato de malla y los ajustes de material (los mismos ajustes al exportar un material).

![](../assets/main-window-export.png)

## Tutoriales

[Ir a Tutorials avanzados](https://substance3d.adobe.com/tutorials/courses/Advanced-3D-Capture/youtube-f8iCtZ3Gmzs)

## FAQ

**¿Cuáles son las mejores condiciones de captura para la fotogrametría?**

Para que la fotogrametría produzca resultados precisos, es importante seguir ciertas prácticas recomendadas al capturar imágenes.

1. Iluminación: La fotogrametría funciona mejor cuando las imágenes se capturan en buenas condiciones de iluminación. Evita tomar imágenes con iluminación de baja o alta contrastación, ya que pueden dificultar la extracción precisa de rasgos de las imágenes. Las mejores condiciones de iluminación para la fotogrametría son los días nublados o las zonas sombreadas.
1. Superposición: Para garantizar que haya suficiente información en las imágenes para extraer características con precisión, es importante capturar imágenes con superposición significativa. Una regla general es que al menos el 60 % de las imágenes se solapen, tanto horizontal como verticalmente.
1. Cámara: Utilice una cámara y una lente de alta resolución que ofrezcan una buena calidad de imagen y nitidez. Evite el uso de cámaras con lente ojo de pez o lente gran angular, ya que puede causar distorsión geométrica que puede afectar a los resultados finales.
1. Orientación: Al tomar imágenes, trate de mantener la cámara nivelada y perpendicular al suelo. Las imágenes tomadas en ángulo pueden dificultar la extracción precisa de características y dar lugar a resultados distorsionados.
1. Calibración de la cámara : Asegúrese de que la cámara esté calibrada antes de tomar las imágenes. Este proceso permite corregir la distorsión de la lente y otros errores que pueden afectar a la precisión de los resultados finales.

**¿Cómo funciona para speculares y objetos reflectantes?**

La fotogrametría puede ser un desafío cuando se trabaja con objetos muy speculares o reflectantes, ya que los reflejos brillantes pueden dificultar la extracción de características de las imágenes. Estas son algunas estrategias que se pueden utilizar para superar estos desafíos:

1. Iluminación: Al capturar imágenes de objetos con altos reflejos, intente evitar la luz solar directa y, en su lugar, capture imágenes en condiciones de nublado o sombreado. Esto puede ayudar a reducir la intensidad de los reflejos y facilitar la extracción de características de las imágenes.
1. Acabado mate: La aplicación de un acabado mate a las superficies reflectantes puede ayudar a reducir la intensidad de los reflejos y facilitar la extracción de características de las imágenes.
1. Capturar varias imágenes: La captura de varias imágenes del mismo objeto desde diferentes ángulos puede ayudar a reducir el impacto de los reflejos y aumentar las posibilidades de poder extraer características de al menos algunas de las imágenes.
1. Edición de imágenes: En el posprocesamiento, ciertos programas de edición de imágenes como Lightroom se pueden utilizar para reducir los reflejos y mejorar las funciones de las imágenes, como aumentar el contraste o la corrección del color.

Tenga en cuenta que los objetos reflectantes pueden necesitar ajustes y tratamientos más elaborados, y puede que no sea posible obtener resultados perfectos en todos los casos. Es una buena idea experimentar con diferentes técnicas.

**¿Cuál es la recomendación entre un teléfono móvil y una cámara DSLR para la fotogrametría?**

Tanto los teléfonos móviles como las cámaras DSLR se pueden utilizar para la fotogrametría, pero tienen diferentes puntos fuertes y débiles. A continuación, se indican algunos aspectos que se deben tener en cuenta a la hora de decidir qué tipo de cámara utilizar:

1. Resolución: Las cámaras DSLR suelen tener una resolución mucho mayor que los teléfonos móviles, lo que puede dar lugar a resultados más detallados y precisos. Sin embargo, con el reciente avance en cámaras de teléfonos móviles, algunas cámaras de teléfonos móviles de gama alta tienen una resolución y una calidad de imagen comparables a las de algunas cámaras DSLR de gama baja.
1. Calibración de la cámara: La fotogrametría se basa en una calibración precisa de la cámara, lo que suele ser más difícil de conseguir con las cámaras de teléfonos móviles que con las cámaras DSLR. Algunas cámaras de teléfonos móviles tienen parámetros de calibración integrados que puede utilizar, pero puede que no sean tan precisos como una calibración adecuada de una cámara DSLR.
1. Duración de la batería y almacenamiento : Las cámaras de teléfonos móviles tienen una duración de batería más limitada en comparación con las cámaras DSLR. Por lo tanto, tendrá que planificar la carga del teléfono o el transporte de baterías adicionales mientras trabaja. Además, debe asegurarse de que el teléfono tiene suficiente capacidad de almacenamiento para manejar archivos de imagen grandes.
1. Coste: Las cámaras DSLR suelen ser más caras que los teléfonos móviles y también requieren accesorios adicionales, como trípodes y unidades flash externas.
1. Portabilidad: Un teléfono móvil es más portátil que una cámara réflex digital y es más probable que tengas el teléfono contigo cuando te encuentres con un objeto o escena interesante que quieras capturar para fotogrametría.

En resumen, realmente depende de sus necesidades específicas y las características del proyecto. Para proyectos de baja resolución, un teléfono móvil puede ser suficiente. Sin embargo, si se necesita alta precisión y alta resolución, una cámara DSLR puede ser una mejor opción. Además, si tiene previsto tomar fotografías de forma regular o para un proyecto a largo plazo, invertir en una cámara DSLR puede ser una solución más rentable a largo plazo.

**¿Cómo debo calibrar mi cámara para limitar el desenfoque en mi objeto?**

La calibración de la cámara es un paso importante en el proceso de fotogrametría que ayuda a corregir la distorsión de la lente y otros errores que pueden afectar a la precisión de los resultados finales. A continuación, se indican algunos pasos que puede seguir para calibrar la cámara y limitar el desenfoque en el objeto:

1. Utilice un trípode: Para mantener la cámara estable y reducir el desenfoque, es importante utilizar un trípode al capturar imágenes para fotogrametría. Esto garantizará que la cámara esté en la misma posición para cada toma y ayudará a minimizar el movimiento de la cámara.
1. Usar un disparador remoto: Para reducir aún más el movimiento de la cámara, puede utilizar el disparador del obturador remoto o la función de temporizador automático en la cámara para tomar las imágenes. Esto ayudará a minimizar cualquier movimiento de la cámara causado por presionar el botón del obturador.
1. Ajuste la velocidad del obturador: Para reducir el desenfoque causado por el movimiento de la cámara, debes usar una velocidad de obturación rápida. Una regla general es usar una velocidad de obturación que sea al menos tan rápida como la recíproca de la distancia focal del objetivo. Por ejemplo, si estás usando un objetivo de 50 mm, deberías usar una velocidad de obturación de al menos 1/50 de segundo.
1. Utilice un ISO alto: En condiciones de poca luz, puede ser necesario utilizar un ISO más alto para mantener una velocidad de obturación rápida y reducir el desenfoque. Sin embargo, tenga en cuenta que un ISO alto también puede aumentar el ruido en la imagen, lo que puede afectar a la precisión de los resultados finales.
1. Usar un flash: En algunas situaciones, el uso de un flash puede ayudar a reducir el desenfoque causado por la luz insuficiente. Ten en cuenta que el flash también puede causar reflejos y otros problemas en algunos casos, así que asegúrate de experimentar con instantáneas con flash y sin flash para ver cuál funciona mejor para tu aplicación específica.

Recuerde que la calibración es un proceso iterativo y que puede requerir varios intentos para obtener buenos resultados.

**¿Puedo mover el objeto durante la captura para fotogrametría?**

En la mayoría de los casos, no se recomienda mover el objeto durante la captura para realizar una fotogrametría. El proceso de fotogrametría se basa en que el objeto se encuentre en una posición fija para cada imagen, ya que el software utiliza las posiciones relativas de las características en las imágenes para reconstruir un modelo 3D del objeto.

Si el objeto se mueve durante la captura, aparecerá en una posición diferente en cada imagen, lo que dificultará que el software coincida con las características correspondientes entre las imágenes. Esto puede dar lugar a imprecisiones en el modelo 3D final y también puede dificultar o hacer imposible el paso de coincidencia de imágenes.

Sin embargo, hay algunos casos en los que mover el objeto puede ser beneficioso. Por ejemplo, en el caso de objetos pequeños, en los que es difícil tomar imágenes con superposiciones significativas, es posible utilizar una placa giratoria y rotar el objeto para asegurarse de que todas las funciones se capturan desde múltiples ángulos.
