---
alias: 
tags: COMMERCE_1DA3
created: Tuesday April 5, 2022; 15:10:10 
---
# Multiple regression
For simple regression, the predicted value depends on *only one predictor variable*:

$$\hat{y}=b_0+b_1x$$

For multiple regression, we write the regression model with *more predictor variables*:

> $$\hat{y}=b_0+b_1x_1+b_2x_2+\cdots+b_kx_k$$

Residuals are similar to simple regressions:

> $$e=y-\hat{y}$$

Degrees of freedom is

> $$df=n-k-1$$

where $n$ is the number of cases and $k$ is the number of predictor variables.

Standard deviation of the residuals is 

> $$s_e=\sqrt{\frac{\sum e_i^2}{n-k-1}}=\sqrt\frac{\sum (y-\hat{y})^2}{n-k-1}$$

## Coefficients
Each coefficient takes into account the other predictor(s) in the model. Multiple regression coefficients must always be interpreted *in terms of the other predictors in the model* (hold all other predictors constant).

## Assumptions and conditions
1. Linearity assumption
    - check *each* of the predictors. Each predictor variable must have a linear relationship with the response variable.
    - residuals should show no patterns.
2. Independence assumption
3. Equal variance assumption
    - the variability of the residuals should be about the same for each predictor.
4. Normality assumption
    - check to see if the distribution of residuals is unimodal and symmetric.
    
## Hypothesis testing
Each hypothesis test is concerned with whether the underlying parameters (slopes and intercept) are actually zero: *global test of significance* (is the model any good or is the dependent variable always random). 

Null hypothesis: $H_0:\beta_1=\beta_2=\dots=\beta_k=0$
 - none of the predictor variables in the model actually contribute to the response variable.   
 
Alternative: $H_A:$ at least one $\beta$ is nonzero. 

Hypothesis tests can be done with [[ANOVA]] and [[F statistic]]. 

Similar to ANOVA, the F-statistic here has two degrees of freedom: $F_{k, n-k-1}$

To test the null hypothesis with F distribution, you can
- compare $\alpha$ and $p$-value.
- compare F statistic and F critical.

If the F test leads to the rejection of the null, do the t-test for each coefficient to see if it's significant:
$$\left\{\begin{array}{l}H_0:\beta_j=0\\H_A:\beta_j\neq 0\end{array}\right.$$

The t statistic is the same as the one in [[population regression]] but with different degrees of freedom

> $$t_{n-k-1}=\frac{b_0-0}{SE(b_j)}$$

## Coefficient [[confidence interval]]
The confidence interval for the true population coefficient for a certain predictor variable $b_j$ ($\beta_j$) is

> $$b_j\pm t^*_{n-k-1}\times SE(b_j)$$

Where $t^*_{n-k-1}$ can be found in the t table and $SE(b_j)$ is usually given in the regression table. 