---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/technical-support/technical-issues/startup-issues/application-doesn-t-start-on-linux.html"
breadcrumb-title: ''
description: Obtenga información sobre cómo solucionar problemas de inicio de Substance 3D Sampler en Linux para resolver problemas de inicio de aplicaciones y mensajes de error.
helpx_creative_field: ""
helpx_description: Sampler > Technical Support > Technical Issues > Startup issues > Application doesnt start on Linux
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: La aplicación no se inicia en Linux
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '108'
ht-degree: 0%

---


# La aplicación no se inicia en Linux

Es posible que la aplicación no se inicie en Linux con el siguiente mensaje de error en un terminal:

```
error while loading shared libraries: libicui18n.so.50
```


Esto significa que falta la UCI de la biblioteca ([International Components for Unicode](http://site.icu-project.org/)) o que la versión instalada es demasiado reciente. La aplicación necesita la versión 50.

Para resolver este problema, instale la versión 50 desde el administrador del paquete o [descargue manualmente](http://mirror.centos.org/centos/7/os/x86_64/Packages/libicu-50.2-4.el7_7.x86_64.rpm) la versión que falta al instalarla en **/usr/lib64** .
