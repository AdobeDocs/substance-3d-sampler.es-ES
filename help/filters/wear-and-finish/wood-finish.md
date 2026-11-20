---
description: Utilice el filtro Acabado en madera de Substance 3D Sampler para aplicar diversos acabados y texturas de superficies de madera a sus materiales.
title: Acabado en madera
hold: true
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '368'
ht-degree: 0%
---

# Acabado en madera

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../assets/Filters/S_Wood_18_N_D.png" alt=""/><br><strong>En:</strong> Desgaste y acabado</td>
    <td style="border: 0;" valign="top">Descripción<br>Añade detalles normales y de rugosidad a tu material para agregar acabados generalmente asociados con la madera, como barniz, cerusa o grano de madera.<br><em>Un color de relleno simple</em><strong><em></em></strong><em> tiene la apariencia de madera al agregar grano de madera con el </em><strong><em>filtro Acabado en madera</em></strong><em>.</em><br><img src="../../assets/wood-finish-before.png" alt=""/><img src="../../assets/wood-finish-after.png" alt=""/></td>
  </tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:

  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.

* **Tipo de fin**:

  Seleccione un estilo para aplicarlo al metal. Cada estilo tiene diferentes parámetros que le permiten ajustar su apariencia. Además del acabado **Natural**, cada acabado tiene un conjunto de parámetros disponibles para controlar el efecto.

  Están disponibles los siguientes acabados:

  * **Natural**: Un acabado natural liso para madera procesada.
  * **Ceruse**: Crea un aspecto suave y bicolor, rellenando los poros abiertos con un pigmento.
  * **Barniz mate**: Añade un acabado de barniz mate suave.
  * **Barniz**: Añade un acabado de barniz altamente reflectante.
  * **Antigua**: Ajuste el color y la rugosidad del material subyacente para crear la apariencia de madera envejecida.
  * **Raw**: Añada el grano de madera para crear la apariencia de la madera en bruto cortada.
  * **Aserrado**: Añada pistas de sierra para crear el aspecto de la madera fresca de la almazara.

### Parámetros compartidos

Aparecen los siguientes parámetros para varios acabados:

* **Tono**: Ajuste el color del material.
* **Saturación**: Ajusta la intensidad del color.
* **Luminosidad**: Ajusta el brillo.
* **Intensidad de rugosidad**: Ajuste la rugosidad del material.
* **Intensidad de rugosidad de las fibras**: Añade información de rugosidad de alta frecuencia al mapa de rugosidad. Se combina con el regulador Intensidad de rugosidad para modificar los valores de Rugosidad, tanto si el material es muy suave como si es muy rugoso.
* **Intensidad normal**: Ajuste la intensidad del mapa de normales.
* **Contraste de máscara de fibras**:

### Acabados

#### Ceruse

* **Color 1**:
* **Color 2**:
* **Variaciones de Color base**:
* **Detalles de alta frecuencia**:

#### Barniz

* **Variaciones de orientación de fibras normales**:

#### Antiguo

* **Intensidad de rugosidad del barniz**:
* **Rotación de efecto**:

#### Sin procesar

* **Información adicional normal**:

#### Aserrado

* **Reducción de rugosidad con fibras**: Ajuste la rugosidad a lo largo de las líneas de sierra, creando un contraste de rugosidad.
* **Número de cortes de sierra**: Ajuste el número de líneas de sierra.
* **Regularidad de máscara**: Ajuste la frecuencia con la que aparecen las líneas de sierra. Un valor más alto hace que las líneas sean menos regulares.
* **Fibras adicionales**: Ajuste el número de fibras que se añaden paralelamente a las líneas de sierra.
