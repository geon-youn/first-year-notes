---
alias: SSR, SSE, MSR, MSE, sum of squares regression, sum of squares error, SSTotal, sum of squares total
tags: COMMERCE_1DA3
created: Saturday April 9, 2022; 19:18:28 
---
# ANOVA in regression
With [[ANOVA]] in regression, we look at the variability in the model and the [[linear model|residual]]s. 

The amount of variability is 
1. Present in the original data.
2. Explained by the regression.
3. Remains unexplained by the regression.

The total variability is the sum of the explained and unexplained variabilities

> $$SSTotal=SSR+SSE$$

Where $SSTotal$ measures all the variability that exists in the data and our model combined (with $n-1$ degrees of freedom):

> $$SSTotal_{n-1}=\sum(y-\overline{y})^2$$  

---

Recall that [[spread|variance]] is $$\frac{SSTotal}{n-1}=\frac{\sum(y-\overline{y})^2}{n-1}$$

---

The variability explained by the regression is the sum of squares, regression $SSR$:

> $$SSR_{k}=\sum(\hat{y}-\overline{y})^2$$

since the model is explaining the variability through $k$ predictor variables, the degrees of freedom of $SSR$ is $k$.

The variability left unexplained by the regression is the sum of squares, errors $SSE$ of the residuals left over between the regression $\hat{y}$ and the data $y$:

> $$SSE_{n-k-1}=\sum(y-\hat{y})^2$$

and has degrees of freedom $n-k-1$. 

Then

> $$s_e=\sqrt\frac{\sum e_i^2}{n-k-1}=\sqrt\frac{SSE}{n-k-1}$$

## F-statistic
Like with [[F statistic]], we want a ratio between the average of the errors, so we have

> $$F=\frac{MSR}{MSE}$$

where

$$MSR=\frac{SSR}{k}$$

and

$$MSE=\frac{SSE}{n-k-1}$$

When we see a high value for the F statistic, we know that a lot of the variability in the original data has been explained by the regression.
- *Higher $F$* means more significant models.

A P value is also given in the ANOVA table to show if the F statistic is high enough to imply that the regression is significant overall.
- *Smaller $P$* means more significant models.

## R squared
> $$R^2=\frac{SSR}{SSTotal}=\frac{\text{(explained)}}{\text{(total)}}$$

or 

> $$R^2=\frac{SSTotal - SSE}{SSTotal}=1-\frac{SSE}{SSTotal}$$

Then,

> $$F=\frac{R^2}{1-R^2}\times\frac{n-k-1}{k}$$