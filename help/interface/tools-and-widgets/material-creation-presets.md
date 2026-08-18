---
breadcrumb-title: ''
description: Aprende a usar plantillas de materiales en Substance 3D Sampler para crear rápidamente materiales complejos y realistas aplicando efectos físicos avanzados mediante puntos de partida sencillos y listos para usar.
user-guide-description: ''
user-guide-title: ''
title: Ajustes preestablecidos de creación de materiales
source-git-commit: 8777fdda4545110ed765f1d275c35bd11e71903b
workflow-type: tm+mt
source-wordcount: '610'
ht-degree: 2%

---


# Ajustes preestablecidos de creación de materiales

Las plantillas de creación de materiales proporcionan puntos de partida predefinidos para los materiales de construcción con un comportamiento físico avanzado. Cada plantilla configura el modelo de material, los canales activados y los parámetros predeterminados necesarios para un tipo específico de superficie, lo que le permite crear materiales complejos rápidamente, manteniendo un control total sobre el resultado. Las plantillas están disponibles al crear un nuevo material y se pueden utilizar con modelos de material de OpenPBR y ASM.

![La ventana Crear material nuevo](../../assets/6.0_materialPresets.png)

>[!TIP]
> Puede obtener más información sobre la creación de materiales avanzados que aprovechen los canales de pelusa, subsuperficial y de revestimiento [aquí.](../../features-and-workflows/create-advanced-materials/advanced-materials.md)

## Creación de un material a partir de una plantilla

Para crear un material utilizando una plantilla:

Abra el cuadro de diálogo Crear material nuevo. Seleccione una plantilla de las pestañas Predefinidas o Personalizadas. Ajuste la configuración del material (nombre, resolución, modelo de material, canales). Haga clic en Crear para empezar a trabajar con el material configurado.

La plantilla seleccionada define la estructura inicial del material, incluidos los canales que están activados y cómo se configuran en la pila de capas.

## Categorías de ajustes preestablecidos

### Plantillas predefinidas

Las plantillas predefinidas son configuraciones de materiales listas para su uso diseñadas para cubrir comportamientos de materiales físicos comunes. Codifican prácticas recomendadas y configuraciones de canal recomendadas para cada caso de uso. Las plantillas predefinidas disponibles incluyen:

- Material base Material estándar basado en datos físicos con canales utilizados habitualmente activados. Utilice esta plantilla para materiales simples o genéricos que no requieran un comportamiento especializado.

- Anisotropía Configura el material para reflejos dependientes de la dirección, adecuado para metales cepillados o superficies con microdetalles orientados.

- Recubrimiento Añade una capa reflectante secundaria en la parte superior del material base, lo que permite efectos de capa transparente o similares al barniz.

- Fuzz Permite crear efectos de superficie suaves y dispersantes de luz que se utilizan para tejidos, fibras o materiales con un aspecto aterciopelado.

- Subsuperficie Activa el transporte de luz subsuperficial para materiales como cera, plásticos o superficies orgánicas donde la luz penetra por debajo de la superficie.

- Transparente Configura el material para la transmisión de luz, adecuado para materiales transparentes como vidrio o finos.

Cada ajuste preestablecido predefinido configura automáticamente los canales necesarios y los valores predeterminados, lo que reduce la configuración manual y la complejidad técnica.

### Ajustes preestablecidos personalizados

Los ajustes preestablecidos personalizados le permiten reutilizar sus propias configuraciones de materiales. Cualquier ajuste preestablecido de material que cree se puede guardar como una plantilla personalizada y aparecerá en la pestaña Personalizados . Esto permite la creación uniforme de materiales en todos los proyectos o equipos, utilizando estándares compartidos y configuraciones de canal.

## Detalles de ajustes preestablecidos

El panel Detalles del ajuste preestablecido muestra y controla los ajustes utilizados para crear el nuevo material.

### Nombre del activo

Define el nombre del activo material que se creará.

### Resolución

Controla la resolución predeterminada de los mapas de material (Anchura y Height). Esta resolución se aplica a todos los canales activados cuando se crea el material.

### Modelo de material

Especifica el modelo de material utilizado por el material:

OpenPBR para flujos de trabajo modernos y estandarizados basados en física ASM para la compatibilidad con tuberías existentes

La plantilla seleccionada se adapta al modelo de material elegido.

### Añadir material base

Cuando está activada, Sampler crea una capa de relleno base utilizando un material base compatible con la plantilla seleccionada. Esto proporciona un resultado visual inmediato y un punto de partida útil. El material base se adapta tanto al OpenPBR como a los modelos de material de ASM.

### Aplicar valores de miniatura preestablecidos

Cuando se activa, el material se inicializa con los valores utilizados para generar la miniatura de vista previa de la plantilla, en lugar de valores predeterminados neutros. Esto ayuda a demostrar el comportamiento previsto de la plantilla y a disponer de una base visual sobre la que empezar a crear.

### Editar lista

Haga clic en **Editar lista** para personalizar el conjunto de canales antes de crear el material. Puede habilitar o deshabilitar canales según sea necesario, o guardar la configuración como una nueva plantilla personalizada.