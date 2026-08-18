---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/interface/panels/layers-panel.html"
breadcrumb-title: ''
description: Aprende a utilizar el panel Capas de Substance 3D Sampler para gestionar capas de filtro y crear pilas de materiales complejas.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Layers panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Panel Capas
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '970'
ht-degree: 2%

---


# Panel Capas

<table>
<tr style="border: 0;">
<td style="border: 0; width: 70%" valign="top">

El **panel Capas** contiene la pila de capas y métodos abreviados para administrar las capas. El **panel Capas** funciona en estrecha colaboración con el **panel Propiedades**: selecciona una capa del **panel Capas** para ver sus propiedades en el **panel Propiedades.**

El **panel Capas** consta de tres secciones principales:

1. La sección de herramientas contiene botones que puede utilizar para
   1. Mostrar/ocultar resolución de capas
   1. Estrategia de resolución de capas de cambio
   1. Añadir una capa
   1. Añadir un material base
   1. Importar un filtro personalizado
   1. Quitar una capa
1. El **selector de modo de fusión** te permite ajustar la forma en que se fusiona una capa con las capas que hay debajo. El **selector de modo de fusión** solo está disponible cuando se selecciona una capa de material; los filtros no utilizan modos de fusión.
1. La **pila de capas** contiene todas las capas que forman el activo.

</td>
<td style="border: 0;" valign="top">

![Animación del panel Capas de ninguna capa a una pila completa que crea un material](../../assets/Layers-panel-gen.png.img.png)

</td>
</tr>
</table>

## La pila de capas

La pila de capas es la colección de materiales, filtros y otros recursos que componen el material actual. Al igual que en Photoshop y Substance 3D Painter, la pila de capas funciona desde la capa inferior primero hasta la capa superior última. Esto significa que cada capa puede afectar a las capas que se encuentran por debajo de ella.

Existen varias formas de administrar la pila de capas:

| Acciones | Cómo aplicar el |
| --- | --- |
| Añadir una capa | Arrastre un recurso desde el **panel Recursos** al área de visualización para agregarlo a la parte superior de la pila de capas. Arrastre un recurso del **panel Recursos** a la pila de capas para agregarlo a una ubicación específica de la pila de capas. Usa el botón **Agregar una capa** de la sección de herramientas para seleccionar un filtro de una lista. |
| Mover una capa | Arrastre una capa de la pila de capas para moverla. Al mover una capa, aparece una barra que indica dónde se colocará la capa. |
| Eliminación de una capa | Haz clic en una capa para seleccionarla y pulsa **Supr** o usa el botón **Quitar una capa** en la sección de herramientas. |
| Alternar visibilidad | Pase el ratón sobre una capa para ver el **conmutador Visibilidad** en el lado derecho de la capa. Cuando se desactiva la visibilidad de una capa, no se calcula. |
| Ver propiedades de capa | Haga clic en una capa para abrir y ver sus propiedades en el panel **Propiedades.** |
| Mostrar/ocultar resolución | Haz clic en el botón superior izquierdo del **panel Capas**. |
| Cambiar la resolución de todas las capas | Haga clic en la flecha junto al botón &quot;Mostrar/ocultar resolución&quot; y seleccione la estrategia para todas las capas de la pila. |
| Cambiar una resolución de capa | Haz clic en una capa para abrir sus propiedades, haz clic en la resolución en el **panel Propiedades** y selecciona la estrategia de resolución que usará la capa. |

## Tipos de capas

Existen tres tipos de capas:

* Materiales
* Filtros
* Imágenes

### Capas de material

Una capa de material contiene información en varios canales y se puede fusionar con las capas inferiores. Las capas de material se muestran de forma ligeramente diferente según se encuentren en la parte inferior de la pila o no. Por ejemplo, la imagen siguiente muestra un material de roca arrastrado dos veces a la pila de capas. Observe que la capa inferior no tiene icono para controlar la fusión, mientras que la capa superior sí lo tiene.

![Capas de material en la pila de capas, la capa superior tiene una opción de fusión.](../../assets/Material-Layer.png)

Las reglas generales para las capas de material son:

* Una capa de material siempre utiliza la resolución del documento.
* Una capa de material en la parte inferior de la pila no tiene nada con qué fusionarse, por lo que el **selector de modo de fusión** no está disponible.
* Una capa de material que no se encuentre en la parte inferior de la pila se puede fusionar con las capas que estén debajo, por lo que puedes usar el **selector de modo de fusión** para cambiar el modo de fusión. Además, aparece un **icono de mezcla** junto al **icono de capa**. Seleccione el **icono de fusión** para ajustar la configuración de fusión de la capa en función del modo de fusión seleccionado.

### Filtrar capas

![Propiedades del filtro Tono/saturación ajustando las capas siguientes.](../../assets/HueSaturation_LayerFilter.gif)

Los filtros realizan operaciones en las capas que se encuentran debajo de ellos para crear efectos específicos. Por ejemplo, en la imagen superior, el **filtro Tono/Saturación** te permite ajustar el tono, la saturación y la luminosidad de las capas inferiores.

Algunos filtros pueden tomar una o más capas como entradas. Por ejemplo:

* El **filtro de Atlas scatter** puede tomar un material como entrada.
* El **filtro de Atlas scatter** dispersión instancias del material del atlas de entrada basándose en los parámetros **Atlas scatter**.

Arrastre un material sobre una ranura de entrada de capas para utilizarlo como entrada.

Una capa de filtro utilizará la estrategia de resolución predeterminada definida en las preferencias. Puede cambiar la resolución que utilizará el filtro en el panel Propiedades.

![Resolución de cambio de una capa de filtro](../../assets/SwitchLayerResolution.gif)

### Capas de imagen

Las capas de imagen utilizan su propia resolución y se encuentran principalmente en el flujo de trabajo de conversión de imagen a material. Al igual que las capas de material, puedes crear una capa de imagen arrastrando una imagen desde el **panel Activos**.

Puede arrastrar una imagen desde el explorador de archivos de su sistema a Sampler, si ya hay capas en la pila de capas, la capa de imagen se agregará a la parte superior de la pila. Si no hay capas en la pila de capas, aparecerá un cuadro de diálogo en el que puede elegir cómo procesar la imagen:

* **De imagen a material** te permite usar IA para convertir una imagen en un material.
* **Multiángulo a material** te permite usar varias imágenes con diferentes condiciones de iluminación para crear un material.
* La **importación de texturas** te permite usar imágenes importadas como canales de texturas para crear un material.
* **Usar como mapa de bits** importa la imagen como una capa de mapa de bits simple.

También puede arrastrar varias imágenes seleccionadas a la pila de capas a la vez para importarlas todas como una sola capa. Esto puede resultar útil para filtros de varias imágenes como **Combinación HDR** y **Multiángulo a material**. Seleccione la capa con varias imágenes para cambiar los datos de canal de cada imagen.
