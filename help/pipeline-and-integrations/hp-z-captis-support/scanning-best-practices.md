---
title: Prácticas recomendadas al digitalizar
description: Aprenda a preparar y colocar sus muestras físicas antes de escanear con HP Z Captis para ahorrar tiempo en el procesamiento posterior en Substance 3D Sampler.
source-git-commit: a0034da3bee13d0d7423828a902da62cf2219474
workflow-type: tm+mt
source-wordcount: '659'
ht-degree: 0%

---


# Análisis de prácticas recomendadas

La calidad de un material digitalizado se decide mucho antes de pulsar el botón de exploración. Una muestra limpia, plana y bien colocada produce mapas limpios que están listos para usarse, mientras que una captura precipitada lleva cada arruga, mota de dust y fibra perdida directamente a tus canales PBR.

La regla de oro es simple: **Dedica un minuto más a preparar el material antes de que el análisis te ahorre unos diez minutos de limpieza más tarde**. El tiempo dedicado a planchar una tela, quitar el dust o alinear la muestra es el tiempo que no dedicará más tarde a desdeformar el material, aplicar parches a las partículas o eliminar las fibras sueltas.

Esta página cubre dos áreas que marcan la mayor diferencia: **preparando tu muestra física** y **colocándola correctamente** en el dispositivo.

## Prepare su muestra física

Todo lo visible en la muestra cuando se captura se copia en los mapas. Unos minutos de preparación eliminan los problemas en el origen antes de que se conviertan en un trabajo de edición.

**Limpiar la muestra**

Dele a la muestra una limpieza rápida antes de colocarla. Cualquier marca en la superficie se interpretará como un detalle del material y se reproducirá en todos los canales.

**Quitar dust y partículas extrañas**

El dust, el pelo, los hilos y otras partículas sueltas son una de las fuentes más comunes de trabajo de posprocesamiento. Cepille o utilice aire comprimido para limpiar la superficie, ya que cada partícula que quede detrás debe pintarse a mano más adelante.

![](../../assets/scanning/clean-textile.png)

**Tejidos de hierro para eliminar las arrugas**

Para las telas y otros materiales flexibles, plancha siempre la muestra plana antes de escanearla. Las arrugas y los pliegues crean falsa información de height y sombra que es difícil de eliminar posteriormente, y que rompe el mosaico del material.

![](../../assets/scanning/flatten-textile.png)

**Eliminar manchas de superficies lisas**

En materiales lisos y no porosos, limpie cualquier mancha, huella digital o manchas. Estos se muestran claramente en los canales de color base y de rugosidad.

**Conocer el thickness de muestra**

Tenga en cuenta el grosor de la muestra. Conocer el thickness le ayuda a colocarlo correctamente y a configurarlo para que la superficie permanezca enfocada en toda el área de escaneo.

## Colocar la muestra correctamente

Una buena colocación mantiene el material plano, nítido y centrado, lo que reduce la cantidad de recorte, desdeformación y alineación que hay que hacer más adelante.

![](../../assets/scanning/center-textile.png)

**Centrar el material en el área de análisis**

Coloque la muestra en el centro del área de exploración. Aquí es donde el enfoque y la iluminación son más uniformes, y da la superficie más útil una vez que el material se recorta. Por esta razón, siempre es ideal escanear una muestra a la vez, para que pueda colocarse en el centro del área de escaneo y obtener los mejores resultados posibles.

**Alinéalo lo más recto posible**

Alinee la muestra a escuadra con el área de exploración en lugar de hacerlo en ángulo. Una muestra recta es mucho más fácil de crear en mosaico y necesita menos rotación y recorte en Sampler.

**Mantener la muestra plana**

Asegúrese de que la muestra queda completamente plana contra la superficie de exploración. Si es necesario, utilice los imanes suministrados con el dispositivo HP Z Captis para sujetar materiales flexibles o rizados. Una muestra plana evita la deformación y el enfoque desigual que, de lo contrario, requiere mucho tiempo corregir.

**No superponer muestras**

Si coloca varias muestras a la vez, no permita que se toquen o se superpongan. Los bordes superpuestos crean límites ambiguos que son difíciles de separar y recortan limpiamente más adelante.

## La recompensa en Sampler

Cuando el ejemplo está limpio, plano y centrado, los mapas que llegan a Sampler ya están cerca de estar listos para la producción. Dedicas tu tiempo a refinar el material en lugar de repararlo: menos tiempo para desdeformar, menos tiempo para limpiar dustes y fibras, y menos tiempo para eliminar manchas y arrugas de tus canales.

Una vez importado el material, utilice los filtros de Sampler (Ecualizar, Mosaico automático, Recorte con perspectiva, Mosaico, ...) para los últimos retoques y exporte cuando esté satisfecho con el resultado.
