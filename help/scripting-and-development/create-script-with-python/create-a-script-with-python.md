---
helpx_url: "https://helpx.adobe.com/es/substance-3d-sampler/scripting-and-development/create-a-script-with-python.html"
breadcrumb-title: ''
description: Aprenda a crear scripts de Python para Substance 3D Sampler para automatizar flujos de trabajo y ampliar la funcionalidad de la aplicación.
helpx_creative_field: ""
helpx_description: Sampler > Scripting and Development > Create a Script with Python
helpx_experience_level: ""
helpx_learn_topic: ""
helpx_tags: ""
title: Crear un script con Python
user-guide-description: ''
user-guide-title: ''
source-git-commit: 55277f7a92e97bf530dd2a2edf4e16c88bb57793
workflow-type: tm+mt
source-wordcount: '189'
ht-degree: 0%

---


# Crear un script con Python

Esta guía describe cómo crear un sencillo complemento de autoguardado con Python.

## Estructura de script

Los scripts requieren un único archivo PY para poder importarse a Sampler. Puede guardar la secuencia de comandos de ejemplo siguiente como un archivo PY e importarla a Sampler.

## Script de ejemplo

El siguiente script crea automáticamente variaciones de tu material al seleccionar una nueva semilla aleatoria para cada capa del material. Esto es útil para garantizar que el material se pueda utilizar en un caso general en lugar de basarse en semillas aleatorias específicas.

### random\_seed\_versions.py

```
import substance_sampler as ssa 

from random import randrange 

 

## Get the current asset loaded in the layer stack

my_asset = ssa.get_selected_asset() 

 

## Create a list of all layers of the current asset

my_asset_layers = my_asset.get_layers() 

 

## Go through the layers list

for layer in my_asset_layers: 

## Go through all parameters of each layer

    for parameter in layer.parameters: 

## if the parameter is Random Seed, change is value

        if parameter.label == "$randomseed": 

            parameter.value = randrange(10000) 

            print(f"Random Seed for layer {layer.name}: {parameter.value}") 

 
```


El código anterior incluye comentarios para explicar lo que está sucediendo en cada línea.

## Importar el script

Una vez que haya guardado el script anterior como un archivo PY en su equipo, puede importarlo con Editar > Preferencias > Complementos y scripts. Una vez importada, aparecerá la opción **Scripts** en la barra de menús junto a **Archivo** y **Editar**. Desde aquí puede ejecutar el script.

Puedes obtener más información sobre cómo administrar tus scripts [aquí](../manage-installed-plugins-and-scripts.md).
