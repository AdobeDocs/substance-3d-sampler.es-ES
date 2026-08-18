---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/embossing.html"
breadcrumb-title: ''
description: Utilice el generador de relieve de Substance 3D Sampler para crear patrones en relieve y efectos de relieve de superficie elevados en materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Embossing
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Relieve
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '503'
ht-degree: 0%

---


# Relieve

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-embossing-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Relieve de texto o motivos en los materiales.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Tamaño de relieve**: 0-1\
  Cambiar el tamaño de cada instancia
* **Distancia de relieve**: 0-1\
  Cambiar el thickness de las líneas en relieve
* **Selección de motivo**:\
  Seleccione el patrón en relieve. Desde aquí, puede seleccionar la opción de relieve de texto o un motivo personalizado.
* **Mosaico De Motivo X**: 1-64\
  Cambiar el número de instancias en el eje X
* **Mosaico De Motivo Y**: 1-64\
  Cambiar el número de instancias en el eje Y

**Relieve**

* **Usar relieve de borde**: alternar\
  Alternar si desea grabar en relieve el borde del motivo elegido
* **Inversión de relieve de borde**: alternar\
  Invertir el height del relieve del borde
* **Intensidad de relieve del borde**: 0-1\
  Cambio de la intensidad del efecto de relieve
* **Usar relleno en relieve**: alternar\
  Alternar si se va a grabar en relieve el relleno del motivo elegido
* **Invertir relieve de relleno**: alternar\
  Invertir el height del efecto de relleno en relieve
* **Intensidad de relieve de relleno**: 0-1\
  Cambio de la intensidad del efecto de relieve

**Patrón**

* **Usar color**: alternar\
  Alterne entre añadir o no color al área en relieve\
  Cuando se activa **Usar color**, aparecerá un parámetro **Color** adicional para ajustar el color.
* **Máscara de motivo** **Distancia**: 0-1\
  Cambiar el tamaño de la máscara utilizada para aplicar color al área en relieve
* **Contraste de máscara de motivo**: 0-1\
  Ajusta el contraste de la máscara. Al reducir el contraste, los bordes de la máscara aparecen más borrosos.
* **Usar azulejo de motivo**: alternar\
  Active esta opción para estructurar el motivo y desactive esta opción para que solo haya una instancia. Cuando el patrón no está en mosaico, las opciones de **Mosaico de motivo** no aparecerán en la sección **Parámetros básicos**.
* **Rotación de motivo**: 0-1\
  Girar el motivo
* **Desplazamiento de motivo**: 0-1\
  Desplace cada fila del motivo de la fila anterior.
* **Usar rugosidad de motivo**: alternar\
  Active esta opción para anular la rugosidad del material subyacente con un valor de rugosidad personalizado siempre que aparezca el efecto de relieve.\
  Cuando se habilita, aparece un control **Rugosidad de motivo** para establecer la rugosidad.
* **Usar motivo metálico**: alternar\
  Active esta opción para anular los valores metálicos del material subyacente con un valor metálico personalizado siempre que aparezca el efecto de relieve.\
  Cuando se habilita, aparece un control **Pattern Metallic** para establecer la rugosidad.

**Texto**: esta sección solo aparece si **Selección de motivo** en **Parámetros básicos** está establecido en **Texto**

* **Selección de fuente**:\
  Seleccionar un tipo de letra
* **Texto**: campo de texto\
  Escriba el texto que desea grabar en relieve
* **Tamaño de texto**: 0-1\
  Ajustar el tamaño de fuente

**Borrador**

* **Borrador normal**: 0-1
* **Oclusión ambiental del borrador**: 0-1
* **Opacidad del borrador**: 0-1

**Parámetros avanzados**

Estos parámetros permiten ajustar los valores de todo el material.

* **Luminosidad**: 0-1
* **Contraste**: -1 a 1
* **Cambio De Tono**; 0-1
* **Saturación**: 0-1
* **Intensidad Normal**; 0-1

## Guía de uso

Añada el filtro Relieve a la parte superior de la pila de capas y comience a ajustar los parámetros.

Los parámetros más importantes son generalmente **Parámetros básicos > Selección de motivo** para modificar el motivo que utilizará el filtro y **Motivo > Usar motivo** para activar y desactivar el mosaico.
