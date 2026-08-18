---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/hdri-tools/line-light.html"
breadcrumb-title: ''
description: Utilice la herramienta Luz de línea de Substance 3D Sampler para añadir fuentes de luz lineal a entornos HDRI para un control de iluminación preciso.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Line Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luz de línea
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '564'
ht-degree: 0%

---


# Luz de línea

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-linelight-18-n-d.png)

**En:** Herramientas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Añade una **luz de línea** a la luz ambiental.

Las imágenes siguientes muestran cómo puedes usar una **luz de línea** para ajustar la iluminación de tu entorno.![](../../assets/3d-2d-filters-cropped-0017-line-light-in.jpg)

La imagen de arriba muestra una esfera sin modificaciones a la luz ambiental.

![](../../assets/3d-2d-filters-cropped-0016-line-light-out.jpg)

Después de agregar una **luz de línea**, el aspecto de la esfera ha cambiado notablemente.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Exposición (VE)**: 0-10\
  Ajusta la exposición o el brillo de la luz.
* **Modo de color de forma**:\
  Seleccione el método que desea utilizar para determinar el color de la luz. Los parámetros disponibles cambiarán en función de esta selección.
  * **Temperatura (Kelvin)**
    * **Temperatura**: 1000 — 27000\
      Ajusta la temperatura de la luz.
  * **RGB**
    * **Color**: selección de color\
      Seleccione el color de la luz.
  * **Entrada de imagen**
    * **Entrada de imagen de forma**: imagen/pincel\
      Importe una imagen para utilizarla como color. Puedes usar la herramienta Pincel para pintar directamente en la **vista 2D**, pero esto puede tener resultados impredecibles con este filtro.
  * **Fondo de muestra**
    * El fondo de muestra no ofrece nuevos parámetros, sino que basa el color de la luz en los valores del fondo.
* **Modo de posición**:\
  Cambie el método utilizado para determinar la posición de las luces. Los parámetros de la sección **Coordenadas de posición** cambiarán en función de la selección. Con **Posición del mundo** seleccionado, los controladores desaparecerán de la **vista 2D**, en su lugar, utilice los parámetros de **Coordenadas de posición** para modificar la posición de la luz.

**Forma**

* **Rotación de línea**: 0-1\
  Rota la luz
* **Thickness de línea**: 0-1\
  Ajuste el thickness de la línea que forma la luz.
* **Patrón**:\
  Cambiar la forma de la línea
* **Dureza del motivo**: 0-1\
  Suaviza los bordes de la luz
* **Modo UV De Patrón**:\
  Modifique el patrón en el que se basa la luz. **Stretch** amplía toda la forma para que coincida con los puntos finales de línea. **Solo estirar el medio** estira el centro de la forma, manteniendo los extremos de la línea sin distorsionar. **Repetir + Espaciado** crea sellos de la forma a lo largo de la longitud de las líneas y agrega un parámetro adicional para administrar el espaciado:
  * **Espaciado de repetición de motivo**: 0-1\
    Ajustar el ancho del espaciado entre instancias de formas

**Coordenadas de posición**

Los parámetros disponibles dependen de la selección realizada para **Parámetros básicos > Modo de posición**. Si se seleccionan **Suelo/techo** o **Distancia desde origen**, están disponibles los siguientes parámetros:

* **Height absoluto de línea**: 0-1\
  Cambia la distancia a la que está la luz de la cámara.
* **Posición de la cámara**: 0-1\
  Ajuste la posición relativa de la cámara a la luz en los ejes X, Y y Z.

Si se elige **Posición del mundo** en **Parámetros básicos > Modo de posición**, están disponibles los siguientes parámetros:

* **Vector Arriba**:\
  Cambiar la dirección hacia arriba.
* **Posición Mundial Punto 1**: -2 a 2\
  Ajuste la posición del primer punto de la línea en los ejes X, Y y Z.
* **Posición Mundial Punto 2**: -2 a 2\
  Ajuste la posición del segundo punto de la línea en los ejes X, Y y Z.
* **Posición de la cámara**: 0-1\
  Ajuste la posición relativa de la cámara a la luz en los ejes X, Y y Z.

**Fondo**

* **Mostrar cuadrícula de tierra**: alternar\
  Muestra u oculta la cuadrícula de tierra.
* **Habilitar recorte de tierra**: alternar\
  Seleccione si la luz puede pasar a través del suelo o no. Si se habilita, aparecerá el siguiente control:
  * **Height de tierra**: -2 a 2\
    Ajuste el height del suelo para reducir la luz.
* **Gama de fondo**:\
  Seleccione el sistema de color utilizado para determinar la gamma de fondo.
