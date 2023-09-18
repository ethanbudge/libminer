
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

[![R-CMD-check](https://github.com/ethanbudge/libminer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/ethanbudge/libminer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of libminer is to test package development for a workshop.
Don’t actually use this!

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ethanbudge/libminer")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(libminer)
## basic example code
lib_summary(sizes = TRUE)
#>                                                                                         Library
#> 1                          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
#> 2 /private/var/folders/m_/j4nrbkts2t51lhpxncv3l1mr0000gn/T/RtmpyRPP1M/temp_libpath16797500dab26
#>   n_packages   lib_size
#> 1        391 1783065351
#> 2          1      37444
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
