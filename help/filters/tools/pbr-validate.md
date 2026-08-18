---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/tools/pbr-validate.html"
breadcrumb-title: ''
description: Utiliza la herramienta de Validación PBR de Substance 3D Sampler para validar y garantizar que los materiales cumplen los estándares de representación basados en la física.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Tools > PBR Validate
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Validación PBR
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '653'
ht-degree: 0%

---


# Validación PBR

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-pbrvalidate-18-n-d.png)

**En:** Herramientas

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el **filtro de Validaciones PBR** para asegurarte de que los valores de PBR de tu material son correctos. A diferencia de la mayoría de los filtros, el **filtro Validación PBR** no está destinado a ser una parte permanente de la pila de capas; en su lugar, utilízalo para validar tu material y luego elimínalo para que no modifique tu material.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Modo de validación**:\
  Seleccione si desea validar los valores de albedo (color base o difuso), los valores metálicos o los valores metálicos y de albedo. Otros parámetros se actualizarán según esta selección
  * **Modo de validación: Albedo**
    * **Umbral de rango oscuro de Albedo**:\
      Establezca el umbral para los valores oscuros que el filtro debe seleccionar como no válidos.
    * **Mapa de superposición**: alternar\
      Cambiar entre modo de superposición: si se activa, el mapa de color base se superpondrá con los píxeles no válidos.
    * **Ocultar validación en color base**: alternar\
      Ocultar la información de validación del canal de color base.
  * **Modo de validación: Metal**
    * **Rango de reflejo de metal**:\
      Defina el rango de valores de reflectancia que el filtro debe seleccionar como no válido.
    * **Mapa de superposición**: alternar\
      Cambiar entre modo de superposición: si se activa, el mapa de color base se superpondrá con los píxeles no válidos.
    * **Ocultar validación en color base**: alternar\
      Ocultar la información de validación del canal de color base.
  * **Modo de validación: Combinado**
    * **Umbral de rango oscuro de Albedo**:\
      Establezca el umbral para los valores oscuros que el filtro debe seleccionar como no válidos.
    * **Rango de reflejo de metal**:\
      Defina el rango de valores de reflectancia que el filtro debe seleccionar como no válido.
    * **Ocultar validación en color base**: alternar\
      Ocultar la información de validación del canal de color base.

## Guía de uso

La **Validación PBR** **filter** ayuda a evitar problemas con los valores metálicos y de albedo de un material. Para entender cómo funciona el **filtro Validación PBR**, primero debes hablar un poco sobre lo que es la PBR.

## ¿Qué es la PBR?

PBR significa &quot;representación basada en la física&quot; y es un método de representación de objetos y materiales mediante la representación de las propiedades físicas de una superficie con varios canales. La PBR se creó para representar con mayor precisión el mundo real y físico que los métodos de sombreado y representación anteriores.

En el mundo real, hay algunos colores y combinaciones de propiedades que son imposibles o increíblemente raras. Por ejemplo, casi nada en el mundo real tiene un albedo blanco puro o negro puro o un color base.

Así que, dado que la PBR está tratando de representar valores del mundo real, y dado que algunos valores no aparecen o raramente aparecen en el mundo real, es posible tener valores de PBR &#39;incorrectos&#39;. Esto es lo que el **filtro Validación PBR** está diseñado para encontrar.

## Cómo usar la Validación PBR

Para usar **Validación PBR**, añádela a la parte superior de la pila de capas. Deberías ver un cambio drástico en el aspecto de tu material, esto se debe a que el **filtro Validación PBR** muestra los resultados de la validación en el canal de albedo.

El filtro utiliza una escala de rojo a verde para mostrar dónde se encuentran los errores. Si todo el material es verde, no hay nada malo con los colores o los valores metálicos del material. Sin embargo, si ve áreas amarillas, naranjas o rojas, hay problemas con el material.

Si está utilizando el modo de validación de color, las áreas que no sean verdes generalmente significan que hay valores en el color base que están cerca de ser completamente negro o completamente blanco. Usa filtros de ajuste como **Matiz/Saturación** o **Brillo/Contraste** para ajustar los valores de tu canal de color hasta que el **filtro Validación PBR** no muestre más errores.

Si está utilizando el modo de validación de metal, las áreas no verdes generalmente significan que la combinación de su color, rugosidad y mapas metálicos en esas áreas no es realista. Esto suele ocurrir con valores de color oscuro, 0 rugosidad y 1 valor metálico. Para corregir estos errores, puede modificar los valores de rugosidad, metálico o de color hasta que **filtro Validación PBR** no muestre más errores.
