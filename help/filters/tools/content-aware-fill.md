---
title: Relleno según el contenido
description: Aprenda a utilizar el filtro Relleno según el contenido en Substance 3D Sampler para corregir problemas en patrones repetidos o eliminar dirtes o suciedad no deseados.
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 1%
---

# Relleno según el contenido

<table>
  <tr>
    <td><img src="../../assets/Filters/S_ContentAwareFill_18_N_D.png" alt=""/><br><strong>En:</strong> Herramientas</td>
    <td>Descripción<br>El relleno según el contenido te permite eliminar elementos como dirtes, texto u otros objetos no deseados de tus materiales.<br>En el ejemplo siguiente del piso del bosque, el palo destaca en el patrón repetido. Con el Relleno según el contenido, podemos eliminar la ramita, lo que hace que la repetición sea un poco menos perceptible. <br><br><img src="../../assets/content-aware-fill-before.png" alt=""/><br><em>Antes de la eliminación</em><br><br><img src="../../assets/content-aware-fill-after.png" alt=""/><br><em>Después de la eliminación</em></td>
  </tr>
</table>

## Parámetros

* **Selección de canales:** Seleccione los canales en los que desea ejecutar el filtro. De forma predeterminada, se establece en todos los canales; sin embargo, también puede optar por ejecutar solo en los canales de Height o de Color base.
* **Espejo:** Para patrones o materiales simétricos, esta configuración guía el Relleno según el contenido para incorporar contenido de reflejo en el material.
* **Escala:** Para patrones geométricos como azulejos o ladrillos, esta configuración puede ayudar a mantener la estructura del patrón.

### Parámetros técnicos

* **Máscara personalizada:** Aplique una máscara con una textura o use el pincel para pintura su propia máscara en la **Ventana gráfica 2D**.
* **Factor de recorte de búsqueda:** Recorte el área de muestra usada por el filtro. De forma predeterminada, el área de muestra cubre toda la textura excepto el área enmascarada; al aumentar el **Factor de recorte de búsqueda**, disminuye el área de muestra, lo que puede ayudar a limitar las muestras a píxeles más cercanos al área enmascarada.

### Configuración de relleno

* **Adaptación de color:** Ajusta en qué medida el relleno intenta adaptarse a los colores circundantes. Este ajuste puede ser útil con materiales que
* **Adaptación de rotación:** Para patrones en los que la rotación de elementos es importante, como los pétalos de una flor o los rayos de una rueda, este ajuste puede ayudar a crear resultados más coherentes.