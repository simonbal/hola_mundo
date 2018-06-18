Hola Mundo
================
Simon Ballesteros
18 de junio de 2018

R Markdown
----------

Este es un documento R Markdown. Markdown es una sintaxis sencilla de formateo para crear documentos en HTML, PDF, y MS Word. Para mayores detalles sobre el uso de R Markdown ver <http://rmarkdown.rstudio.com>.

Cuando pulsa el boton **Knit** se genera un documento que incluye tanto el contenido como la salida de cualquier trozo de codigo R embebido dentro del documento. Puede incrustar partes de codigo R como este:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Incluyendo graficos
-------------------

Tambien puede insertar graficos, por ejemplo:

![](hola_mundo_files/figure-markdown_github/pressure-1.png)

Note que el parametro `echo = FALSE` fue agregado al trozo de codigo para prevenir la impresion del codigo R que genero el grafico.
