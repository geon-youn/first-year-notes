---
alias: correlation coefficient, r, covariance, quantitative variables condition, linearity condition, outlier condition
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 14:06:16 
---
# Understanding correlation
**Correlation coefficient (r)**: a measure ($-1\leq r\leq 1$) that evaluates the [[scatterplot|direction]] and strength of linear association between two [[types of variables|quantitative]] [[data value|variable]]s.

| Correlation coefficient | Meaning                             |
|:-----------------------:| ----------------------------------- |
|         $r=-1$          | perfect negative linear association |
|          $r=0$          | no linear association               |
|          $r=1$          | perfect positive linear association |

If $z_x$ and $z_y$ are the [[standardizing|z-score]]s of the two variables and $n$ is the sample size,

$$r=\frac{\sum z_xz_y}{n-1}$$
$$r=\frac{\sum (x-\overline{x})(y-\overline{y})}{\sqrt{\sum(x-\overline{x})^2\sum(y-\overline{y})^2}}=\frac{\sum(x-\overline{x})(y-\overline{y})}{(n-1)s_xs_y}$$

**Covariance**: an alternative to the correlation coefficient; units: `(units of x)*(units of y)`.
$$\operatorname{cov}(x,y)=rs_xs_y=\frac{\sum(x-\overline{x})(y-\overline{y})}{n-1}$$

Unlike correlation coefficient, covariance depends on the "units of measurement" for both variables and has no bounds on values. 

```ad-warning
Before you use correlation, you must check these three conditions:
- **Quantitative variables condition**: correlation applies only to quantitative variables.
- **Linearity condition**: correlation measures the strength only of linear association.
- **Outlier condition**: unusual observations can distort the correlation.
``` 

```ad-abstract
title: Correlation properties
- The sign of a correlation coefficient gives the direction of the association.
- Correlation is always between -1 and +1. 
- Correlation treats $x$ and $y$ symmetrically.
- Correlation has no units.
- Correlation is not affected by changes in the center or scale of either variable.
- Correlation measures the strength of the linear association between two variables.
- Correlation is sensitive to unusual observations. 
```

**Correlation table**: displays the correlations between pairs of variables in a data set.

```ad-example
A correlation table for some variables collected on a sample of Amazon books

|          | # Pages | Width | Thick | Pub year |
| -------- | ------- | ----- | ----- | -------- |
| # Pages  | 1.000   |       |       |          |
| Width    | 0.003   | 1.000 |       |          |
| Thick    | 0.813   | 0.074 | 1.000 |          |
| Pub year | 0.253   | 0.012 | 0.309 | 1.000    | 
```