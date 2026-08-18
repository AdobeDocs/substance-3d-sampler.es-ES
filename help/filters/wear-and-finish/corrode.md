---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/wear-and-finish/corrode.html"
breadcrumb-title: ''
description: Utilice el filtro Corrode en Substance 3D Sampler para añadir efectos de corrosión y degradación química a los materiales metálicos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Wear and Finish > Corrode
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Corrosión
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 0%

---


# Corrosión

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/corrode-filter-icon.png)

**En:** Desgaste y acabado

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

El filtro de corrosión imita el efecto del ácido que se come el material, dejando agujeros y daños en la superficie.

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Raíz aleatoria**:\
  La velocidad aleatoria determina los valores aleatorios de otros parámetros que utilizan aleatoriedad en este filtro.
* **Áreas afectadas**:\
  Seleccione el modo en que la curvatura de la superficie afecta al efecto del filtro.
* **Nivel de perforación**: 0-1\
  Ajuste el número de taladros creados.
* **Posición de curvatura**: 0-1\
  Modifique el rango de curvatura que se va a modificar.
* **Curvatura suave**: 0-1\
  Suaviza el mapa de curvatura.
* **Distancia de daño**: 0-1\
  Controle el radio de daño alrededor de las áreas corroídas.
* **Intensidad de daño**: 0-1\
  Ajuste la cantidad de daño en las áreas afectadas.
* **Intensidad de Height**: 0-1\
  Controle el impacto de los daños en el mapa del height.
* **Posición de extrusión**: alternar\
  Cambie la dirección de los daños en el mapa del height. Cuando está desactivado, el daño se come en la superficie; cuando está activada, el daño se genera hacia fuera desde la superficie.

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

Algunos de los parámetros avanzados afectan al material completo en lugar de solo a las áreas modificadas por este filtro.

* **Luminosidad**: 0-1\
  Ajusta la luminosidad para todo el material.
* **Contraste**: -1 a 1\
  Ajusta el contraste del albedo para todo el material.
* **Cambio de tono**: 0-1\
  Desplazar el valor de tono de los colores en todo el material.
* **Saturación**: 0-1\
  Ajuste la Saturación para todo el material.
* **Intensidad normal**: 0-1\
  Ajuste la intensidad del mapa normal en el que se ha visto afectado por el **filtro de corrosión**.
* **Intervalo de Height**: 0-1\
  Aumente el rango de valores del mapa de height para todo el material.
* **Posición del Height**: 0-1\
  Desplazar el height de todo el material.
* **Intensidad de Oclusión ambiente**: 0-1\
  Ajuste la intensidad del impacto de AO debido al **filtro de corrosión**.
