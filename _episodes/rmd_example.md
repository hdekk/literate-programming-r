This is an R Markdown document.


```r
x <- rnorm(1000)
head(x)
```

```
## [1]  1.8704016 -0.7559773  0.0212779 -0.8932887 -1.3446511 -1.1520600
```

`knitr` offers a lot of control over representing different
types of output. We can also have inline `R` expressions
computed on the fly.

The mean $\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_{i}$ of the
1000 random variates we generated is
-0.023.

This figure is computed on-the-fly as well. No more
copy-paste, including for figures:


```r
plot(density(x))
```

![plot of chunk sec_4](figure/sec_4-1.png)