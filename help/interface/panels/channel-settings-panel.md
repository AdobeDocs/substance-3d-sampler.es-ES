---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/interface/panels/channel-settings-panel.html"
breadcrumb-title: ''
description: Aprenda a utilizar el panel Configuración de canal de Substance 3D Sampler para administrar los canales de material y controlar la visibilidad de los canales.
helpx_creative_field: ""
helpx_description: Sampler > Interface > Panels > Channel Settings panel
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Panel Configuración de canal
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '483'
ht-degree: 1%

---


# Panel Configuración de canal

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


El panel **Configuración de canal** controla la lista de canales calculados para tu material actual. Puedes gestionar la visibilidad de los canales, añadir o eliminar canales de tu material, o cambiar el modelo de material que se está utilizando.

</td>
<td style="border: 0;" valign="top">

![El panel de configuración del canal.](../../assets/6.0_ChannelSettingsPanel.png)

</td>
</tr>
</table>

## Modelo de material

Utilice este menú desplegable para seleccionar la estructura de sombreado utilizada para procesar el material. Las opciones del **panel de configuración de canal** cambiarán en función del modelo de material seleccionado.

Al cambiar el modelo de material, la pila de capas deberá volver a calcularse para el nuevo modelo y se dispondrá de diferentes canales. Sampler intenta minimizar la pérdida de datos en la conversión; sin embargo, es posible que el cambio resulte en sutiles diferencias en apariencia con un nuevo modelo de material.

>[!NOTE]
>
> Es posible cambiar de Adobe Standard Material (ASM) a OpenPBR, pero actualmente no es posible cambiar de OpenPBR a ASM.


## Canales de material

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">


Esta sección muestra la lista de canales que se calculan de forma predeterminada en función del flujo de trabajo.

Puedes usar el **botón Editar lista** para abrir la **selección de canales** y cambiar los canales que se calculan para tu material.

</td>
<td style="border: 0;" valign="top">

![El panel Configuración de canal con la sección Canales de material resaltada](../../assets/6.0_ChannelSettingsPanel_MaterialChannels.png){width="200px"}

</td>
</tr>
</table>

>[!NOTE]
>
> Algunos materiales de Substance Source no emiten canales de oclusión de ambiente u opacidad, por ejemplo. Aunque el canal de opacidad esté marcado como &quot;calculado&quot;, si el archivo de Substance no genera, Sampler no lo genera.

### Selección de canal

La ventana de selección de canales le permite añadir o quitar canales del material.

![Captura de pantalla de la ventana de selección de canales con Adobe Standard Material seleccionado como Modelo de material.](../../assets/6.0_ChannelSelectionWindow.png)

Para agregar un canal a su material, seleccione un canal disponible y use el botón **>**.
Para quitar un canal del material, selecciónelo en la **lista Canales seleccionados** y use el botón **&lt;**.
Puedes añadir todos los canales disponibles a tu material con el botón **** o eliminar todos los canales de tu material con el botón **≪**.

También puedes usar los ajustes preestablecidos para seleccionar rápidamente una lista de canales para tu material. De forma predeterminada, Sampler incluye varios ajustes preestablecidos, pero también puede crear los suyos propios:

1. Añade los canales deseados a tu material.
1. Utilice el **botón Guardar como ajuste preestablecido**.
1. Asigne un nombre al ajuste preestablecido.

>[!NOTE]
>
>Al guardar un ajuste preestablecido, este no se aplica al material.

## Canales personalizados

Alternar canales adicionales que no se incluyen con el flujo de trabajo seleccionado de forma predeterminada.

<table>
<tr style="border: 0;">
<td style="border: 0; width: 30%" valign="top">

Cada canal personalizado tiene dos opciones que puede utilizar para controlarlo:

1. Utilice el selector Visibilidad para mostrar u ocultar el canal en la vista 2D.
2. Use el **botón Automático** para cambiar si el canal se calcula automáticamente.
   * Cuando se activa, el canal se calcula si una capa por encima de él en la pila lo solicita.
   * Cuando se apaga, el canal siempre se calcula.

</td>
<td style="border: 0;" valign="top">

![Panel de configuración de canal con la sección Canales personalizados resaltada.](../../assets/6.0_ChannelSettingsPanel_CustomChannels.png){width="200px"}


</td>
</tr>
</table>



