---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/features-and-workflows/texture-generators.html"
breadcrumb-title: ''
description: Aprenda a usar generadores de texturas en Substance 3D Sampler para crear texturas y patrones de procedimiento para la creación de materiales.
helpx_creative_field: ""
helpx_description: Substance 3D Sampler
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Generadores de texturas
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 1%

---


# Generadores de texturas

![](../assets/sa_whats-new-screen_v4-3-0_generators.png)

Los generadores de texturas proporcionan un control mejorado sobre la creación de materiales mediante las opciones de <b>ruidos paramétricos, patrones </b>y<b> grunges</b>. Las imágenes generadas se pueden utilizar en mapas de canales o máscaras.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../assets/Capture-decran-2024-01-31-105700.png)

</td>
<td style="border: 0;" valign="top">

Los generadores de texturas son un tipo de recursos de Substance 3D Sampler. Se pueden filtrar en el panel Activos con el icono Generadores de texturas .

</td>
</tr>
</table>

## Cómo usar los generadores de texturas

### Mapas de canales

Arrastre y suelte un generador de texturas en la vista 3D, la vista 2D o la pila de capas y seleccione un canal para utilizarlo.

![](../assets/DndTexgen.gif)

Se creará un filtro de relleno en la pila con el generador de texturas en la entrada derecha. Puede acceder a las propiedades del generador de texturas en el panel de propiedades.

#### Filtros

Algunos filtros como <b>Parquet</b> usan generadores de texturas predeterminados para las máscaras de patrones. Otros trabajan con una imagen o un generador de texturas como el filtro <b>Patrón</b>.\
En los filtros, puedes usar generadores de texturas en cualquier propiedad de imagen, por ejemplo <b>máscaras personalizadas</b>.

Los filtros pueden sugerir generadores con los que trabajar; se muestran en el nuevo selector de recursos, al hacer clic en una propiedad de imagen.

![](../assets/suggested-filter.png)

#### Tutorial

Encontrarás todos los tutoriales de Substance 3D Sampler en nuestra [página de aprendizaje](https://creativecloud.adobe.com/cc/learn/app/substance-3d-sampler).

[Diseño textil con los generadores de texturas de Sampler](https://creativecloud.adobe.com/cc/learn/substance-3d-sampler/web/fabric-texture-generator?locale=en)

[Material de fibra de carbono en minutos con Substance 3D Sampler](https://creativecloud.adobe.com/cc/learn/substance-3d-sampler/web/create-carbon-fiber-material?locale=en)

[Material de tela a cuadros en minutos con Substance 3D Sampler](https://creativecloud.adobe.com/cc/learn/substance-3d-sampler/web/create-plaid-fabric-material?locale=en)

## Cómo crear generadores de texturas personalizados

Puede importar generadores de texturas creados con Adobe Substance 3D Designer mediante el botón *Importar* en las acciones de pila de capas. Se deben crear de una forma específica en Designer para que funcionen correctamente al importarse en Sampler.

### Tipo

Elija &quot;Generador de texturas&quot; como gráfico<b> tipo</b>.

![](../assets/typetexgen.png)

#### Salidas

El nodo de salida de los filtros del filtro debe tener definido el <b>identificador</b> o el <b>uso </b>:

* El resultado principal del generador de texturas no debería tener ningún uso. A continuación, 3D Sampler puede reconocerlo como el resultado principal.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../assets/patternMask.png)

</td>
<td style="border: 0;" valign="top">

![](../assets/PatternMaskusage.png)

</td>
</tr>
</table>

* El <b>resultado secundario</b> del generador de texturas necesita <b>uso</b> para ser usado.\
  Su nombre de grupo sería el <b>Identificador</b> de salida principal.

>[!NOTE]
>
> Si creas tus propios filtros y generadores de texturas para que funcionen juntos, te recomendamos que uses <b>usos personalizados</b> de acuerdo con los <b>identificadores de salida</b>.

<table>
<tr style="border: 0;">
<td style="border: 0;" valign="top">

![](../assets/patterndata2.png)

</td>
<td style="border: 0;" valign="top">

![](../assets/patterndata2usage2.png)

</td>
</tr>
</table>

>[!IMPORTANT]
>
> Si desea que el generador de texturas personalizado esté en una lista de recursos sugeridos de filtro, debe agregar los siguientes datos de usuario en el gráfico de Substance:
> 
> alchemist::sugeredfilters=[NombreFiltro,NombreFiltro2];

>[!NOTE]
>
> Los datos de usuario se pueden usar con [filtros personalizados](../filters/custom-filters.md).

#### Formato

Exportar el filtro como archivo de almacenamiento de Substance (.sbsar)

>[!NOTE]
>
> Puede exponer parámetros de filtro para controlar el filtro directamente en Sampler. Ver instrucciones [aquí](https://experienceleague.adobe.com/en/docs/substance-3d-designer/using/substance-graphs/manage-parameters/exposing-a-parameter)
