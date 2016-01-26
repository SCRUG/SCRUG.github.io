---
title: "San Carlos R User Group"
output: 
  html_document: 
    highlight: tango
    theme: flatly
---

## Hola!

Bienvenido al Grupo de Usuarios R en San Carlos, Costa Rica. Si buscas unirte
al grupo, o si quieres ver las reuniones futuras (o pasadas) mira aqui:
[www.meetup.com/San-Carlos-R-User-Group/](http://www.meetup.com/San-Carlos-R-User-Group/). 

In esta pagina presentamos información general y esta abierto a todos los
comentarios y sugerencias para mejorarlo! 

## Instalar R (para participar en los talleres)
Para participar en los talleres necesitas tener instalado una versión reciente
de [R](https://cran.rstudio.com/) y de [RStudio
                                         Desktop](https://www.rstudio.com/products/rstudio/download/).
No importa si usas MS Windows, Mac OSX or Linux en tu computador, para cada uno
hay versiones correspondientes de los programas.

Una vez que tienes R y RStudio Desktop instalado puedes correr el siguiente
código para tengas el mínimo de paquetes necesarios para seguir las
introducciones. En los anuncios de cada taller y charla se mencionaran paquetes
adicionales, pero siempre se asume que tengas lo siguiente:

```{r}
# Para leer datos de Excel: read_xl
install.packages("read_xl")

# Para manipular datos: dplyr, tidyr
install.packages("dplyr", "tidyr")

# Para visualizar datos: ggplot2 
install.packages("ggplot2")

# Para tener datos ejemplo disponible:
install.packages("devtools")
install_github("San-Carlos-RUG/EDAWR-ES")
```

## Recursos para aprender R
Hay muchos recursos sobre R y bastantes en español. Una lista de documentación
en español [esta aquí]().

Quizás la forma mas interactiva (divertida) para comenzar es usando
[swirl-spa](https://github.com/alcideschaux/swirl-spa), la traducción de
[swirl](https://github.com/swirldev/swirl) al español. Esto de dará un buen
punto de partida para empezar a explorar R y acostumbrarte a la sintaxis del
lenguaje.

Ademas recomendamos las presentaciones del grupo de usuarios en Bagota, como la
[introducción a R](http://bogota-r.github.io/intro/) y sobre [gráficas en R](http://bogota-r.github.io/graficas/).

Pero posiblemente lo mas importante es que busques un problema para analizar
que te guste o que sea necesario para tu trabajo/estudio/saludo mental. Hay un
[portal de datos abiertos](http://datosabiertos.gob.go.cr/home/) de Costa Rica,
y muchos recursos mas a nivel internacional.

### Hojas de Referencia en español
* [Domar Datos](http://www.rstudio.com/wp-content/uploads/2015/03/data-wrangling-spanish.pdf)
* [R Markdown](http://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-spanish.pdf)
* [Shiny](http://www.rstudio.com/wp-content/uploads/2015/03/shiny-spanish.pdf)
* [Desarollo de Paquetes](http://www.rstudio.com/wp-content/uploads/2015/03/devtools-spanish.pdf)
* [Visualización de Datos](http://www.rstudio.com/wp-content/uploads/2015/04/ggplot2-spanish.pdf)

### Hojas de Referencia en inglés
*Avisanos si sabes, o has hecho una traducción*

* [R Reference Card 2.0](http://cran.r-project.org/doc/contrib/Baggott-refcard-v2.pdf) - Material from R for Beginners by permission of Emmanuel Paradis (Version 2 by Matt Baggott).
* [Data Mining Refcard](http://www.rdatamining.com/docs/R-refcard-data-mining.pdf) - R Reference Card for Data Mining.
* [Regression Analysis Refcard](http://cran.r-project.org/doc/contrib/Ricci-refcard-regression.pdf) - R Reference Card for Regression Analysis.

## Lista (muy) abreviada de cosas fabulosas
Hay una lista de cosas fabulosas de R llamada
[awesome-r](https://github.com/qinwf/awesome-R). Es un buen recurso para
explorar que mas hay. Aquí presentamos un breve resumen, para hacer resaltar lo
que consideramos son los mas comunes (no necesariamente lo mas fabuloso). 
Mira la [la lista original](https://github.com/qinwf/awesome-R) para ver 
muchas mas cosas por descubrir. Y si no te es suficiente, mira la lista completa
de paquetes en [CRAN](https://cran.r-project.org/web/packages/available_packages_by_name.html).

### Manipulación de datos
*Paquetes para preparar datos.*

* [dplyr](https://github.com/hadley/dplyr) - Fast data frames manipulation and database query.
* [data.table](https://github.com/Rdatatable/data.table) - Fast data manipulation in a short and flexible syntax.
* [reshape2](https://github.com/hadley/reshape) - Flexible rearrange, reshape and aggregate data.
* [readr](https://github.com/hadley/readr) - A fast and friendly way to read tabular data into R.
* [haven](https://github.com/hadley/haven) - Improved methods to import SPSS, Stata and SAS files in R.
* [tidyr](https://github.com/hadley/tidyr) - Easily tidy data with spread and gather functions.
* [broom](https://github.com/dgrtwo/broom) - Convert statistical analysis objects into tidy data frames.
* [lubridate](http://cran.r-project.org/web/packages/lubridate/index.html) - A set of functions to work with dates and times.

## Graphic Displays
*Packages for showing data.*

* [ggplot2](https://github.com/hadley/ggplot2) - An implementation of the Grammar of Graphics.
* [misc3d](https://cran.r-project.org/web/packages/misc3d/index.html) - Powerful functions to deal with 3d plots, isosurfaces, etc.

## Web Technologies and Services
*Packages to surf the web.*

* [shiny](https://github.com/rstudio/shiny) - Easy interactive web applications with R.
* [RCurl](http://cran.r-project.org/web/packages/RCurl/index.html) - General network (HTTP/FTP/...) client interface for R.
* [httr](https://github.com/hadley/httr) - User-friendly RCurl wrapper.
* [XML](http://cran.r-project.org/web/packages/XML/index.html) - Tools for parsing and generating XML within R.
* [rvest](https://github.com/hadley/rvest) - Simple web scraping for R, using CSSSelect or XPath syntax.
* [OpenCPU](https://www.opencpu.org/) - HTTP API for R. 
* [Rfacebook](https://github.com/pablobarbera/Rfacebook) - Access to Facebook API via R.


## R Development
*Packages for packages.*

* [devtools](https://github.com/hadley/devtools) - Tools to make an R developer's life easier.
* [testthat](https://github.com/hadley/testthat) - An R package to make testing fun.
* [roxygen](https://github.com/klutometis/roxygen) - Describe your functions in comments next to their definitions.
* [lintr](https://github.com/jimhester/lintr) - Static code analysis for R to enforce code style.

