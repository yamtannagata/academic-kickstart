---
title: Automatización en Datamine Studio RM
author: Yamtan Nagata
date: '2020-07-11'
slug: automatizacion-en-datamine-studio-rm
categories:
  - Datamine
  - Studio RM
  - JavaScript
tags: []
subtitle: ''
summary: 'Un alcance a la automatización de procesos en Datamine usando Macros y Scripts'
authors: []
lastmod: '2020-07-11T00:20:23-05:00'
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

En palabras simples, una **macro** es una serie de instrucciones, una secuencia de _procesos_ y _comandos_, listados en formato de texto simple y guardados en un archivo con extensión (.mac) que puede ser leído por Studio RM y conseguir que realice un mismo proceso usando los mismos parámetros de forma repetitiva, las veces que sean necesarias.

Bajo ese mismo enfoque, un **script** es algo un poco más complejo, ya que debe contar con una interface gráfica diseñada en HTML, dentro de la cual se introduce un script, que puede estar escrito en JavaScript o VBScript; es gracias a dicha interface gráfica que podemos interactuar con archivos propios de Studio RM y que se encuentran dentro o fuera de la carpeta donde estamos trabajando nuestro proyecto de estimación de recursos.
