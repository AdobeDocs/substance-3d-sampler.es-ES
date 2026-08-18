---
helpx_url: "https://helpx.adobe.com/substance-3d-sampler/technical-support/configuration/nvidia-driver-settings.html"
breadcrumb-title: ''
description: Aprenda a configurar los ajustes del controlador NVIDIA para Substance 3D Sampler con el fin de optimizar el rendimiento de la GPU y resolver comportamientos lentos.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Configuration > NVIDIA Driver Settings
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Configuración de controlador NVIDIA
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 0%

---


# Configuración de controlador NVIDIA

Si utiliza una GPU NVIDIA pero el rendimiento es lento, existen dos causas comunes:

1. Faltan controladores o no están actualizados
1. Sampler está usando una GPU incorrecta

## Actualizar controladores

Para actualizar los controladores NVIDIA:

1. Vaya a la página de descarga de controladores de NVIDIA: <https://www.nvidia.com/Download/index.aspx?lang=en-us>
1. Seleccione el modelo de GPU y descargue los controladores.
1. Instale los controladores con el archivo descargado.

Una vez instalados los controladores más recientes, abra Sampler para ver si ha mejorado el rendimiento. Si el rendimiento es lento, es posible que Sampler esté utilizando una GPU incorrecta.

## Configurar Sampler

Para comprobar qué GPU está utilizando Sampler, haga lo siguiente:

![](../../assets/nvidiacontrolpanel.png)

1. Abra el Panel de control de NVIDIA. Para abrir el Panel de control de NVIDIA, realice una de las siguientes acciones:
   1. Busque el Panel de control de NVIDIA mediante el menú Inicio
   1. En la bandeja del sistema, haga clic con el botón derecho en el icono de Geforce y seleccione el Panel de control de NVIDIA.
1. En el Panel de control de NVIDIA, seleccione Administrar configuración 3D en el menú de la izquierda.
1. Seleccione la ficha Program Settings (Configuración del programa).
1. En Seleccionar un programa para personalizar, utilice el menú desplegable para buscar Sampler.
1. Si Sampler no aparece en el menú desplegable, utilice Agregar.
   1. Busque la ubicación de instalación de Sampler (la ubicación de instalación predeterminada es **C:/Archivos de programa/Adobe/Adobe Substance 3D Sampler**).
   1. Seleccione **Adobe Substance 3D Sampler.exe** en la ubicación de instalación.
1. Con Sampler seleccionado, en &quot;Seleccionar el procesador gráfico preferido para este programa:&quot; seleccione &quot;Procesador NVIDIA de alto rendimiento&quot;.
1. Haga clic en Aplicar.

Una vez que haya seguido este proceso, abra Sampler para ver si el rendimiento ha mejorado.
