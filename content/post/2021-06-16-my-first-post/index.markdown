---
title: My first post
author: ''
date: '2021-06-16'
slug: my-first-post
categories: []
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2021-06-16T20:02:48-07:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
output: 
  html_document:
    code_folding: hide
---

<!-- blogdown::new_post(title = "My first post", -->
<!--                    ext = '.Rmarkdown', -->
<!--                    subdir = "post") -->

Hello, does this work? 


```r
library(ggplot2)

x = seq(-1, 1, .01)
y = sin(x^3)/(1 + x^6)

ggplot(mapping = aes(x = x, 
                     y = y)) +
geom_line() +
geom_ribbon(aes(ymin = 0, 
                ymax = y), 
            fill = "pink", 
            alpha = 0.5) +
theme_void() 
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-1.png" width="672" />
