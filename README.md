[![Travis-CI Build Status](https://travis-ci.org/laurivaltteri/testing_rpackaging.svg?branch=master)](https://travis-ci.org/laurivaltteri/testing_rpackaging)

bloodstats
----------

A package with utilities for basic statistics on blood biomarkers.

---
output: github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->

# bloodstats

A dummy package for demo and testing.

## Installation


```r
# # Install devtools if you don't have it already
# install.packages("devtools")
devtools::install_github("mariakalimeri/bloodstats")
```


## Examples


```r
data.frame(var1 = c(1, 2, 3), var2 = c(4, 5, 6)) %>%
  bloodstats::bloodmeans()
```
