---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/tools/atlas-splitter.html"
breadcrumb-title: ''
description: Utiliza la herramienta Atlas splitter de Substance 3D Sampler para dividir atlas de texturas en mapas de texturas individuales para la edición de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Atlas Splitter
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Atlas splitter
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 0%

---


# Atlas splitter

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-atlassplitter-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El **Atlas splitter** es una herramienta útil para organizar y ver los elementos de un atlas.

Las imágenes siguientes muestran el **Atlas splitter** en acción.

![](../../assets/3d-2d-filters-cropped-0039-atlas-splittter-in.jpg)

La imagen anterior muestra un material de atlas añadido a la pila de capas. use el **Atlas splitter** para seleccionar elementos específicos del atlas.

![](../../assets/3d-2d-filters-cropped-0038-atlas-splitter-out.jpg)

Con el **Atlas splitter** añadido a la pila de capas, es posible centrarse en una sola hoja o en cualquier otro elemento del material del atlas.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Vista de cuadrícula**: alternar\
  Cambiar entre la vista de cuadrícula y la vista individual de los elementos. Si se ha activado, aparecerán los siguientes parámetros adicionales:
  * **Opacidad de cuadrícula**: 0-1\
    Modificar la opacidad de la cuadrícula
  * **Opacidad de selección de cuadrícula**: 0-1\
    Modificar la opacidad del borde alrededor del elemento seleccionado
  * **Escala automática**: alternar\
    Cambiar si los elementos del atlas se escalan para rellenar cada cuadrado de la cuadrícula o no.
* **Recorte automático**: alternar\
  Seleccione si desea ajustar el recorte de la forma seleccionada. Si se activa, aparecerá una opción adicional:
  * **Modo de recorte automático**:\
    Elija cómo se recorta el elemento seleccionado para rellenar el espacio del material.
* **Selección de forma**: 1-10\
  Cambiar el elemento del atlas que está seleccionado. Para atlas con más de 10 elementos, puede escribir un número en el valor **Selección de forma** para cambiar el rango del regulador.
* **Rotación**: 0-1\
  Rotar elementos

**Parámetros avanzados**

* **Tolerancia de forma pequeña**: 0-1\
  Ajuste el tamaño mínimo de las formas que debe seleccionar el **Atlas splitter**. Esto resulta útil para filtrar artefactos
* **Rotación automática**: alternar\
  Si se activa, los elementos se girarán automáticamente para tener orientaciones similares.
* **Disminuir escala de máscara de opacidad**: 0-4\
  Ajuste la escala de la máscara de opacidad. Tenga en cuenta que el aumento de este valor puede disminuir la calidad de la máscara de opacidad.
* **Precisión de detección de formas**:\
  Seleccione el algoritmo de detección de formas que desea utilizar.
* **Ancho de dilatación**: 0-32\
  Modificar la dilatación: de este modo, se extruyen los colores de los bordes del elemento en el área enmascarada para evitar problemas de transparencia en el borde de los elementos del atlas. Vea el canal de color base en la **vista 2D** para ver los resultados.
* **Color de fondo personalizado**: alternar\
  Si se habilita, aparece un control para modificar el color de fondo del canal normal:
  * **Color de fondo normal**: selección de color\
    Seleccione el color de fondo personalizado del canal normal en las partes transparentes del material.
* **Color De Fondo De Height**: 0-1\
  Ajuste el color de fondo del canal de height. En general, es una buena idea hacer que el fondo del height coincida con el height medio de los bordes de los elementos del atlas para evitar artefactos en los bordes de los elementos.
