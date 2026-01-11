
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->

<!-- badges: end -->

The goal of regexcite is to make regular expressions better.

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("apoorva43/regexcite")
```

## Usage

``` r
library(regexcite)
## basic example code
str_split_one("a, b, c", pattern = ", ")
#> [1] "a" "b" "c"
```
