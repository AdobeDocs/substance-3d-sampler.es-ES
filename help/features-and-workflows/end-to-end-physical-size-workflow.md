---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/features-and-workflows/end-to-end-physical-size-workflow.html"
breadcrumb-title: ''
description: Aprende a usar el flujo de trabajo de tamaño físico integral en Substance 3D Sampler para crear materiales físicamente precisos a la altura de la escala real.
helpx_creative_field: ""
helpx_description: Sampler > Features and workflows > End to end Physical Size Workflow
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Flujo de trabajo de Tamaño físico de principio a fin
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Flujo de trabajo de Tamaño físico de principio a fin

Haz coincidir el tamaño físico de la vida real de tus muestras e imágenes escaneadas en un contexto digital para crear elementos visuales físicamente precisos en todas las aplicaciones.

## Importar digitalizaciones

1. Seleccione la plantilla de creación de material.
1. Marque la casilla de verificación tamaño físico.

   ![](../assets/screenshot-2022-01-20-at-16-15-53.png)
1. Dos enfoques para establecer el Tamaño físico:

   3 bis. Haga clic en Medida manual : La herramienta Medida le permite calibrar el tamaño físico entre 2 características de la muestra.\
   Seguimiento entre dos puntos -> Intro

   ![](../assets/screenshot-2022-01-20-at-16-31-26.png)

   3 ter. Medida automática : Esta herramienta permite obtener un tamaño físico estimado de la muestra en función de los metadatos de la imagen (ppp). Es más rápido, pero solo funciona con digitalizaciones, ya que utiliza los ppp almacenados para calcular un tamaño inicial preciso.

   <b>Ahora puede procesar las digitalizaciones</b>
1. Agregue un recorte y ajústelo a la muestra. Puede ver el tamaño físico que se muestra en la esquina inferior derecha de la ventana gráfica 2D actualizada.

   Visualícelo con proporción física en la ventana gráfica 2D para ver con precisión los mapas en los que está trabajando.\
   Puede configurar la vista 2D para que se ajuste al tamaño físico, de modo que el valor de PPP de la proporción de pantalla coincida con la escala del material. En otras palabras, puede poner su muestra real junto a la pantalla para verificar las dimensiones.

   ![](../assets/cq5dam.web.1280.png)
1. Agregue un Ecualizador para deshacerse de los degradados.
1. Añadir mosaico para corregir el mosaico parece
1. Si es necesario, la transformación de deformación resulta útil para realinear solo partes del mapa.

   <b>Listo para exportar</b>
1. Exportar como

   Seleccione el formato Sbsar, Sampler le añadirá Tamaño físico como metadatos. Permitirá que otras aplicaciones lean y utilicen esta información también.\
   También puede exportar imágenes; respetará la proporción de tamaño físico.

   Si necesitas usar el tamaño físico en cualquier momento, usa el *Panel de Tamaños físicos*.

   Al exportar como imágenes, ahora es posible forzar que el tamaño de las imágenes respete la proporción de tamaño físico.

## Tutorial de vídeo

También puede encontrar tutoriales en vídeo que le ayudarán a moverse por esta función:
