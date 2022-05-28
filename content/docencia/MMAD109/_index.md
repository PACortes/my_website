---
date: "2021-09-19"
linkTitle: MMAD109
summary: En este taller vamos a  introducir el software R.  Aprenderemos herramientas básicas para la visualización y el análisis de datos. Finalmente, aprenderemos a realizar informes automáticos.
title: "MMAD109: visualización y análisis de datos"
type: book
---

{{< figure src="foto1.png" >}}

{{< toc hide_on="xl" >}}


##  Gestión de la contaminación y pasivos ambientales (MMAD119)

La asignatura tiene por objetivo proporcionar al estudiante una base conceptual general sobre los diferentes problemas de contaminación ambiental asociados al desarrollo urbano e industrial y las herramientas e instrumentos de gestión y control que se aplican en Chile y el mundo para manejar la contaminación y los pasivos ambientales del territorio, en el marco de la institucionalidad y normativa vigentes en el país.

## Objetivos del taller

En el presente taller aprenderemos a manejar `R` y `RStudio` como herramienta para poder explorar, visualizar, analizar y comunicar de manera eficaz datos de contaminación atmosférica. 

## ¿Qué es `R`?

`R`  es un tipo de lenguaje de programación con software libre, que, a su vez, es un tipo de lenguaje interpretado. Es decir, los comandos o instrucciones son ejecutados directamente sin ningún tipo de software externo.

El código `R`   es desarrollado actualmente por R Development Core Team, y su proyecto es colaborativo y abierto, por lo que otros usuarios programadores pueden ser partícipes del proyecto mediante la publicación de paquetes que extienden su configuración básica. 

`R`  incluye una amplia variedad de técnicas estadísticas y de visualización de datos.


## ¿Qué es `RStudio`?

`RStudio` es un entorno de desarrollo integrado para `R`. `RStudio` incluye una interfaz gráfica que nos permite interactuar con `R` de una forma más amigable. 

Es importante señalar que `RStudio` es un programa que ejecuta `R` y proporciona herramientas adicionales que son útiles al escribir código `R`, por ende RStudio` y `R` no son lo mismo.


## Definiciones

A continuación, se definen conceptos que serán de utilidad al momento de comenzar a explorar el mundo `R`.

**CRAN**:  The Comprehensive R Archive Network es una red de servidores web en todo el mundo donde podemos encontrar el código fuente R, los manuales y la documentación R, y los paquetes.

**Paquete**: Colección de funciones diseñadas para atender una tarea específica. 

**Instalar un paquete**: Esta acción se realiza una sola vez. Para ello usaremos la función `install.packages()`, dando como argumento el nombre del paquete que deseamos instalar, entre comillas. 

**Cargar  un paquete**: Esta acción se realiza cada vez que iniciemos sesión y que necesitemos utilizar un determinado paquete. Para ello usaremos la función `library()`, dando como argumento el nombre del paquete que deseamos instalar, esta vez sin utilizar comillas. 

`Función`: Serie de operaciones a la que les hemos asignados un nombre. Las funciones aceptan argumentos, es decir, especificaciones sobre cómo deben funcionar.


{{< cta cta_text="Comencemos con el taller" cta_link="sesion01_1" >}}

