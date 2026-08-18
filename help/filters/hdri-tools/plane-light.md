---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/hdri-tools/plane-light.html"
breadcrumb-title: ''
description: Utilice la herramienta Luz plana de Substance 3D Sampler para añadir fuentes de luz planas a entornos HDRI para efectos de iluminación de área.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Plane Light
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Luz plana
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '502'
ht-degree: 0%

---


# Luz plana

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-planelight-18-n-d.png)

**En:** Herramientas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Añada una luz con la forma de un plano plano a su entorno.

![](../../assets/3d-2d-filters-cropped-0002-plane-light-out.jpg)

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

* **Escala De Plano**; 0-1\
  Ajusta la escala de la luz.
* **Tamaño de plano**: 0-1\
  Ajuste las dimensiones de la luz en los ejes X e Y.
* **Rotación de plano**: 0-1\
  Ajuste la rotación de la luz a lo largo de los ejes X, Y y Z.
* **Patrón**:\
  Seleccione la forma de la luz.
* **Dureza del motivo**: 0-1\
  Suaviza o desenfoca los bordes de la luz
* **Modo UV De Patrón**:\
  Elija si las transformaciones estiran toda la forma o solo el centro de la forma para mantener los detalles de los bordes y las esquinas.

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
