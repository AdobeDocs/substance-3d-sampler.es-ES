---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/cross-polarising-for-3d-capturesubstance-3d-sampler.html"
breadcrumb-title: ''
description: Aprende a usar técnicas de polarización cruzada en Substance 3D Sampler para reducir los reflejos y mejorar la calidad de la Captura 3D.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Cross-polarizing for captura 3D
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---


# Cross-polarizing for captura 3D

>[!WARNING]
>
> La compatibilidad con captura 3D se ha eliminado a partir de la versión 5.1 de Sampler.

## Cross-Polarizing

En esta guía del usuario, repasaremos cómo tratar con los objetos reflectantes y los problemas que causan, y cómo usar la polarización de luz para resolver este problema.

¿Prefiere aprender sobre este tema en un tutorial de vídeo? Encuéntralo [aquí](https://youtu.be/VWsbP56MDk0?si=Hdp7vblJB6L1RPxK "Tutorial de polarización cruzada").

![](../assets/polarized-lens-3d-capture.png)

Cuando la luz incide en una superficie, normalmente se refleja de forma difusa, rebotando uniformemente, lo que le da a la superficie un aspecto de color. Sin embargo, dependiendo de la rugosidad de la superficie, alguna luz puede reflejarse directamente hacia el ojo o la cámara. Este <b>reflejo del specular</b> cambia según tu ángulo de visión.

La fotogrametría funciona alineando patrones visuales y elementos entre fotografías, y supone que el aspecto de un objeto no cambiará entre cada fotografía consecutiva. Por lo tanto, el reflejo del specular es un efecto no deseado. Un objeto de caso leve puede tener solo un revestimiento reflectante, pero los objetos que son de metal pueden ser mucho más complicados y requerir más esfuerzo para resolverlos. Abordaremos el caso leve en esta guía del usuario. Solo tenemos que captar un color base perfecto, intacto por los reflejos de specular. Es fácil volver a añadir la reflectividad en 3D una vez capturada.

Para solucionarlo, podemos filtrar nuestros reflejos de specular usando un método llamado <b>polarización cruzada</b>. Cuando la luz se polariza, todas las ondas se orientan en la misma dirección. Si luego lo polarizas de nuevo, en una dirección perpendicular, se bloquea completamente, haciéndolo invisible.

La polarización afecta principalmente a la luz del specular, ya que se trata de rayos de luz enfocados, que viajan en una dirección específica, en lugar de la luz difusa dispersa que queremos mantener.

Polarizas la luz con un filtro polarizador, una lámina transparente especial que filtra las ondas. Vienen en muchas formas, usaremos filtros de vidrio atornillados para tus lentes, así como láminas de película polarizante al estilo DIY

La idea básica es <b>añadir un filtro a tu luz</b> y <b>tu lente</b>, y configurarlos para que sean <b>perpendiculares entre sí</b>. Esto significa que tendrás que ajustar la orientación del filtro rotándolo. Una vez configurados, los reflejos del specular procedentes de esa luz se vuelven invisibles. Es muy especial verlo, ya que al girar los filtros de repente se eliminan por completo todos los reflejos de una luz polarizada.

![](../assets/polarizing-before-after-3d-capture.png)

Debería comprarse un filtro polarizante para el objetivo, ya que se desea una óptica óptima, que siga permitiendo fotografías nítidas y nítidas. Los diferentes objetivos tienen diferentes tamaños de rosca a los que atornillar los filtros, así que asegúrate de tener el adecuado para tu objetivo de elección, o unos cuantos tamaños para varios objetivos si estás experimentando.

Polarizar las luces es más barato y sencillo: <b> láminas de película polarizante</b> son relativamente económicas. Puede utilizar una hoja entera o cortar partes. Es una buena idea cortar piezas circulares que cubran toda la luz, ya que hace que sea más fácil rotarlas. Algunas luces son mejores para esto, podrían tener un pequeño portafiltros, o imanes para mantener las hojas en su lugar. Si no, la cinta adhesiva siempre funciona.

Asegúrate de <b>añadir el polarizador después de cualquier difusor</b>, ya que al difuminar la luz se cancela cualquier polarización.

La mayoría de los flashes de anillos más baratos se atornillan a la ranura del filtro y es posible que ya no te permitan acoplar un filtro de lente. Tampoco tienen forma de adjuntar filtros polarizadores a la propia luz del flash, por lo que tendrás que crear los tuyos propios. Solo los modelos de la parte superior de la línea lo admiten correctamente.

<b>La rotación y la correspondencia de los polarizadores en toda la configuración deben realizarse constantemente</b>. El filtro del objetivo debe ser totalmente perpendicular a todas las luces. La única forma de hacerlo es mirar la pantalla de la cámara y ajustar las cosas. Me gusta empezar grabando una sola hoja en el flash y, a continuación, ajustar el filtro de mi lente para bloquear los reflejos del flash. Solo puedes hacerlo tomando una foto, o disparando el flash en seco. Es un poco complicado, puedes marcar la orientación correcta en tu filtro de lente con un marcador y luego tratar de no tocar más la lente y el filtro de flash.

Ajustar la polarización de las luces del vídeo es diferente, pero más fácil. Tendrás que ajustar constantemente las luces conforme las mueves o cuando ajustas el height de la cámara. Simplemente <b>gira la hoja hasta que se vea bien en la pantalla de tu cámara</b>.

<b>Todas las fuentes de luz que aparecen en los reflejos deben polarizarse</b>, por lo que es posible que tengas que cerrar las ventanas o apagar las pantallas.

Cuando se configura correctamente, deberías poder capturar un objeto como si fuera completamente mate, sin reflejos e incluso con iluminación. Al igual que cuando ves tu malla solo con la textura de color base aplicada, te permite capturar objetos reflectantes difíciles.

Ahora obtén más información sobre [cómo procesar tu Captura 3D con Substance 3D Sampler](processing-advanced-3d-captures.md).
