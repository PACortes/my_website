---
date: "2021-09-19"
linkTitle: ggplot2
summary: En este módulo vamos a visualizar nuestros datos usando el paquete `ggplot2`.
title: "ggplot2: Visualización de datos"
type: book
---

{{< figure src="ggplot2_logo.png" >}}

{{< toc hide_on="xl" >}}

## ¿Qué es `ggplot2`?

Paquete de visualización altamente versátil que permite crear gráficos elegantes y atractivos.

`ggplot2` implementa un único sistema para describir y construir gráficos, el cuál funciona en capas (se agrega una a una) y se aplica a diferentes tipos de visualizaciones. 

La sintáxis básica de `ggplot2` para generar un gráfico es:

`ggplot(data, mapping=aes(x,y))+ geom_function()`


{{< cta cta_text="Comencemos con el taller" cta_link="scatterplot" >}}
