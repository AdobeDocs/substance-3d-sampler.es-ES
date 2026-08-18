---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/filters/generators/weave.html"
breadcrumb-title: ''
description: Usa el generador de tejido de Substance 3D Sampler para crear patrones de tejido y texturas textiles para la creación de materiales.
helpx_creative_field: ""
helpx_description: Sampler > Filters > Generators > Weave
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Tejer
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '756'
ht-degree: 0%

---


# Tejer

<table>
<tr style="border: 0;">
<td width="41.60%" style="border: 0;" valign="top">

**En:** Generadores

</td>
<td width="58.30%" style="border: 0;" valign="top">

## Descripción

Usa el filtro Tejido para convertir imágenes en patrones tejidos.

</td>
</tr>
</table>

## Parámetros

**Ajustes preestablecidos**

Utilice los ajustes preestablecidos para cambiar rápidamente los parámetros y ver los diferentes estilos de tejido

**Parámetros básicos**

* **Raíz aleatoria**:\
  Semilla aleatoria en la que se basan todos los demás parámetros aleatorios de este filtro.
* **Imagen**: imagen/pincel\
  Seleccione una imagen o pinte directamente en la **vista 2D**. El filtro **Tejer** funciona mejor cuando se selecciona una imagen.
* **Recuento de colores**: 1-10\
  El **filtro de trama** desglosa automáticamente la entrada de imagen en varios colores según este parámetro. Los parámetros de cada Color se pueden controlar de forma independiente.
* **Tamaño de área (cm)**: 2-50\
  Cambiar el tamaño físico representado por el espacio 2D. Esto cambiará el número de puntos utilizados para recrear la imagen de entrada.
* **Densidad (puntos por cm)**: 1-105\
  Funciona con el control **Tamaño de área (cm)** para ajustar el número de puntos en el espacio 2D.
* **Rugosidad global**: 0-1\
  Ajustar la rugosidad del material
* **Modo de trama de color**:\
  Seleccione si la trama se colorea en función de la entrada de la imagen o si se basa en selecciones de color personalizadas. Si se selecciona **Anular por color**, aparecerá un parámetro **Color** adicional en cada color.

**Color X**

El número de colores disponibles para modificar depende de **Parámetros básicos > Recuento de colores**.

* **Color**: selección de color\
  Solo está disponible si **Parámetros básicos > Modo de trama de color** está establecido en **Reemplazar por color**. Elija el color del material de esta sección.
* **Tamaño de borde**: 0-1\
  Añada un borde en los bordes del color seleccionado. El borde aumenta la longitud de la trama entre las roscas de deformación cerca del borde del color, evitando que las puntadas de deformación aparezcan cerca del borde de los conjuntos de colores.
* **Desplazamiento de rugosidad**: 0-1\
  Modificar la rugosidad de este conjunto de colores
* **Metálico**: 0-1\
  Modificar el valor metálico de este conjunto de colores
* **Posición del Height**: 0-1\
  Ajuste el height de este conjunto de colores. Utilice esta opción para añadir profundidad a la versión tejida de la imagen.

**Avanzado**

* **Color de deformación**: selección de color\
  Cambiar el color de los subprocesos de deformación (de forma predeterminada, los subprocesos de deformación se ejecutan de forma perpendicular a los subprocesos que son más visibles).
* **Deformar - Intercambio de trama**:\
  Intercambie los hilos que son deformados y los que son trama. Esto tiene el efecto de girar los puntos 90 grados,
* **Deformar ejes**: 1-16\
  Ajuste la frecuencia relativa de las roscas de deformación a roscas de trama. Se puede utilizar para crear diferentes motivos de jacquard.
* **Tamaño de deformación**: 0-1\
  Engrosar o reducir las roscas de deformación
* **Intensidad de desenfoque de diferencia de Height**: 0-1\
  Controle la pendiente o el desenfoque causados por las diferencias de **posición del Height**. Esto no tiene efecto a menos que cambie el regulador **Posición del Height** para al menos un conjunto de colores.

## Guía de uso

El filtro Tejido puede resultar un poco confuso al principio, pero con solo unos pocos parámetros importantes para empezar pronto estarás creando intrincados tejidos para añadir a tus materiales.

>[!NOTE]
>
> Si has usado el filtro [Bordado](embroidery.md) antes, el filtro Tejido funciona de forma similar. Producen efectos diferentes, pero puede utilizar imágenes con ellos de la misma manera.
> 
> Las imágenes para tejer deben ser de proporciones cuadradas, de alta resolución (2K como mínimo) y tener un máximo de 10 colores diferentes. El canal alfa o el canal de transparencia se pueden utilizar para cortar formas. Lo ideal es que estén basados en vectores, pero se exporten como mapa de bits PNG.

Para utilizar el filtro Tejido:

1. Arrastra y suelta una imagen en
1. Añada el filtro Tejido a la pila de capas.
1. Ajuste **Parámetros básicos > Número de colores** hasta que el equilibrio de color se vea correcto para la imagen. Con un límite de 10 colores, el filtro Tejer funciona mejor con colores planos e imágenes ilustradas.
1. Ajuste otros parámetros para ajustar el aspecto del parche.

Estos son los conceptos básicos del uso del filtro Tejido.

Es posible utilizar imágenes transparentes en el filtro Tejer, pero de forma predeterminada también afectarán al mapa de opacidad del material, ya que las partes transparentes de la imagen también harán transparente el material. Para crear un parche con el filtro Tejido y hacer que se asiente sobre las capas inferiores, utilice el filtro Calcomanía.

1. Crea un filtro de pegatinas.
1. Añada el filtro Tejido a la ranura de entrada del filtro de pegatinas.
1. Siga los pasos normales para ajustar el patrón de tejido.

La capa de pegatina convierte la entrada de tejido en una pegatina, por lo que la transparencia de la capa de tejido indica a la capa de pegatina cómo enmascarar el patrón tejido. Con la capa de pegatinas, también puedes mover el patrón por el material o activar funciones como el mosaico.
