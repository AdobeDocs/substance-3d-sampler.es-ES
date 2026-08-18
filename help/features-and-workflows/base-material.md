---
breadcrumb-title: ''
description: Aprende a usar el Material base en Sampler, un gran punto de partida para la edición eficiente de materiales.
title: Usar como mapa de bits
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 4%

---


# Material de base

**Material base** es una capa de material fundamental diseñada para proporcionarte un punto de partida rápido y flexible al crear materiales en Sampler. Expone un conjunto completo de parámetros que se adaptan automáticamente al **modelo de material** que usa tu material (OpenPBR o ASM), lo que te permite crear cualquier cosa, desde superficies simples hasta materiales complejos y físicamente ricos.
Tanto si estás empezando desde un ajuste preestablecido como si estás creando un material desde cero, el Material base te garantiza que siempre empieces desde una **base clara, predecible y editable**.

## Concienciación de modelo de material (OpenPBR vs ASM)

El Material base es **compatible con el modelo de materiales**.
Esto significa que las propiedades disponibles y los valores predeterminados cambian dependiendo de si el material se crea mediante:

* OpenPBR
* ASM (Adobe Standard Material)

Aunque ambas versiones tienen el mismo propósito, exponen **diferentes grupos de parámetros y comportamientos**, que coinciden con el modelo de material subyacente:

### Material base de OpenPBR

Los grupos de parámetros incluyen:

* Base
* Especular
* Transmisión
* Subsuperficie
* Abrigo
* Fuzz
* Emisión
* Película fina
* Geometría
* Varios

Estos parámetros se alinean con la representación unificada y basada físicamente del OpenPBR y están diseñados para interoperabilidad en todo el ecosistema 3D.

### MATERIAL BASE de ASM

Los grupos de parámetros incluyen:

* Superficie
* Absorción
* Dispersión
* Translucidez
* Abrigo
* Brillo
* Emisión
* Geometría

Este diseño refleja el modelo de sombreado de ASM y garantiza la continuidad con los flujos de trabajo existentes basados en ASM.

>[!NOTE]
>
>El Material base siempre se adapta al modelo de material del material al que se aplica. Un Material base aplicado a un material de OpenPBR no mostrará los parámetros de ASM, y viceversa.

## Valores uniformes y asignaciones personalizadas

Para cada parámetro expuesto, el Material base proporciona dos formas de trabajar:

### Valores uniformes (predeterminado)

De forma predeterminada, los parámetros utilizan valores uniformes (reguladores o selectores de color).
Esto te permite definir rápidamente el aspecto general de tu material sin entradas de textura.

Los valores uniformes son ideales para:

* Bloqueo de materiales
* Creación de superficies limpias y sencillas
* Establecimiento de un punto de partida visual

### Mapas personalizados

Si ya tienes mapas de textura, puedes **invalidar cualquier valor uniforme** habilitando su **entrada de mapa personalizado**.

* Alternar la opción de asignación personalizada para el parámetro
* Conecta la textura existente
* El mapa reemplaza completamente el valor uniforme

## Ajustes preestablecidos

El Material base incluye un conjunto de **ajustes preestablecidos**, visibles como miniaturas en la parte superior del panel Propiedades.
Los ajustes preestablecidos proporcionan:

* Valores de Material base preconfigurados
* Una forma rápida de empezar desde una configuración visualmente significativa
* Puntos de partida coherentes y legibles para tipos de superficie comunes

La selección de un ajuste preestablecido no bloquea el material. Todos los parámetros se pueden editar por completo.

## Aplicación de valores preestablecidos al crear un material

Al crear un material nuevo, puede optar por aplicar valores preestablecidos desde el panel Crear material nuevo.
Qué hace esto

* Reemplaza los valores predeterminados del Material base por los valores representados por la miniatura de ajuste preestablecido seleccionada
* Proporciona un punto de partida visual inmediato, en lugar de valores predeterminados neutros
* Ayuda a reducir el efecto de &quot;página en blanco&quot; al iniciar un material nuevo

Lo que no hace

* No hornea ni congela los valores
* No impide que se sigan editando
* No añade mapas de textura automáticamente

Puedes pensar en ello como elegir dónde empezar, no limitar a dónde puedes ir.

## Activación del canal: Un paso crítico

Para que un parámetro de Material base tenga un efecto visible, el canal correspondiente debe estar activado en los ajustes de canal del material.

### Prácticas recomendadas

Antes de ajustar un parámetro, compruebe que su canal está activado
Activa solo los canales que necesitas para mantener tu material limpio y eficaz