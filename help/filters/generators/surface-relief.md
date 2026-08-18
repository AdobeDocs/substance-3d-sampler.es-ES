---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/filters/generators/surface-relief.html"
breadcrumb-title: ''
description: Utilice el generador de Relieves de superficie en Substance 3D Sampler para crear patrones de superficies en relieve y de relieve en materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Surface Relief
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Relieve de superficie
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---


# Relieve de superficie

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-surfacerelief-18-n-d.png)

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Utilice el filtro Relieve de superficie para añadir ruido al material. Esto puede ayudar a dividir las formas grandes o añadir interés visual.

</td>
</tr>
</table>

## Parámetros

<b>Parámetros básicos</b>

* <b>Raíz aleatoria</b>:\
  Semilla aleatoria en la que se basan todos los demás parámetros aleatorios de este filtro.
* <b>Intensidad</b>: 0-1\
  Cambiar la amplitud del ruido
* <b>Intensidad De Desenfoque</b>: 0-1\
  Intensidad del desenfoque aplicado al ruido
* <b>Imperfección de superficie </b>: Generador de imágenes/pinceles/texturas\
  Utilice una imagen o un generador de texturas como imperfección de la superficie.

<b>Parámetros de ruido</b>

* <b>Abrazadera</b>: 0-1\
  Fijar el ruido a un cierto rango
* <b>Contraste</b>: 0-1\
  Modificar el contraste del ruido
* <b>Invertir</b>: alternar\
  Invertir el mapa de height de ruido

<b>Transformar</b>

* <b>Mosaico</b>: 1-16\
  A diferencia de <b>Parámetros básicos > escala</b>, <b>Mosaico</b> administra el número de instancias del ruido.
* <b>Duplicar</b>:\
  Reflejar el ruido en uno o ambos ejes
* <b>Desplazamiento</b>:\
  Recolocar el ruido en los ejes X e Y
* <b>Rotación</b>:\
  Rota el ruido. El ángulo de rotación se ajusta para garantizar que el mosaico siga siendo posible.

<b>Máscara</b>

* <b>Usar máscara personalizada</b>: alternar\
  Active esta opción para ver los controles de Máscara personalizada :
  * <b>Máscara</b>: image/brush/Texture Generator\
    Importa una imagen para usarla como máscara o usa el pincel para pintar directamente en la <b>vista 2D</b>
  * <b>Máscara personalizada - Desenfocar</b>: 0-1\
    Desenfocar la máscara
  * <b>Máscara personalizada - Invertir</b>: alternar

<b>Parámetros avanzados</b>

* <b>Intensidad de Height</b>: 0-1\
  Controlar la mezcla del mapa de altura de ruido con el mapa de altura de materiales subyacente
* <b>Height - Reemplazar base</b>: alternar\
  Alternar entre reemplazar o no el height base
* <b>Intensidad normal</b>: 0-1\
  Ajuste la intensidad del mapa normal del ruido
* <b>Normal - Reemplazar base</b>: alternar\
  Alternar entre reemplazar o no el mapa normal base
* <b>Dirección normal</b>:\
  Modificar los ejes que se utilizarán para la generación normal
* <b>Normal - Girar dirección</b>
* <b>Oclusión ambiente - Intensidad</b>
* <b>Oclusión ambiente - Radio</b>
