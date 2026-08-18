---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/hdri-tools/sphere-light.html"
breadcrumb-title: ''
description: Utilice la herramienta Esfera clara de Substance 3D Sampler para añadir fuentes de luz esférica a entornos HDRI para conseguir efectos de iluminación puntual.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Sphere Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luz de esfera
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---


# Luz de esfera

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-spherelight-18-n-d.png)

**En:** Herramientas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Añade una luz de esfera a tu entorno.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

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
* **Exposición (VE)**: 0-10\
  Ajusta la exposición o el brillo de la luz.
* **Radio de esfera**: 0-1\
  Ajusta el tamaño de la luz.
* **Modo de posición**:\
  Cambie el método utilizado para determinar la posición de las luces. Los parámetros de la sección **Coordenadas de posición** cambiarán en función de la selección.

**Coordenadas de posición**

Los parámetros disponibles dependen de la selección realizada para **Parámetros básicos > Modo de posición**. Si se selecciona **Distancia desde origen**, están disponibles los siguientes parámetros:

* **Distancia desde origen**: 0-20\
  Ajusta la distancia de la luz desde la cámara.
* **Posición de la cámara**: 0-1\
  Ajuste la posición relativa de la cámara a la luz en los ejes X, Y y Z.

Si se selecciona **Posición del mundo**, están disponibles los siguientes parámetros:

* **Vector Arriba**:\
  Cambiar la dirección hacia arriba.
* **Posición de mundo de esfera**: -2 a 2\
  Ajuste la posición de la luz de la esfera en los ejes X, Y y Z.
* **Distancia desde origen**: 0-20\
  Ajusta la distancia de la luz desde la cámara.
* **Posición de la cámara**: 0-1\
  Ajuste la posición relativa de la cámara a la luz en los ejes X, Y y Z.

**Forma**

* **Dureza de esfera**: 0-1\
  Suavizar o endurecer los bordes de la luz de la esfera
* **Sombreado**:\
  Cambia el degradado de la exposición de la luz en función de los diferentes estilos de luz del mundo real. Con **Luz de Sombreado** seleccionada, aparecen parámetros adicionales:
  * **Posición del Mundo Luz del Sombreado**: -1 a 1\
    Modificar la posición del área sombreada en la luz
  * **Transparencia de Penumbra**: 0-1\
    Ajuste el nivel de opacidad del área sombreada de la luz.

**Fondo**

* **Gama de fondo**:\
  Seleccione el sistema de color utilizado para determinar la gamma de fondo.
