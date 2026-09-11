---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/getting-started/system-requirements.html'
breadcrumb-title: ''
description: Revise los requisitos del sistema de Substance 3D Sampler para asegurarse de que el hardware y el software cumplen los estándares de compatibilidad.
helpx_creative_field: ''
helpx_description: Sampler > Getting Started > System requirements
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Requisitos del sistema
user-guide-description: ''
user-guide-title: ''
source-git-commit: cd61972eaf1567863dc8c3549a1c90c84ffee825
workflow-type: tm+mt
source-wordcount: '595'
ht-degree: 1%

---


# Sistemas compatibles

A continuación se muestra una lista de hardware y sistemas compatibles con la aplicación:

>[!WARNING]
>
> Se sabe que los siguientes controladores Nvidia provocan inestabilidad al ejecutar Sampler:
>
> * 610.47
>
> Se recomienda evitar el uso de estas versiones: lo ideal sería utilizar una versión más reciente o, si no hay ninguna versión más reciente disponible, utilizar la versión anterior.

## Windows

|  | Mínimo | Recomendado | Óptimo |
| --- | --- | --- | --- |
| **SO** | Windows 11 de 64 bits, versión 23H2 | Windows 11 Versión de 64 bits 24H1 | Windows 11 de 64 bits, versión 24H2 |
| **CPU** | Intel Core i5 AMD Ryzen 5 | Intel Core i7 AMD Ryzen 7 | Intel Core i9 AMD Ryzen 9 |
| **GPU** | NVIDIA GeForce RTX 2060 Super NVIDIA Quadro RTX 4000 AMD Radeon RX 5700 XT AMD Radeon Pro W5700 | NVIDIA GeForce RTX 3080 NVIDIA Quadro RTX A4000 AMD Radeon RX 6800 XT AMD Radeon Pro W7700 | NVIDIA GeForce RTX 4090 NVIDIA Quadro RTX 5000 Ada Generation AMD Radeon RX 7900 XTX AMD Radeon Pro W7800 |
| **VRAM** | 8 GB | 16 GB | 24 GB |
| **RAM** | 16 GB | 32 GB | 64 GB |
| **Almacenamiento** | SSD con 30 GB de espacio disponible | SSD con 50 GB de espacio disponible | SSD con 70 GB de espacio disponible |

### macOS

|  | Mínimo | Recomendado | Óptimo |
| --- | --- | --- | --- |
| **SO** | macOS 13 Ventura | macOS 14 Sonoma | macOS 26 Tahoe |
| **CPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **GPU** | Apple M1 | Apple M2 Pro | Apple M4 Pro |
| **RAM** | 24 GB | 32 GB | 64 GB |
| **Almacenamiento** | SSD con 30 GB de espacio disponible | SSD con 50 GB de espacio disponible | SSD con 70 GB de espacio disponible |

### Linux

| Empresas | Vapor |
| --- | --- |
| RHEL 8 <br>RHEL 9 | Ubuntu 22.04 |

>[!NOTE]
>
> Si su sistema cumple los requisitos del sistema anteriores, pero el rendimiento sigue siendo lento, es posible que Sampler esté utilizando una GPU incorrecta.
>
> Si utiliza una GPU NVIDIA, [cambie la GPU que Sampler utiliza siguiendo las instrucciones de esta página](../technical-support/configuration/nvidia-driver-settings.md).

## Recomendaciones generales

* Para trabajar en condiciones cómodas, recomendamos un monitor con una resolución superior a 1 MegaPixel y mayor de 1280 píxeles.
* Muchas aplicaciones de Substance dependen de OpenSSL 1.1.1 para la compatibilidad con RHEL8/9. Para los sistemas con versiones más recientes de OpenSSL, deberá proporcionarlo manualmente.

## Configuraciones no compatibles

**Windows**

* No se admiten máquinas virtuales.
* Windows Server no es compatible.

**Mac**

* Solo se admiten configuraciones oficiales de Apple.
* Las eGPU no son compatibles actualmente y pueden presentar problemas de estabilidad.

**Linux**

* Los controladores Mesa en Linux no son compatibles.

**Cualquier plataforma**

* Las GPU integradas no son compatibles con las CPU x86-64 (Intel, AMD).
* No se admite el uso de Sampler en combinación con software de terceros que intercepte llamadas de Sampler a los controladores gráficos. Dicho software incluye:
  * Inyectores de proceso posterior, como los reshaders que aplican gradación de color, efectos de cámara, ...
  * Superposiciones en pantalla como cruces personalizadas, métricas de rendimiento de GPU, máscaras para streaming de vídeo...

## Versiones mínimas del controlador de GPU

A continuación se muestra una lista de las versiones mínimas del controlador de la GPU necesarias para que la aplicación se ejecute sin problemas. Esta lista está sujeta a cambios a medida que se lancen nuevas versiones.

Para descargar nuevos controladores, consulte: [La GPU tiene controladores obsoletos](https://experienceleague.adobe.com/en/docs/substance-3d-painter/using/technical-support/technical-issues/gpu-issues/gpu-has-outdated-drivers).

| SO | NVIDIA | AMD | Intel |
| --- | --- | --- | --- |
| **Windows** | GeForce 551.86 Quadro/RTX 538.33 | Radeon 23.8.1 Radeon Pro / FirePro 24.q2 | 31.0.1015590 |
| **Linux** | 525.116.04 o posterior *o* 535.54.03 o posterior | Radeon 23.20 Pro 23.Q3 | No admitido |

>[!NOTE]
>
> En **Mac OS**, el controlador de la GPU lo proporciona el propio sistema operativo. Actualice a la versión más reciente del sistema operativo para acceder al controlador más reciente.

## Idiomas

La interfaz de software está disponible en los siguientes idiomas:

* Inglés
* Alemán
* francés
* Japanese
* Coreano
* Chino
* Italiano
* Portugués
* Español
