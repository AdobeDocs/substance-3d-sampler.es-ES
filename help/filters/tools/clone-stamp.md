---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/clone-stamp.html"
breadcrumb-title: ''
description: Utiliza la herramienta Tampón de clonar de Substance 3D Sampler para clonar y pintar áreas de textura para una edición y reparación de materiales perfectas.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Clone Stamp
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Tampón de clonar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

---


# Tampón de clonar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-clonestamp-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

La herramienta **Tampón de clonar** te ayuda a duplicar o parchear manualmente partes de tu material. Esto es útil para arreglar costuras o eliminar errores de su material. El **filtro Tampón de clonar** es una de las herramientas disponibles en la barra lateral izquierda.

En las imágenes que aparecen a continuación se muestra el **Tampón de clonar** que se está utilizando para eliminar los escombros de un material de nieve.

![](../../assets/3d-2d-filters-cropped-0049-clone-stamp-in.jpg)

En la imagen de arriba, el material de nieve incluye una serie de ramitas y otros escombros dispersos alrededor.

![](../../assets/3d-2d-filters-cropped-0048-clone-stamp-out.jpg)

La herramienta **Tampón de clonar** se usa para quitar algunas ramitas y reemplazarlas con nieve limpia.

</td>
</tr>
</table>

## Tutorial sobre Tampón de clonar

## Parámetros

<b>Parámetros básicos</b>

* <b>Expandir máscara</b>: 0-1\
  Ajuste la distancia alrededor del área pintada en la que el filtro intentará hacer coincidir el material subyacente.
* <b>Fusión de transición</b>: 0-1\
  Suaviza el borde del área clonada para que se mezcle mejor con el material subyacente.
* <b>Desenfocar máscara</b>: 0-1\
  Ajuste la cantidad de detalle del borde del tampón de clonar. Si se aumenta este valor, los bordes del área clonada tendrán un aspecto más blob.
* <b>Mantener proporción</b>: alternar\
  Si se desactiva, permite ajustar las proporciones del área estampada.
  * <b>Horizontal</b>: 0-2
  * <b>Vertical</b>: 0-2
* <b>Rotación</b>: De -180 a 180\
  Gire el área estampada.
* <b>Voltear horizontal</b>: alternar\
  Reflejar el área estampada a lo largo de un eje horizontal.
* <b>Voltear verticalmente</b>: alternar\
  Reflejar el área estampada a lo largo de un eje vertical.

<b>Fusión de transición</b>

Utilice los controles de fusión de fundido para ajustar individualmente la fusión de fundido para cada canal del material.

<b>Avanzado</b>

* <b>Intensidad normal</b>: 0-2\
  Ajuste la intensidad de las normales en el área estampada.
* <b>Posición de origen</b>: \
  0-1: Ajuste la posición de origen horizontal.\
  0-1: Ajuste la posición de origen vertical.
* <b>Posición de destino</b>:\
  0-1: Ajuste la posición de destino horizontal.\
  0-1: Ajuste la posición de destino vertical.
* <b>Modo de segmentación</b>: menú desplegable\
  Activar o desactivar el mosaico.

## Guía de uso

Haz clic en la **herramienta Tampón de clonar** para crear una nueva capa de filtro Tampón de clonar en la parte superior de la pila de capas. También puedes añadir un filtro Tampón de clonar con el botón **Añadir una capa** en el **panel Capas**.

La creación de una capa de filtro Tampón de clonar abre automáticamente la **vista 2D** en el **área de visualización**. Aparece una **Barra de herramientas** en la parte superior de la **vista 2D** cuando se selecciona la capa Tampón de clonar.

![](../../assets/alchemist-2020-2-clone.gif){width="300px"}

Para empezar a usar la herramienta Tampón de clonar, haz clic y arrastra el cursor sobre el área problemática en la **vista 2D**. El material comenzará a actualizarse automáticamente en función de la fuente. Las áreas en las que use la **herramienta Tampón de clonar** aparecen resaltadas.

## Barra de herramientas

<table>
<tr style="border: 0;">
<td width="16.67%" style="border: 0;" valign="top">

![](../../assets/CloneStampBrushToolbar.png)

</td>
<td width="83.33%" style="border: 0;" valign="top">

Mientras está seleccionada la capa Tampón de clonar, aparece una barra de herramientas en la vista 2D con controles adicionales.

* Selecciona la <b>herramienta Pincel </b> para añadir a la máscara o la <b>herramienta Borrar </b> para quitar de la máscara.
* Defina el tamaño de la herramienta seleccionada actualmente.
* Acceder a controles adicionales:
  * <b>Mosaico de pincel</b>: \
    Alternar el mosaico de pinceles X e Y.
  * <b>Superposición:</b>\
    Alterne si la superposición se muestra al pasar el puntero sobre la vista 2D.
* Ver controles de vista 2D.

</td>
</tr>
</table>

>[!NOTE]
>
> Al igual que con otras barras de herramientas de Ventana gráfica, puede arrastrar el controlador situado en la parte superior de la barra de herramientas para cambiar la posición de la barra de herramientas dentro de la ventana gráfica, hacer doble clic en el controlador para cambiar entre el modo vertical y horizontal o utilizar el doble cursor para ocultar o expandir la barra de herramientas.

## Selección de origen

Utilice Ctrl+Clic en la vista 2D para añadir un nuevo origen. Al agregar un nuevo origen, se creará un sello adicional bajo la capa Tampón de clonar en el <b>panel Capas</b>. Puede controlar cada sello de forma individual.

>[!NOTE]
>
> Por lo general, es una buena idea tratar de evitar tener el punto de origen cerca del área sobre la que está clonando. Si el punto de origen está cerca del área problemática, es posible clonar el área problemática.

## Mét. abreviados

| Acción | Windows + Linux | MacOs |
| --- | --- | --- |
| Aumentar tamaño de pincel | ] o Ctrl + Rueda del ratón | ] o Cmd + Rueda del ratón |
| Reducir tamaño de pincel | [ o Ctrl + Rueda del ratón | [ o Cmd + Rueda del ratón |
| Establecer el origen | Ctrl + clic izquierdo | Cmd + clic izquierdo |
