---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/features-and-workflows/flatten-layers.html"
breadcrumb-title: ''
description: Aprende a acoplar capas en Substance 3D Sampler para mejorar el rendimiento y simplificar la pila de capas mientras conoces el impacto.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Acoplar capas
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 1%

---


# Acoplar capas

El acoplado de capas es una forma útil de mejorar el rendimiento y simplificar la pila de capas, pero es importante tener en cuenta el impacto que el acoplado de capas puede tener en el proyecto.

## ¿Para qué sirve el botón Acoplar capas?

Acoplar capas fusiona todas las capas de la capa actualmente seleccionada en una sola capa. La capa acoplada resultante tendrá el mismo aspecto que las capas originales, pero ya no podrá realizar ajustes en las capas individuales originales.

### ¿Por qué acoplar capas?

Cada vez que cambie una capa en la pila de capas, Sampler deberá volver a calcular el resultado de esa capa y de todas las capas que haya sobre ella. Cada capa adicional para calcular significa tiempo de procesamiento adicional y uso de memoria. Aplanar varias capas reduce la cantidad de tiempo y memoria necesaria para procesar esas capas. Por ejemplo, en lugar de volver a calcular 10 capas, Sampler solo necesita procesar una única capa.

Además, al acoplar las capas, se obtiene una pila de capas más sencilla, que es más fácil de explorar y comprender.

### ¿Cuándo no debería acoplar las capas?

No es posible acceder individualmente a las capas acopladas en la pila de capas, por lo que no podrá realizar cambios en los parámetros del resultado acoplado. Como resultado, solo debe acoplar las capas si ya no necesita realizar cambios en el resultado de dichas capas.

## Parámetros de capa acoplada

Mientras se pierden los parámetros de las capas originales, las capas acopladas tienen su propio conjunto de parámetros que puede ajustar para controlar cómo se utiliza cada canal resultante.

Para cada canal, puede:

* <b>Uso de salida</b>: Cambie para qué canal se utiliza la salida. Al acoplar capas, se crea un TIFF, se le asigna un nombre para cada canal y se asigna automáticamente a él.
* <b>Opacidad del canal alfa</b>: Alterne si la opacidad se basa en el resultado del canal del Alpha.
* <b>Quitar</b>: eliminar el canal de esta capa. Esto puede resultar útil para los canales que no contienen información útil. Por ejemplo, es una buena idea eliminar un canal de opacidad totalmente blanco, ya que hacerlo liberará memoria sin afectar a los resultados visuales.
