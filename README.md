
# PhytoNokoueTPR

<!-- badges: start -->
<!-- badges: end -->

The goal of PhytoNokoueTPR is to provide interactive material for R lessons on environmental data analysis.

## Installation

You can install the development version of PhytoNokoueTPR from [GitHub](https://github.com/) with:
(If you have done some package management, the package devtools may already be installed. If this is the case, comment the first line below.)

``` r
install.packages("devtools")
devtools::install_github("acapet/PhytoNokoueTPR")
```

## Accessing TP files

We use .Rmd files for interactive practical sessions.
To access the first TP in the editor, copy the following in the console, and execute.

``` r
file.edit(system.file('TP1','TP1.Rmd',package = 'PhytoNokoueTPR'))
```
