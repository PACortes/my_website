---
date: "2021-09-19"
linkTitle: ggplot2
summary: En este taller, aprenderemos a visualizar nuestros datos usando el paquete ggplot2.
title: "ggplot2: Visualización de datos"
type: book
---

{{< figure src="ggplot2_logo.png" >}}

{{< toc hide_on="xl" >}}

## Resumen

- Fundamental {{<hl>}}Python programming skills{{</hl>}}
- {{<hl>}}Statistical concepts{{</hl>}} and how to apply them in practice
- Gain experience with the {{<hl>}}Scikit{{</hl>}}, including data visualization with {{<hl>}}Plotly{{</hl>}} and data wrangling with {{<hl>}}Pandas{{</hl>}}

## ¿Qué es ggplot2?

ggplot2 es un paquete de visualización altamente versátil que permite crear gráficos elegantes y atractivos.

El paquete ggplot2 implementa un único sistema para describir y construir gráficos, el cuál funciona en capas (se agrega una a una) y se aplica a diferentes tipos de visualizaciones. 

En general, ggplot2 divide un gráfico (plot) en tres partes fundamentales diferentes: 

```r
ggplot(data = MisDatos, mapping=aes(x=Variable1, y =Variable2))+ geom_function()
```

## Visualizaciones a realizar

{{< list_children >}}


## Enlaces de interés


{{< cta cta_text="Comencemos con el taller" cta_link="python" >}}
