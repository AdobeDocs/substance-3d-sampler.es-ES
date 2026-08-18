---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/crop-tool.html"
breadcrumb-title: ''
description: Utiliza la herramienta Recortar de Substance 3D Sampler para recortar y cambiar el tamaño de las texturas y las capas de materiales con un control preciso de las dimensiones.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > Crop tool
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Herramienta Recortar
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '707'
ht-degree: 0%

---


# Herramienta Recortar

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-crop-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa la **herramienta Recortar** para ajustar el recorte de tu imagen o material. La **herramienta Recortar** funciona de manera muy similar a la **herramienta Transformar**. Con la **herramienta Transformar**, los cambios realizados en el cuadro de transformación se comportan de una a una con la imagen subyacente, por lo que al aumentar la escala del cuadro Transformar se aumenta el tamaño de la imagen subyacente. Con la **herramienta Recortar**, esta relación se invierte, al aumentar la escala del cuadro Recortar se reduce el tamaño de la imagen subyacente. Por esta razón, al usar la **herramienta Recortar**, puede ser útil configurar la **vista 2D** para que muestre las entradas de capa, en lugar de las salidas de material predeterminadas.

La **herramienta Recortar** es útil para realizar ajustes en imágenes que tienen proporciones de aspecto no estándar. Por ejemplo, puede usar la herramienta Recortar para ajustar la escala de una imagen importada mediante los parámetros Tamaño de entrada en el **panel Propiedades**.

>[!NOTE]
>
> Ten en cuenta que la **herramienta Recortar** puede funcionar en imágenes o materiales. Si existe una imagen o un canal de digitalización en la pila de capas en la **capa Recortar**, el **filtro Recortar** se aplicará al canal Digitalizar. Si no existe ninguna imagen o canal de digitalización, el **filtro Recortar** modificará el material.

En las imágenes siguientes puedes ver la **herramienta Recortar** en acción.

![](../../assets/3d-2d-filters-cropped-0047-crop-in.jpg)

Tenga en cuenta que la vista 2D está configurada para mostrar Entradas de capa de modo que los controladores de la **vista 2D** muestren qué área de la entrada se convertirá en la salida.

![](../../assets/3d-2d-filters-cropped-0046-crop-out.jpg)

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Tamaño de entrada**: 0-8192\
  Ajuste el tamaño de la entrada en píxeles en los ejes X e Y.

**Parámetros avanzados**

* **Filtrado**:\
  Seleccione el método de filtrado aplicado a los píxeles redimensionados. El filtrado bilineal desenfoca los píxeles entre sí, mientras que el filtro Más cercano mantiene los bordes de los píxeles.
* **Transformación de recorte**: 0-1\
  Modifique los valores de matriz de la transformación. La edición de estos valores puede proporcionar un control más preciso sobre la rotación y la escala, así como sesgar los controles de recorte.
* **Desplazamiento de recorte**: 0-1\
  Desplazar el recorte desde la posición inicial.

## Guía de uso

>[!NOTE]
>
> El filtro Recortar tiene su propia resolución, recortará y generará la resolución adecuada según el material recortado o la imagen. Para mantener los mejores resultados, coloque las capas anteriores en Entrada máxima y utilice una Escala superior para ampliar los resultados finales.

Haga clic en la **herramienta Recortar** para agregar una nueva capa de filtro Recortar a la parte superior de la pila de capas.

Al crear o seleccionar una capa de filtro Recortar, se abre automáticamente la **vista 2D**. Con la capa Recortar seleccionada, aparece una barra de herramientas en la parte superior de la **vista 2D**.

## Funcionalidad

>[!NOTE]
>
> El filtro Recortar realiza la inversión del movimiento, la escala o la rotación que se solicita. Si considera que el filtro Recortar no es correcto, es posible que el filtro Transformar le resulte más útil.

### Mover

Para mover la capa:

1. Pase el ratón por encima del cuadro de transformación
1. El cursor se convertirá en cuatro flechas
1. Haga clic y arrastre para mover el cuadro de transformación.

### Escala

Para escalar la capa:

1. Pase el ratón sobre uno de los controles situados en el borde o en la esquina del cuadro de transformación
1. El cursor se convertirá en cuatro flechas.
1. Haga clic y arrastre para escalar el cuadro de transformación.

>[!NOTE]
>
> Los controles situados en la esquina del cuadro de transformación le permitirán escalar en dos dimensiones a la vez, mientras que los controles situados en el borde del cuadro de transformación le limitarán a escalar en una dimensión.

### Rotar

Para rotar la capa:

1. Coloque el puntero del ratón fuera del cuadro de transformación, pero dentro de la **vista 2D**.
1. Aparecerá una pequeña flecha horizontal junto al cursor.
1. Haga clic y arrastre para rotar el cuadro de transformación.

>[!NOTE]
>
> Puede cambiar el centro de rotación arrastrando el círculo pequeño situado en el centro del cuadro de transformación. El cuadro de transformación siempre gira alrededor de este círculo.

## Barra de herramientas

![](../../assets/transform-toolbar.png){width="200px"}

La barra de herramientas contiene los siguientes métodos abreviados:

* Hazlo cuadrado: Ajuste la escala de la transformación actual para que sea cuadrada.
* Rotación +90° (a la derecha): rotación de 90° hacia la derecha.
* Rotación -90° (a la izquierda): rotación de 90° a la izquierda.
* Restablecer centro de rotación: Restablezca el centro de rotación en el centro del cuadro Transformar.
* Restablecer transformación: Restablezca la herramienta Transformar a su posición predeterminada.
