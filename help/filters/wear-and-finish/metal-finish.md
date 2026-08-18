---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/wear-and-finish/metal-finish.html"
breadcrumb-title: ''
description: Utilice el filtro Acabado metálico de Substance 3D Sampler para aplicar diversos acabados y texturas de superficies metálicas a sus materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Metal Finish
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Acabado Metálico
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '624'
ht-degree: 0%

---


# Acabado Metálico

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/metal-finish-filter-icon.png.img.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Convierte tu material en un metal con varios acabados y estilos.

*Una materia prima metálica se convierte en una superficie de metal cepillado con el filtro **Acabado metálico.***

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0023-metal-finish-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0022-metal-finish-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Modificar sólo metálico**: alternar\
  Cuando está activado, este filtro limitará sus cambios en el canal metálico.
* **Modo de color Metal**:\
  Seleccione un color basado en un metal existente o elija el suyo propio. Con **Color personalizado** seleccionado, aparecerá el siguiente control:
  * **Color de metal**: selección de color\
    Selecciona un color personalizado para tu acabado metálico.
* **Tipo de fin**:\
  Seleccione un estilo para aplicarlo al metal. Cada estilo tiene diferentes parámetros que le permiten ajustar su apariencia. Pueden aparecer los siguientes parámetros:
  * **Intensidad**: 0-1\
    Ajusta la intensidad del acabado elegido.
  * **Escala**: 0-1\
    Modifique la escala del motivo que guía al acabado elegido.
  * **Rugosidad**: 0-1\
    Controlar el valor de rugosidad del metal.
  * **Escala de cuentas**: 0-1\
    Disponible para **Sandblasted**. Defina el tamaño de los granos utilizados para crear el efecto de chorro de arena.
  * **Pulido**: 0-1\
    Disponible para **fundir**. Ajusta la cantidad de pulido que suaviza las partes más altas del material.
  * **Patrón**:\
    Disponible para **Rectificado**. Defina el patrón utilizado por la amoladora.
  * **Detalles del Relieve**: 0-1\
    Disponible para **Raw**. Ajuste la intensidad normal.
  * **Orientación**: 0-1\
    Disponible para **Brushed**. Cambie la dirección del efecto del pincel.
  * **Longitud del pincel**: 0-1\
    Disponible para **Brushed**. Cambie la longitud de los trazos utilizados para crear el efecto de pincel.
  * **Pinceles**: 0-1\
    Disponible para **Galvanizado**. Superponga un aspecto de pincel sobre el acabado galvanizado.

**Máscara**

* **Usar máscara personalizada**: alternar\
  Activar o desactivar el uso de una máscara personalizada. Si se ha activado, aparecerán los siguientes parámetros:
  * **Máscara**: imagen/pincel\
    Seleccione una imagen para utilizarla como máscara o utilice el pincel para pintar una máscara personalizada directamente en la vista 2D.
  * **Máscara personalizada - Desenfocar**: 0-1\
    Desenfoca la máscara.
  * **Máscara personalizada - Invertir**: alternar\
    Invierte la máscara.

**Parámetros avanzados**

* **Color base**: alternar\
  Defina si el canal de color base se ve afectado por el filtro.
* **Metálico**: alternar\
  Defina si el canal metálico se ve afectado por el filtro.
* **Rugosidad**: alternar\
  Defina si el canal de rugosidad se ve afectado por el filtro.
* **Specular level**: alternar\
  Controlar si el canal de specular level se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Specular level** **- Valor**: 0-1\
    Ajuste el valor del canal de specular.

>[!NOTE]
>
> Actualmente hay un error conocido por el que el control **Specular level** puede desaparecer si está deshabilitado sin control para volver a habilitarlo. Si pierde el control **Specular level** pero lo necesita de vuelta, puede usar la acción de deshacer (ctrl + z o cmd + z en macOS) para deshacer la deshabilitación del botón deslizante.

* **Normal**: alternar\
  Establezca si el filtro afecta al canal normal. Si se habilita, aparece un control adicional:
  * **Intensidad normal**: 0-1\
    Ajuste la intensidad de la modificación normal mediante el filtro.
* **Height**: alternar\
  Establezca si el canal de height se ve afectado por el filtro.
* **Emisor**: alternar\
  Establezca si el canal de emisión se ve afectado por el filtro. Si se habilita, aparece un control adicional:
  * **Emisor - Color**: selección de color\
    Defina el color del canal de emisión.
* **Oclusión de ambiente**: alternar\
  Establezca si el canal de oclusión ambiente se ve afectado por el filtro. Si se habilita, aparecen los siguientes controles adicionales:
  * **Oclusión ambiente - Intensidad**: 0-1\
    Ajuste la intensidad del AO generado.
  * **Oclusión de ambiente** **- Radio**: 0-1\
    Ajuste el radio del efecto AO.
* **Opacidad**: alternar\
  Establezca si el filtro afecta al canal de opacidad. Si se habilita, aparece un control adicional:
  * **Opacidad - Valor**: 0-1\
    Cambiar la opacidad del material.
