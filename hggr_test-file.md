---
title: "hggr_test-file"
author: "RP"
date: "2024-12-22"
output: 
  html_document: 
    keep_md: true
---
# Loading the required packages


``` r
library(easypackages)
libraries("tidyverse")
```

```
## Loading required package: tidyverse
```

```
## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
## ✔ dplyr     1.1.4     ✔ readr     2.1.5
## ✔ forcats   1.0.0     ✔ stringr   1.5.1
## ✔ ggplot2   3.5.1     ✔ tibble    3.2.1
## ✔ lubridate 1.9.3     ✔ tidyr     1.3.1
## ✔ purrr     1.0.2     
## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
## ✖ dplyr::filter() masks stats::filter()
## ✖ dplyr::lag()    masks stats::lag()
## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors
## All packages loaded successfully
```




# Typing and running a code chunk.


``` r
x <- c(1:10)
y <- x^2
sample_data <- tibble(x, y)
ggplot(data = sample_data, aes(x = x, y = y)) +
    geom_point()
```

![](hggr_test-file_files/figure-html/unnamed-chunk-2-1.png)<!-- -->












