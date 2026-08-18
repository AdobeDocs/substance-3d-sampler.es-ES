---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/hdri-tools/nadir-patch.html"
breadcrumb-title: ''
description: Utilice la herramienta de Nadir patch de Substance 3D Sampler para parchear el área de nadir de las imágenes HDRI y obtener mapas de entorno perfectos.
helpx_creative_field: ""
helpx_description: Sampler > Filters > HDRI Tools > Nadir Patch
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Nadir patch
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---


# Nadir patch

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

![](../../assets/s-nadirpatch-18-n-d.png)

**En:** Herramientas HDRI

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Retoca el nadir de la luz de tu entorno para ocultar artefactos o costuras.

En las imágenes siguientes, puedes ver cómo se usa el **Nadir patch** para quitar el soporte de la cámara en esta imagen panorámica.

![](../../assets/3d-2d-filters-cropped-0011-nadir-patch-in.jpg)![](../../assets/3d-2d-filters-cropped-0010-nadir-patch-out.jpg)

</td>
</tr>
</table>

## Parámetros

**Parámetros básicos**

* **Habilitar**: alternar\
  Activar o desactivar el parche: esto puede resultar útil para ver rápidamente el impacto del parche sin tener que cambiar la visibilidad de la capa.
* **Ayuda para mostrar fotogramas**: alternar\
  Encienda o apague los fotogramas.
* **Thickness de fotogramas**: 0-1\
  Ajuste el thickness del marco. Esto puede resultar útil cuando el origen del parche está lejos del nadir.
* **Escala del parche**: 0-1\
  Ajuste el límite del área a la que se aplicará el parche.
* **Tamaño de parche**:\
  Ajuste las dimensiones del parche.
* **Rotación de parche**: 0-1\
  Gire los límites del parche. Esto rota tanto la ubicación de origen como la ubicación del parche, por lo que el parche seguirá teniendo la misma orientación. Para rotar la revisión en su lugar, use **Desplazamiento de rotación de origen**.
* **Alpha de parches**:\
  Seleccione la forma utilizada para enmascarar el parche. Si se selecciona **Entrada de máscara**, aparecerá un parámetro adicional:
  * **Entrada de máscara**: imagen/pincel\
    Importa una imagen para usarla como máscara o pinta una máscara directamente en la **vista 2D**.
* **Dureza del parche**: 0-1\
  Ajuste el desenfoque en los bordes de la máscara de parche.
* **Desplazamiento de rotación de origen**: 0-1\
  Desplazar la rotación del origen : Esto tiene el efecto de girar el parche.

## Guía de uso

Un problema común que se puede producir al crear una luz de entorno a partir de fotografías son los artefactos que se producen alrededor de los niveles superior e inferior de la textura. El **Nadir patch** **filter** ayuda a minimizar estos problemas.

1. Agregue el **filtro de Nadir patch** a la parte superior de la pila de capas.
1. Utilice el identificador de la **vista 2D** para cambiar la ubicación de origen del parche.
   1. El nadir de parches cambia en función de la ubicación del origen. Si el origen se encuentra en la mitad inferior del espacio de textura, se aplicará el parche en el nadir inferior; si el origen está en la mitad superior, se aplicará un parche en el nadir superior.
1. Modifique los parámetros para afinar la transformación del parche y ocultar mejor las costuras y los defectos.
