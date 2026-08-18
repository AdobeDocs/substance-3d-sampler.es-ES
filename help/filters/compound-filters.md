---
helpx_url: 'https://helpx.adobe.com/substance-3d-sampler/filters/compound-filters.html'
breadcrumb-title: ''
description: Aprenda a crear y utilizar filtros compuestos en Substance 3D Sampler para combinar varios filtros en capas reutilizables únicas.
helpx_creative_field: ''
helpx_description: Sampler > Filters > Compound Filters
helpx_experience_level: ''
helpx_learn_topic: ''
helpx_tags: ''
title: Filtros compuestos
user-guide-description: ''
user-guide-title: ''
source-git-commit: dc832dc546735437051226f4e1e731b55147b3ea
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 0%

---


# Filtros compuestos

Esta función le permite crear un nuevo tipo de filtros que se representan como una sola capa en la interfaz y que se componen de varios filtros.

>[!NOTE]
>
> Compatible desde Substance 3D Sampler 3.1.0

## Descripción

Un filtro compuesto es un archivo **.ssafilter** que es una carpeta comprimida .7zip de:

* un archivo de descripción con formato JSON: **myfilter\_name.json**
* una carpeta **resources** que contiene:
  * la miniatura del filtro: icon.png
  * dependencias de archivos externos

### Descripción del contenido del archivo

* Nombre: Etiqueta del filtro compuesto que se muestra en la interfaz
* Id.: Identificador único del filtro compuesto
* Categoría: Categoría del filtro compuesto que se utiliza en el panel Activos al agrupar los activos por categoría
* Versión: Número incremental para definir la versión del filtro compuesto.
* Nodo: Lista de nodos que deben utilizarse
* Vínculo: Lista de conexiones entre los diferentes nodos

### Ejemplo

```JSON
{ "SamplerFilter":  
 { 
 "Name": "My filter", 
 "Category": "My filter category", 
 "Id": "my_unique_id", 
 "Version": 2, 
 "Node": [ 
        { 
            "Id": "foo", 
            "InternalFilter": "Foo" 
        }, 
        { 
            "Id": "bar", 
            "File": "bar.sbsar" 
        } 
    ], 
    "Link": [ 
        { 
            "From": { "Node": "FilterInput", "Usage": "baseColor" }, 
            "To": { "Node": "foo", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "FilterInput", "Usage": "normal" }, 
            "To": { "Node": "foo", "Usage": "normal"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "baseColor" }, 
            "To": { "Node": "bar", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "bar", "Usage": "baseColor" }, 
            "To": { "Node": "FilterOutput", "Usage": "baseColor"} 
        }, 
        { 
            "From": { "Node": "foo", "Usage": "normal" }, 
            "To": { "Node": "FilterOutput", "Usage": "normal"} 
        } 
    ] 
}}
```

## Creación paso a paso.

1. Crear un nuevo archivo: **my\_new\_filter.json**
1. Defina su nombre, ID, categoría,...
1. Defina la lista de nodos que necesita
1. Si necesitas archivos externos, crea la carpeta **resources** junto a tu archivo **.json**
1. Agregue sus archivos en la carpeta **resources**
1. Escribir la lista de vínculos entre los nodos
1. Verifique que su JSON sea válido (sin errores tipográficos, coma ausente o corchete ausente)
1. Si quieres una miniatura, añade una imagen **icon.png** en la carpeta **resources**
1. Seleccione el archivo **.json** y la carpeta **resources** y comprímalo

## Documentación

### Versión

El uso de un número de versión le permite realizar un seguimiento de las diferentes iteraciones. Al abrir una pila de capas realizada con una versión anterior del filtro compuesto, se mostrará una notificación para sugerirle que actualice a la versión más reciente.

### Nodo

Un nodo puede hacer referencia a un filtro interno de Substance 3D Sampler. Defina un identificador único **Id** que se usará para definir vínculos entre nodos y la etiqueta del filtro interno **InternalFilter**

```JSON
{ 
  "Id": "step1_identifier", 
  "InternalFilter": "Dirt" 
}
```

Un nodo puede hacer referencia a un archivo SBSAR que no está en Substance 3D Sampler. Defina un identificador único **Id** que se usará para definir vínculos entre nodos y el nombre de archivo **Archivo** del archivo SBSAR. El archivo SBSAR debe estar en una carpeta **resources** junto al archivo .alchfilter.

```JSON
{ 
  "Id": "step1_identifier", 
  "File": "foo.sbsar" 
}
```

>[!NOTE]
>
> **filterImg** y **filterMat** no se pueden usar como id. de nodo

### Vincular

Un vínculo es una descripción de cómo se vinculan dos nodos y se componen de dos elementos:

* De: Uso que debe utilizar el nodo
* Para: Resultado de uso del nodo

Cada elemento tiene 3 atributos:

* Nodo: Declare el **Id** del nodo que desea usar
  * Para establecer la entrada del filtro compuesto, el identificador del nodo es **FilterInput**
  * Para establecer el resultado de la capa compuesta, el identificador del nodo es **FilterOutput**
* Uso: Declare el uso que desea utilizar. Hay 3 opciones:
  * Uso único a la vez y declarar enlace por enlace (baseColor, normal, height, ambienteOclusión, rugosidad, metálico, difuso, specular, brillo, nivel especular, opacidad, emisivo, scan1, ...)
  * También puede especificar una lista [&quot;baseColor&quot;, &quot;normal&quot;]. El primer elemento de la lista de **From** coincidirá con el primer elemento de la lista de **To**. etc...
  * Use **\*** para permitir que Substance 3D Sampler haga la coincidencia entre usos idénticos de todos los usos del nodo De y el nodo A (no es posible combinar **\*** con otro vínculo, mientras que son posibles vínculos únicos y vínculos de lista entre los mismos nodos)
* Grupo: En el caso de que un nodo tenga varias veces el mismo uso, puede utilizar el atributo Group para seleccionar un uso específico. es decir: Para los filtros de mezcla, para obtener el color base del material inferior, use *Material1* y para obtener el color base del material superior use *Material2*

```JSON
Link between two nodes  
{ 
  "From": { "Node": "node1","Usage": "baseColor", "Group": ""}, 
  "To": { "Node": "node2", "Usage": "baseColor"} 
} 
 
Link between outputs of layers below of the compound filter and the compound filter: 
{ 
  "From": { "Node": "FilterInput", "Usage": "*" }, 
  "To": { "Node": "node1", "Usage": "*"} 
} 

Link to declare outputs of the compound filter: 
{ 
  "From": { "Node": "node1", "Usage": "*" }, 
  "To": { "Node": "FilterOutput", "Usage": "*"} 
}
```
