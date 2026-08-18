---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/3d-capture/camera-settingsfocussubstance-3d-sampler.html"
breadcrumb-title: ''
description: Aprenda a configurar el enfoque de la cámara en Substance 3D Sampler para obtener una calidad de Captura 3D y una nitidez de imagen óptimas.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Enfoque de ajustes de cámara
user-guide-description: ''
user-guide-title: ''
source-git-commit: 6cc0519fb8c0f74fa805691ec4adb9e449a627d5
workflow-type: tm+mt
source-wordcount: '759'
ht-degree: 0%

---


# Enfoque de ajustes de cámara

>[!WARNING]
>
> La compatibilidad con captura 3D se ha eliminado a partir de la versión 5.1 de Sampler.

## Configuración de la cámara: enfoque

<b>Aperture</b> es el ajuste de cámara más complejo, por lo que en esta guía del usuario lo explicaremos en profundidad.

¿Prefiere ver esta guía como un tutorial en vídeo? Puedes encontrarlo [aquí](https://youtu.be/kFZ71ZWuap0?si=MDuvyO9w96rFpsQ9 "tutorial de vídeo sobre apertura y enfoque para Captura 3D").

![](../assets/focus-manually-3d-capture.png)

## Enfoque de un objetivo

De forma predeterminada, el sistema de enfoque automático de la cámara controla esto y define el enfoque automáticamente. Eso tiene sentido cuando fotografiamos personas, entornos grandes o cualquier cosa dinámica, pero para nuestro sujeto controlado y estático incluso podría causar problemas; el enfoque automático puede cometer errores y arruinar una foto, incluso entre dos tomas.

Todas las DSLR pueden cambiar del enfoque automático a un <b>enfoque manual</b> completo. Esto significa que tiene el control total del enfoque, girando el anillo de enfoque en el objetivo. De esta forma, estás seguro de que el enfoque no saltará entre tomas. Si lee el manual de la cámara, probablemente habrá ajustes que le ayudarán, como &quot;enfoque máximo&quot;, donde se dibuja un efecto de color sobre la pantalla de la cámara. Esto ayuda a ver qué parte de la imagen está enfocada. Incluso puede haber un ampliador de zoom, en el que la pantalla muestre una pequeña parte de la vista actual ampliada, lo que le ayudará a lograr un enfoque perfecto en píxeles. Especialmente este ampliador de zoom es crucial para ayudar a conseguir el enfoque.

El uso del enfoque manual te ayudará a ver y comprender mejor lo que está sucediendo con tu apertura <b></b> y el enfoque <b>3}. </b>El inconveniente es que <b>tienes que reajustar el enfoque cada vez que la cámara o el sujeto se mueve</b>. Es fácil olvidar y arruinar una foto, así que conviértela en un hábito que hay que comprobar.

## Selección del valor de apertura

<b>Aperture</b> es complicado porque afecta al <b>enfoque</b> y al <b>enfoque</b>. No queremos que algunas partes de nuestro sujeto no estén enfocadas, esto causa problemas en el proceso de fotogrametría. Eso significa que una apertura grande, normalmente entre f1.8 y f3.5 para lentes estándar, será un problema. Por otro lado, ir para la apertura más pequeña posible, f/32 tampoco es muy bueno, las cosas también se hacen menos nítidas en este extremo, y la cantidad de luz que entra es pequeña, lo que lleva a problemas de iluminación.

Aunque la profundidad de campo se ensancha con aperturas más pequeñas, también se escala con la distancia de enfoque. Esto quiere decir que tendrás más profundidad de campo cerca y mucho menos hasta la nitidez total, más lejos. Esto puede ser problemático para objetos pequeños, si desea que ocupen la mayor parte de la fotografía.

Entonces, ¿cuál es el valor de apertura correcto? Como regla general, descubre cuál es el rango de apertura más nítido para tu objetivo y empieza con este valor. Esto es probablemente <b> F8 o f11, hasta f16</b>.  Comprueba si <b>todo está enfocado</b>; de lo contrario, reduce paso a paso hasta aproximadamente f20. Si el objeto aún no está totalmente enfocado, aléjese un poco más de él. Incluso 10-15 cm de distancia puede marcar la diferencia para los objetos pequeños.

Además, tenga en cuenta que la elección del objetivo puede marcar la diferencia. Los objetivos predeterminados del kit que vienen con una cámara no suelen ser los más nítidos ni los de mayor calidad, y puede valer la pena invertir en un objetivo de mayor calidad. Especialmente para primeros planos, los objetivos macro pueden ser útiles, ya que permiten que el enfoque se acerque mucho más al objetivo.

## Enfoque entre corchetes

Hay un truco especial que puedes hacer, para lograr una nitidez perfecta cuando todo lo demás falla. <b>Enfoque entre corchetes</b> significa que tomas <b>varias fotos</b>, a <b>diferentes distancias de enfoque</b>, y las combinas en Photoshop. Requiere <b>mucho trabajo adicional</b>, especialmente con series de bucles completos, por lo que solo se debe usar como último recurso.

Si tiene 2 o más fotografías con diferente enfoque, cárguelas en capas diferentes.

![](../assets/focus-differences-3d-capture.png)

Seleccione todas las capas y vaya a <b>Editar</b> > <b>Alinear capas automáticamente</b>. Pulse Aceptar con la configuración predeterminada. Photoshop intentará hacer una alineación perfecta de todas las capas seleccionadas

A continuación, ve a <b>Editar</b> > <b>Fusionar capas automáticamente</b>. De nuevo, seleccione Aceptar con todos los ajustes predeterminados. Photoshop fusionará las partes más nítidas de las capas.

Si todo salió bien, ahora tienes una fotografía perfectamente nítida. Vale la pena convertir al menos algunos de estos pasos en una acción grabada, para ahorrarte tiempo.

Ahora que has aprendido todo lo que hay que saber sobre Aperture y Focus para el proceso de Captura 3D, obtén más información sobre [cómo crear una configuración de iluminación ideal](3d-capture-lighting-substance-3d-sampler.md).
