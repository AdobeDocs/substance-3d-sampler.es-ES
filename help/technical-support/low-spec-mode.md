---
title: Modo de especificación baja
description: Obtenga información sobre el modo de especificación baja, que Sampler habilita cuando el hardware no cumple los requisitos mínimos del sistema.
hold: true
source-git-commit: 59761aab02bff266047813f1714e3f53ddcb805c
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%
---

# Modo de especificación baja

![](../assets/v6.1/6_1-Checked.png)

Si su hardware no cumple con los [requisitos mínimos](../getting-started/system-requirements.md) de Sampler, Sampler se iniciará automáticamente en modo de especificación baja, que se comporta como [modo de rendimiento](performance-mode.md) sin la opción de cambiar la configuración.

## Limitaciones del modo de especificación baja

El modo de especificación baja activa automáticamente el **modo de rendimiento** con todas las funciones deshabilitadas y una resolución de vista previa máxima de 2048 × 2048.

El modo de especificación baja desactiva:

* **Desplazamiento**
* **Sombras**
* **Seguimiento de rutas**

Además, el modo de especificación baja impide las exportaciones por encima de 2048px × 2048px.

![](../assets/low-spec-mode-export-message.png)

*Este mensaje aparece en la **ventana de exportación**mientras está en **modo de especificación baja**para proporcionar información adicional.*

## ¿Cómo puedo saber si el modo de especificaciones bajas está activado?

Al iniciar Sampler, si el hardware no cumple los requisitos mínimos, aparecerá una ventana que indicará qué requisitos no se cumplen y le ofrecerá la opción de continuar iniciando Sampler.

La imagen siguiente muestra un ejemplo de una máquina con menos de 8 GB de VRAM.

![](../assets/low-device-specs-popup.png)

Si elige **Iniciar de todos modos**, Sampler se iniciará en **modo de especificación baja**. Si ha utilizado la casilla de verificación en el mensaje anterior para no mostrarse e iniciarse de todos modos, seguirá viendo el siguiente banner en los inicios posteriores.

![](../assets/low-spec-mode-banner.png)

Por último, aunque el **modo de especificación baja** está habilitado, no es posible desactivar el modo de rendimiento ni ajustar la configuración del modo de rendimiento.

![](../assets/performance-mode-locked.png)
