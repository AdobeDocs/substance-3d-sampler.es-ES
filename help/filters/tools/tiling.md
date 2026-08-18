---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/tools/tiling.html"
breadcrumb-title: ''
description: Utilice la herramienta Mosaico de Substance 3D Sampler para crear patrones de mosaico perfectos a partir de texturas para superficies de materiales repetibles.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Tiling
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Mosaico
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '596'
ht-degree: 0%

---


# Mosaico

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-tiling-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el **filtro Mosaico** para que tu material sea apto para mosaicos. El filtro **Hacer que el azulejo** también hace que el material sea en mosaico, pero cada filtro funciona de una manera diferente. Si crees que el **filtro Mosaico** no funciona para ti, prueba el **filtro Mosaico**.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Mostrar costura**: alternar\
  Elija si desea mostrar la costura
* **Usar máscara**: alternar\
  Si está activada, puede crear una máscara personalizada para controlar la ubicación de la unión
  * **Máscara**: imagen/pincel\
    Importa una imagen para usarla como máscara o usa el pincel para pintar una máscara directamente en la **vista 2D**

**Edge**

* **Detectar bordes**: alternar\
  Alterne la detección de bordes en función de los canales de material para crear una transición más orgánica entre las capas de material. Si se activa, aparecerán los siguientes parámetros adicionales:
  * **Usar umbral por canal**: alternar\
    Si está activado, aparecen parámetros adicionales para ajustar el umbral de cada canal de forma individual.
    * **Color base del umbral**: 0-1
    * **Umbral normal**: 0-1
    * **Height de umbral**: 0-1
  * **Umbral**: 0-1\
    Ajuste el valor de umbral utilizado para encontrar la unión.
  * **Desenfocar**: 0-1\
    Desenfocar el área alrededor de la costura
  * **Smoothness**: 0-2\
    Ajusta el smoothness de la costura. Esto puede ayudar a evitar artefactos
  * **Resolución de cuadrícula**: 1-11\
    Ajuste la resolución de la rejilla en la que se dibuja la unión. Una resolución más baja puede mejorar el rendimiento, pero disminuye la calidad de la costura
  * **Usar color base**: alternar\
    Cambiar si la información de color base se tiene en cuenta en la generación de costuras
  * **Usar normal**: alternar\
    Cambiar si la información normal se tiene en cuenta en la generación de juntas
  * **Usar Height**: alternar\
    Cambiar si la información de height se tiene en cuenta en la generación de juntas
  * **Desplazamiento de corte**: 0-0,5\
    Ajuste el desplazamiento de la unión en los ejes X e Y

**Parámetros avanzados**

* **Transformar**: 0-2\
  Ajuste los valores de transformación de matriz. Aumente los valores X y W para ajustar el grado de superposición existente entre el material subyacente y el superpuesto.
* **Desplazamiento**: 0-1\
  desplazar el material en los ejes X e Y
* **Filtrado**:\
  Seleccione el método de filtrado que desee utilizar en los píxeles redimensionados. El filtrado bilineal desenfoca los píxeles, mientras que el filtro más cercano mantiene el borde duro entre los píxeles.
* **Tamaño de entrada**: 0-8192\
  Ajuste el tamaño de la entrada en píxeles en los ejes X e Y.

## Guía de uso

El **filtro de mosaico** funciona en dos pasos:

1. Ajusta la escala y desplaza el material para generar una superposición.
1. Luego varía el borde superpuesto para ocultar la costura.

Por lo tanto, para usar el **filtro Mosaico**, ajustar estas dos partes del proceso puede obtener los mejores resultados.

1. Agregue el **filtro Mosaico** a la parte superior de la pila de capas
1. Utilice los controles para transformar el material de modo que haya suficiente superposición para ocultar la costura.
   1. Escalar el material puede resultar útil para crear una superposición, pero también puede provocar la pérdida de detalles.
1. Ajuste los parámetros en la sección **Edge** para ajustar la unión.

Para algunos materiales que usan el **filtro de baldosas** por sí solo, se producirán artefactos o problemas a lo largo de la costura. En este caso, es recomendable utilizar otros filtros, como **Tampón de clonar**, para corregir los problemas de costura y mosaico.

Es una buena práctica trabajar en el mosaico del material al principio del proceso de creación del material - tan pronto como se añade un elemento no mosaico al material, es una buena idea asegurarse de que se mosaicos antes de seguir trabajando. Los filtros de Sampler están diseñados para que no rompan los materiales de mosaico. Esto significa que, una vez que los azulejos de material subyacente, puede seguir trabajando con filtros y los materiales incluidos de Sampler y su material seguirá siendo azulejo.
