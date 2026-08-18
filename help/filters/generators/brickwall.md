---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/generators/brickwall.html"
breadcrumb-title: ''
description: Usa el generador de paredes de ladrillo en Substance 3D Sampler para crear patrones realistas de paredes de ladrillo y texturas de mampostería para materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Brickwall
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Pared De Ladrillo
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '558'
ht-degree: 0%

---


# Pared De Ladrillo

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-brickwall-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

DescripciónEl filtro Pared (Brickwall) genera un patrón de ladrillo basado en las capas inferiores. Esto es útil para crear paredes de ladrillo (como su nombre indica) pero también pisos, o en cualquier otro lugar se utilizan ladrillos.

En las imágenes siguientes, un material de arcilla se convierte en una pared de ladrillo con el filtro **Brickwall.**

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0053-brickwall-in.jpg){width="200px"}

</td>
<td style="border: 0;" valign="top">

![](../../assets/3d-filters-cropped-0052-brickwall-out.jpg){width="200px"}

</td>
</tr>
</table>

</td>
</tr>
</table>

## Parámetros

**Ajustes preestablecidos**

Seleccione entre una serie de ajustes preestablecidos para emular rápidamente un estilo específico.

**Parámetros básicos**

* **Raíz aleatoria**: número aleatorio\
  Valor aleatorio utilizado para determinar otros valores aleatorios en este filtro.\
  Haga clic en el número para obtener un nuevo valor aleatorio. Cuando se haya seleccionado un valor aleatorio, haga clic en el nombre del parámetro para restablecer el valor a 0.
* **Ladrillo**:\
  Combinar ladrillos en función del estilo seleccionado
* **Tipo de ladrillo**:\
  Seleccionar el estilo de ladrillo
* **Mosaico**: 1-25\
  Cambie la cantidad de mosaico en los ejes X e Y.
* **Desplazamiento**: 0-1\
  Modifique el desplazamiento de cada fila de ladrillos de la fila anterior.
* **Usar color personalizado**: alternar\
  Combinar ladrillos en función del estilo seleccionado

**Mezcla**

* **Modo de mezcla**:\
  Cambiar la organización de los ladrillos. El uso de un **modo de mezcla** crea un segundo conjunto de ladrillos que se pueden controlar independientemente del conjunto base.\
  Con **Modo de mezcla** establecido en **Ninguno**, no aparecerá ningún otro parámetro en esta sección.
* **Tipo de ladrillo 2**:\
  Seleccione el estilo del segundo conjunto de ladrillos.
* **Desplazamiento de Height**: 0-1\
  Desplazar el height del segundo conjunto de ladrillos

**Cemento**

* **Color de cemento**: selector de color\
  Cambiar el color del cemento entre ladrillos.
* **Rugosidad del cemento**: 0-1\
  Cambiar la rugosidad del cemento entre ladrillos.
* **Intersticio de cemento**: 0-1\
  Cambiar la anchura del cemento entre ladrillos. Cambia el tamaño del ladrillo.
* **Nivel de cemento**: 0-1\
  Cambiar el height del cemento
* **Trastorno del cemento**: 0-1\
  Ajusta la planitud del cemento. En valores altos, el cemento puede elevarse por encima de los ladrillos.

**Edad**

* **Trastorno del ladrillo**: 0-1\
  Ajuste aleatoriamente la rotación de cada ladrillo en 3 dimensiones.
* **Dispersión de ladrillos**: 0-1\
  Añadir grietas en ladrillos
* **Borde de ladrillo**: 0-1\
  Dañar y romper los bordes de los ladrillos
* **Ladrillo despegado**: 0-1\
  Quitar ladrillos al azar
* **Variación de color de ladrillo**: 0-1\
  Varía el color de los ladrillos para hacer que la pared parezca menos uniforme
* **Suciedad del ladrillo**: 0-1\
  Añadir dirt a los ladrillos

**Parámetros avanzados**

* **Intensidad de fusión de Height**: 0-1\
  Ajuste la fusión del height desde el material base. Un valor de 0 ignora el height del material base y solo utiliza los parámetros de filtro de tipo &quot;Brickwall&quot; para generar información del height. El valor 1 utiliza el material base para generar información de height.
* **Intensidad normal**: 0-1\
  Ajuste la intensidad de las normales generadas por el filtro de pared de ladrillo. Un valor de 0 significa que no hay valores normales.
* **Intensidad de Oclusión ambiente**: 0-1\
  Ajuste la intensidad del AO. Un valor de 0 significa en realidad que no hay Oclusión de ambiente.

Guía de uso

El filtro Pared rota el material subyacente en ladrillos individuales que, a continuación, reorganiza. Por esta razón, el filtro Brickwall funciona mejor con superficies duras como rocas o metales, en otras palabras, los materiales más adecuados para ser ladrillos en el mundo real.

El filtro Ladrillo es útil para crear un material base en el que se pueden superponer otros efectos, como musgo, nieve o dirt.
