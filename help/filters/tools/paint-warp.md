---
title: deformación de pintura
description: Aprenda a utilizar el filtro de deformación de Pintura en Substance 3D Sampler para un control preciso de la deformación del material.
source-git-commit: f281c7ec254de74381b2565f835cc32e4de643d2
workflow-type: tm+mt
source-wordcount: '516'
ht-degree: 2%
---

# Deformación de pintura

<table>
  <tr style="border: 0;">
    <td style="border: 0;" valign="top"><img src="../../assets/Filters/S_WarpPaint_18_N_D.png" alt=""/><br><strong>En:</strong> Herramientas</td>
    <td style="border: 0;" valign="top"><strong>Descripción</strong><br>El filtro <strong>Deformación de Pintura</strong> es una poderosa herramienta diseñada para corregir distorsiones geométricas en digitalizaciones basadas en imágenes. Es especialmente útil para materiales con patrones lineales, como tejidos de pana, tablones de madera o ladrillos, donde las líneas naturales no son perfectamente rectas o alineadas con los ejes. Al definir manualmente el flujo del patrón, puede "enderezar" el material para garantizar un azulejo perfecto y mapas de textura de calidad profesional.<br></td>
  </tr>
</table>

## Alineación de patrones de materiales

Puede añadir el filtro Deformación de Pintura manualmente a la Pila de capas, pero el flujo de trabajo más eficaz para las digitalizaciones consiste en utilizar la acción rápida dedicada.

### Uso de la acción rápida

1. Abra la pestaña **Acción rápida**.
1. Seleccione **Alinear patrones de materiales pintando**.

* Sampler añadirá automáticamente tres capas a tu pila: **Ecualizar**, **Deformación de Pintura horizontal** y **Deformación de Pintura vertical**.

1. En la **Pila de capas**, identifica qué dirección sigue tu patrón.

* *Ejemplo:* Para pana con nervaduras verticales, mantén la **Deformación de Pintura vertical** y deshabilita o elimina la versión horizontal.

### Pintar las guías de deformación

Una vez seleccionado el filtro, debe definir el trazado &quot;torcido&quot; actual del motivo para que Sampler sepa cómo enderezarlo.

1. Vaya al panel **Propiedades** del filtro Deformación de Pintura.

1. Busque la propiedad **Image Input** y haga clic en el icono **Brush** que aparece junto a ella para entrar en el modo de pintura.

1. Ajuste el **tamaño de pincel** mediante los widgets de interfaz de usuario o los métodos abreviados.

1. Pintura en función del material:

   >[!TIP]
   >
   > Mantén pulsado **Mayús** mientras haces clic para crear segmentos perfectamente rectos entre puntos.

1. Traza varias líneas a lo largo de la anchura o el height de la textura para proporcionar al algoritmo suficientes datos.

1. En el panel **Propiedades**, cambie el parámetro **Straighten** a **On**. Sampler deformará la imagen para que las líneas pintadas se conviertan en perfectamente paralelas al eje elegido.

## Referencia de parámetros

| Nombre | Descripción | Rango/Opciones | Predeterminado |
| --- | --- | --- | --- |
| **Dirección** | Determina el eje al que se alineará la deformación. | Vertical, Horizontal | Vertical |
| **Enderezar** | Activa o desactiva el efecto de deformación en función de la máscara pintada. | Alternar (activar/desactivar) | Desactivado |
| **Mostrar entrada** | Superposición auxiliar que muestra guías para ayudar a pintar con precisión. | Alternar (activar/desactivar) | Desactivado |
| **Deformación suave** | Controla el difuminado y el smoothness de la deformación entre guías pintadas. | 0.0 - 1.0 | 0.5 |

## Sugerencias y prácticas recomendadas

* **Usar Mostrar entrada:** Habilite el conmutador **Mostrar entrada** al pintar. Esto proporciona una superposición de cuadrícula que facilita ver exactamente dónde se desvía la digitalización original de una cuadrícula perfecta.
* **No sobrepasar la Pintura:** No es necesario realizar un seguimiento de cada línea de un patrón. Normalmente, 3 a 5 líneas bien colocadas a lo largo de la textura son suficientes para que el algoritmo calcule la deformación necesaria.
* **Combinar con mosaico:** Use Deformación de Pintura antes de aplicar el filtro **Mosaico**. Un patrón enderezado es significativamente más fácil de azulejar sin costuras visibles o líneas &quot;rotas&quot; en los bordes.
* **Ecualizar primero:** Como se ve en la acción rápida, colocar un filtro **Ecualizar** antes de la deformación de Pintura ayuda a eliminar los degradados de luz, lo que facilita ver los detalles del patrón que está intentando alinear.

## Artículos relacionados

* [Ecualizar](../adjustments/equalize.md)
* [Mosaico](tiling.md)
* [Acciones rápidas](../../features-and-workflows/quick-actions.md)
* [Análisis de prácticas recomendadas](../../pipeline-and-integrations/hp-z-captis-support/scanning-best-practices.md)
