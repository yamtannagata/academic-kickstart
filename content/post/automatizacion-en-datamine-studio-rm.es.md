---
title: Automatización de procesos en Datamine Studio RM
author: Yamtan Nagata
date: '2020-07-11'
slug: automatizacion-en-datamine-studio-rm
categories:
  - Datamine
  - Studio RM
  - JavaScript
tags: []
subtitle: ''
summary: 'Un alcance a la automatización de procesos en Studio RM usando Macros y Scripts'
authors: []
lastmod: '2020-07-12T00:20:23-05:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

Durante el desarrollo de mi trabajo, se han presentado tareas recurrentes que han significado una inversión de tiempo considerable y que en mi opinión son buenas oportunidades para poder pensar un poco, dedicar algo de tiempo y conseguir automatizarlas, de esa forma se pueden llevar a cabo dichas tareas en un considerable menor tiempo, más aún, se puede invertir ese tiempo ganado en interpretar de mejor forma los resultados obtenidos.

Con ese objetivo planteado, me puse a indagar acerca de las opciones con las que contaba el software de estimación de recursos que usabamos en la empresa para poder automatizar sus procesos, que por cierto se trata de [Datamine Studio RM](https://www.dataminesoftware.com/es/solutions/studio-rm-recursos-y-reservas/) y para mi sorpresa, contaba con dos opciones muy interesantes:

* Macros
* Scripts

En palabras simples, una **macro** es una serie de instrucciones, una secuencia de procesos y comandos, listados en formato de texto simple y guardados en un archivo con extensión (.mac) que puede ser leído por Studio RM y conseguir que ejecute una secuencia de comandos usando los mismos parámetros de forma repetitiva, las veces que sean necesarias.

{{< figure library="true" src="automatizacion-en-datamine-studio-rm.es/generic_macro.png" title="**_Figura 01: Ejemplo de una macro en Studio RM_**" lightbox="true" >}}

En la figura 01 pueden observar parte de una de las macros que utilizo, en esa vista se muestran los comandos **TONGRAD**, **EXTRA** y **JOIN** que se van a ejecutar de manera secuencial utilizando los mismos parámetros establecidos previamente.

Bajo ese mismo enfoque, un **script** es algo un poco más complejo, ya que debe contar con una interfaz gráfica diseñada en HTML y un bloque de código, que puede estar escrito en JavaScript o VBScript, es gracias a dicha interfaz gráfica que podemos interactuar con archivos propios de Studio RM y que se encuentran dentro o fuera de la carpeta donde estamos trabajando nuestro proyecto de estimación de recursos.

{{< figure library="true" src="automatizacion-en-datamine-studio-rm.es/generic_interface_script.png" title="**_Figura 02: Ejemplo de una interfaz gráfica_**" lightbox="true" >}}

En la figura 02 pueden apreciar una interfaz gráfica simple que diseñé para un script que realizaba una evaluación dinámica usando el solido en 3D del levantamiento topográfico y el modelo de bloques estimado.

Hasta aquí he tratado de explicar, de forma muy general, con que herramientas podemos contar para automatizar aquellas tareas repetitivas donde intervienen una serie de comandos bajo los mismos parámetros, evitando de esa forma que se cometan errores al intentar repetir el mismo escenario las veces que sean necesarias.

Llego el momento de despedirme, no sin antes invitarlos a revisar la sección de **proyectos** donde encontrarán con más detalle algunas macros y scripts que implementé en mi trabajo.

Hasta pronto.
