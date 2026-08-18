---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/auto-tiling.html"
breadcrumb-title: ''
description: Utiliza la herramienta Mosaico automático de Substance 3D Sampler para crear automáticamente patrones de mosaico perfectos a partir de texturas con tecnología de IA.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mosaico automático
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '575'
ht-degree: 0%

---


# Mosaico automático

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El <b>filtro Mosaico automático</b> busca estructuras repetitivas en tu material y las usa para crear un material de mosaico. A diferencia del <b>filtro Hacer mosaico</b> o del <b>filtro Mosaico</b>, el <b>Mosaico automático</b> se centra en aislar el área más pequeña del material que se puede hacer en mosaico.

<b>La segmentación automática </b> es especialmente útil para textiles.

</td>
</tr>
</table>

>[!NOTE]
>
> Para que el filtro Mosaico automático funcione, se requiere un mínimo de repeticiones 3x3 en la imagen o el material de origen.

## Tutorial de filtro de segmentación automática

## Acerca del segmentación automática

Al agregarlo a la pila de capas, <b>Mosaico automático</b> intentará encontrar automáticamente patrones repetidos y generar un material de mosaico. Si esto no funciona, puedes usar el botón <b>Configuración avanzada </b> para ajustar manualmente el proceso.

Si estás planeando crear un material de mosaico a partir de una imagen, es mejor usar el <b>filtro Mosaico automático</b> primero y luego usar el filtro <b>Imagen a material</b>.

<b>Mosaico automático</b> se ejecuta por completo en tu dispositivo, no se envía contenido a la nube.

## Parámetros

A diferencia de la mayoría de los filtros, <b>Mosaico automático</b> no tiene parámetros. En su lugar, hay un botón <b>Configuración avanzada </b>, que le guiará a través del proceso de configuración del filtro. No es necesario realizar ajustes manuales en cada paso, y puede saltar hacia delante o hacia atrás seleccionando un paso en la parte superior de la ventana.

Este proceso consta de los siguientes pasos:

1. <b>Introducción</b>: Explica cómo funciona el filtro. Use la casilla de verificación para ocultar esta pantalla en el futuro.
1. <b>Asignar selección</b>: Seleccione el canal que debe utilizar el filtro. Se recomienda el canal con el patrón de repetición más visible. Este suele ser el color base o el canal de Height, pero otros canales pueden ser útiles en función del material.
1. <b>Configuración de muestra</b>: Realice cambios en el material de entrada para obtener los mejores resultados. Esto incluye elegir una resolución y rotar o deformar la entrada. Si el patrón es muy pequeño, puede ser útil seleccionar una resolución más alta para asegurarse de que el patrón es visible. Sin embargo, para patrones más grandes, una resolución más baja puede proporcionar resultados mejores y más rápidos.
1. <b>Tamaño de trama</b>: En este paso, el filtro busca el patrón más pequeño que puede encontrar. Puede seleccionar una detección automática mayor o menor, o seleccionar un tamaño personalizado para especificar su propio tamaño. Para obtener los mejores resultados, seleccione el tamaño más pequeño que tenga el patrón repetido una vez por cuadro.\
   Si todas las cajas tienen una forma irregular y no parecen coincidir con el patrón, utilice el tamaño personalizado para intentar obtener resultados más regulares.
1. <b>Detección de patrones</b>: Coloque los puntos de forma que cada punto esté en la misma posición del motivo. Por ejemplo, en un patrón de tablero de ajedrez en blanco y negro, puede que desee que los puntos estén en el centro de los cuadrados en negro.
1. <b>Región de interés</b>: Seleccione el área del material que desea utilizar para crear el patrón final. El uso de una región más grande disminuirá la cantidad de repetición visible, pero la inclusión de áreas con artefactos o diferencias de iluminación visibles puede aumentar la cantidad de repetición visible.
1. <b>Eliminación de juntas</b>: Ajuste la configuración para minimizar la visibilidad de la unión. <b>El smoothness de corte </b>controla la suavidad de la línea de la unión, mientras que <b>Anchura de fusión </b>difumina la unión entre los azulejos.

Una vez que hayas completado todos los pasos, usa <b>Aplicar</b> para confirmar tus opciones. El filtro <b>Mosaico automático</b> procesará el material para generar un resultado final.
