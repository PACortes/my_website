---
date: "2021-09-28"
linkTitle: dplyr
summary: En este taller, aprenderemos a manipular nuestros datos usando el paquete `dplyr`.
title: "dplyr: manipulación de datos"
type: book
---

{{< figure src="dplyr_logo.png" >}}

{{< toc hide_on="xl" >}}

# ¿Qué es `dplyr`?

Es un paquete de R que contiene una colección de funciones para realizar operaciones de manipulación de datos, tales como : filtrar por fila, seleccionar columnas específicas, reordenar filas, añadir nuevas filas, agregar datos, entre muchas otras.

Lo fantástico de este paquete es que cada función en `dplyr` hace solo una cosa, de manera muy rápida y efectiva.


# Base de datos

Para el presente tutorial, utilizaremos el conjunto de datos **flor Iris**,  multivariante introducido por Sir. Ronald Fisher en su artículo de 1936, [The use of multiple measurements in taxonomic problems](https://onlinelibrary.wiley.com/doi/10.1111/j.1469-1809.1936.tb02137.x).


![](/courses/ggplot2/scatterplot_files/iris.png)

La base de datos **iris** viene incluida en R y contiene las mediciones en centímetros de las variables longitud de los pétalos (**Petal.Length** y **Petal.Width**) y sépalos (**Setal.Length** y **Setal.Width**) de 50 flores de tres especies (**Species**) del género Iris: *Iris setosa*, *Iris versicolor* e *Iris virginica*. 


## Enlaces de interés

* [dplyr](https://dplyr.tidyverse.org/)

* [Conjunto de datos iris](https://es.wikipedia.org/wiki/Conjunto_de_datos_flor_iris)


{{< cta cta_text="Comencemos con el taller" cta_link="select" >}}
