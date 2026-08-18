---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/getting-started/export/export-window.html"
breadcrumb-title: ''
description: Aprenda a utilizar la ventana de exportación de Substance 3D Sampler para configurar y exportar materiales en diversos formatos y ajustes preestablecidos.
helpx_creative_field: ""
helpx_description: Sampler > Getting Started > Export > Export Window
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Ventana de exportación
user-guide-description: ''
user-guide-title: ''
source-git-commit: 0f989901713dd30f8f936de2445caf5dc70a9225
workflow-type: tm+mt
source-wordcount: '737'
ht-degree: 0%

---


# Ventana de exportación

Puedes exportar tu activo desde el panel <b>Exportar</b> en la <b>barra derecha</b>.

Las opciones de exportación dependen del tipo de contenido que se exporta.

![Una imagen de la ventana de exportación](../../../assets/6.0_ExportWindowMaterialSettings.png)

Ventana Exportar para una exportación de material.

>[!NOTE]
>
> El panel Exportar también tiene opciones para Enviar el contenido a Substance 3D Designer, Painter o Stager. Esto exportará automáticamente el recurso con la configuración correcta para otras aplicaciones de Substance 3D.

## Configuración general

Las siguientes opciones de configuración están disponibles para todos los tipos de recursos.

* <b>Nombre: </b>Este campo define el nombre del activo que está exportando. Se utilizará como prefijo en el nombre de archivo de los archivos exportados.
* <b>Guardar en: </b>Selecciona el destino de exportación de tu activo. Si lo desea, también puede crear una subcarpeta en la ubicación elegida. Si esta opción está habilitada, la subcarpeta recibirá el nombre del activo.

## Ajustes de material

Al exportar materiales, el panel Ajustes de material de la ventana de exportación dispone de las siguientes opciones:

* <b>Formato</b>: Seleccione un formato de archivo para el activo exportado.
  * <b>SBSAR</b>: Exporte el material para utilizarlo en cualquier aplicación que admita materiales de Substance.
  * <b>SBS</b>: Exporte el material para poder abrirlo en Substance 3D Designer.
  * <b>EXR, JPEG, PNG, TARGA, TIFF</b>: Exporta el material como una colección de archivos de imagen.

>[!NOTE]
>
> La profundidad de bits se fuerza a 16 bits para los canales Normal y Height. Otros canales se exportan en 8/16 bits, dependiendo de sus materiales y los filtros que utilice el activo. Dependiendo del formato de archivo, la profundidad de bits se puede cambiar ya que algunos formatos de archivo no admiten la alta profundidad de bits.

![](../../../assets/export-format.png){width="400px"}

* <b>Ajuste preestablecido </b>(EXR, JPEG, PNG, TARGA, TIFF): Seleccione un ajuste preestablecido para configurar automáticamente la exportación de archivos para una aplicación o canalización determinada.
  * La opción <b>Predeterminado (flujo de trabajo del proyecto)</b> muestra una lista de todos los canales disponibles de tus materiales sin ningún ajuste preestablecido aplicado.
  * Usa el botón <b>Administrar ajustes preestablecidos </b> situado a la derecha del parámetro Ajustes preestablecidos para editar los ajustes preestablecidos o añadir los tuyos propios.<b> </b>
  * [Encontrará más información sobre los ajustes preestablecidos aquí.](../managing-presets.md)

>[!NOTE]
>
> La selección de ajustes preestablecidos no está disponible cuando el formato de exportación es SBS o SBSAR. Para estos formatos, el archivo de salida ya está configurado para utilizarse en todos los productos de Substance e integraciones de Substance.

* <b>Tipo de material </b>(SBSAR, SBS): seleccione si el material exportado se comporta como un material estándar, una pegatina o un atlas. Esta configuración puede cambiar su tratamiento por otras aplicaciones que admiten archivos SBSAR y SBS.

![](../../../assets/screenshot-2023-01-24-at-16-32-58.png)

* <b>Compresión </b>(SBSAR, SBS): Seleccione cómo se comprime el archivo exportado
  * <b>Automático</b>: permite que Sampler determine la configuración de compresión.
  * <b>Mejores</b>: Esta opción genera archivos más pequeños, pero también puede significar tiempos de carga y guardado más largos mientras el archivo está codificado o descodificado.
  * <b>Ninguno</b>: Si no se utiliza compresión, los archivos serán más grandes, pero se cargarán y se guardarán más rápido.
* <b>Resolución (</b>SBSAR, SBS<b>)</b>: Seleccione una resolución de salida para el material.
  * De forma predeterminada, la resolución se basa en los parámetros globales de Sampler. Si selecciona una resolución diferente, Sampler volverá a calcular todos los materiales con esta nueva resolución. Puede afectar al aspecto final de los materiales.

![](../../../assets/SAPR_ResolutionSBSAR.png)

* <b>Resolución </b> (formatos de imagen): Seleccione si la resolución de cada capa se exporta de forma independiente o anule la resolución para que todas las capas se exporten con un tamaño uniforme. Si se selecciona Anular todo, aparecerán las opciones para modificar la resolución de salida.
  * De forma predeterminada, la resolución se basa en la resolución de salida de cada capa. Si selecciona una resolución diferente, Sampler volverá a calcular todos los materiales con esta nueva resolución. Puede afectar al aspecto final de los materiales.

![](../../../assets/SAPR_ResolutionTextures.png)

* **Modelo de material** (todos los formatos están en el ajuste preestablecido predeterminado): Seleccione un estándar de sombreado para las texturas exportadas.
  * Cambiar el Modelo de material afectará a los nombres de archivo de los archivos exportados. Por ejemplo, el OpenPBR utiliza &quot;Metalness&quot; en lugar de ASM que utiliza &quot;Metallic&quot;.

### Más información

El espacio disponible en el disco en la unidad de destino seleccionada está visible en la parte inferior de la <b>ventana de exportación</b>.

>[!NOTE]
>
> <b>El Tamaño físico</b> está configurado durante la creación del material y no se puede modificar durante la exportación.

### Canales

![](../../../assets/SAPR_Channelspreview.png)

En el lado derecho del <b>panel Configuración de materiales</b>, aparece una lista de canales que se pueden exportar y sus resoluciones (canales predeterminados y personalizados).

Cada ajuste preestablecido tiene un conjunto diferente de canales que exportar, y el nombre de los archivos exportados se basa en los nombres visibles en el área <b>Canales que exportar</b>. Puede utilizar la casilla de verificación situada junto a cualquier canal para activar o desactivar la exportación para ese canal.

![](../../../assets/SAPR_Channels_ExportPreset.gif)
