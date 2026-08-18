---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/embroidery.html"
breadcrumb-title: ''
description: Usa el generador de bordados de Substance 3D Sampler para crear patrones de tejidos bordados y texturas de pespunte para los materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Embroidery
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Bordado
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 0%

---


# Bordado

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-embroidery-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro Bordado le permite convertir rápidamente imágenes en parches bordados. Puede personalizar el aspecto de los parches y utilizar las herramientas de gestión de color para actuar como una máscara para varios materiales.

Las imágenes siguientes muestran el **filtro de bordado** en acción.

![](../../assets/3d-2d-filters-cropped-0035-embroidery-in.jpg)

En la imagen anterior, se ha importado la imagen de origen. Tenga en cuenta que la imagen es opaca y tiene un fondo blanco.

![](../../assets/3d-2d-filters-cropped-0034-embroidery-out.jpg)

En la imagen anterior, el **filtro de bordado** se ha añadido a la pila de capas y ha convertido la imagen de origen en un parche bordado. Tenga en cuenta que, si bien la imagen de origen era opaca, la salida del **filtro de bordado** tiene transparencia.

</td>
</tr>
</table>

## Complemento de bordado Tajima

¿Estás interesado en probar el plugin de bordado Tajima? \
Más información [aquí](../../pipeline-and-integrations/tajima-exporter-plugin.md).

## Parámetros

<b>Parámetros básicos</b>

* <b>Raíz aleatoria</b>:\
  Semilla aleatoria en la que se basan todos los demás parámetros aleatorios de este filtro.
* <b>Imagen</b>: imagen/máscara\
  Seleccione una imagen de su sistema o pinte una máscara personalizada.
* <b>Recuento de colores</b>: 1-8\
  El filtro de bordado intentará dividir las imágenes importadas en colores independientes. Modifique este valor para cambiar el número de colores utilizados.
* <b>Densidad</b>: 80-300\
  Seleccione la densidad de las fibras.
* <b>Diseño</b>: Relleno, Contorno, Relleno + Contorno, Puntada\
  Seleccione el modo de bordado: *Relleno* rellena toda la zona de color, *Contorno* crea un contorno de la zona de color, *Relleno + Contorno* crea ambos en cada zona de color y *Puntada* crea un contorno de puntada superior de la zona de color.
* <b>Relleno/contorno: </b>0-1\
  Cambiar la forma en que se distribuyen las fibras en la zona de color.
* <b>Subproceso</b>:\
  Ajuste el Thickness y la longitud de los subprocesos.
* <b>Áreas suaves: </b>0-1\
  Incluya las zonas de color e impacte en el comportamiento de los hilos.
* <b>Imperfecciones</b>: 0-1\
  Añada imperfecciones al hilo para ayudar a romper el patrón

<b>Color 1</b>

Utilice los controles para ajustar cada zona de color individualmente.

* <b>Rellenar</b>: alternar\
  Hacer visible o invisible la zona de color.
* <b>Height</b>: \
  Desplazar la orientación de las roscas

<b>Fin de la puntada</b>

* <b>Color personalizado:</b>\
  Personalizar el color de todo el bordado
* <b>Rugosidad: </b>0-1\
  Cambie el valor de Rugosidad para que el bordado sea áspero o brillante.
* <b>Metálico: </b>0-1\
  Cambie el valor Metálico para añadir una sensación metálica a las roscas.
* <b>Nivel de Anisotropía: </b>0-1\
  Cambie el nivel de Anisotropía para acentuar la metalidad.

<b>Avanzado</b>

* <b>Intensidad normal</b>: 0-1\
  Ajusta la intensidad de las normales.
* <b>Intervalo de Height:</b> 0-1\
  Ajuste la posición del Height del bordado en el material base.
* <b>Posición del Height:</b> 0-1\
  Ajuste la posición del Height del bordado en el material base.

## Guía de uso

El filtro de bordado puede resultar un poco confuso al principio, pero con solo unos pocos parámetros importantes para empezar, estarás añadiendo parches a tus materiales en apenas tiempo.

>[!NOTE]
>
> Si has usado el filtro [Tejer](weave.md) antes, el filtro Bordado funciona de manera similar.

Para utilizar el filtro Bordado:

1. Añade el filtro Bordado a la pila de capas.
1. Utilice <b>Parámetros básicos > Imagen</b> para agregar una imagen al filtro o una imagen a la pila de capas debajo del filtro Bordado (no en una de las ranuras de entrada). Si una imagen no se agrega a <b>Parámetros básicos > Imagen</b>, el filtro selecciona automáticamente las imágenes de los canales de digitalización si están disponibles.
1. Ajuste <b>Parámetros básicos > Recuento de colores </b> hasta que el equilibrio de color se vea correcto para la imagen. Con un límite de 8 colores, habilite o deshabilite los colores para aislar los colores que necesita.\
   El filtro Bordado funciona mejor con colores planos e imágenes ilustradas.
1. Ajuste otros parámetros para ajustar el aspecto del parche.

Es posible utilizar imágenes transparentes en el filtro Bordado, pero por defecto también afectarán al mapa de opacidad de su material: las partes transparentes de la imagen también harán transparente el material. Para crear un parche con el filtro Bordado y hacer que se asiente en la parte superior de las capas inferiores, utilice el filtro Calcomanía.

1. Crea un filtro de pegatinas.
1. Añada el filtro de bordado a la ranura de entrada del filtro de pegatinas.
1. Siga los pasos normales para ajustar el patrón de bordado.

La capa de pegatina convierte la entrada de bordado en una pegatina, de modo que la transparencia de la capa de bordado indica a la capa de pegatina cómo enmascarar el motivo bordado. Con la capa de pegatinas, también puedes mover el patrón por el material o activar funciones como el mosaico.
