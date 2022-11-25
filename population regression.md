---
alias: 
tags: COMMERCE_1DA3
created: Saturday April 2, 2022; 14:41:29 
---
# Population regression
[[sample regression line|Sample regression lines]] are useful, however population regression line is what we usually need. 

We can imagine a **true line** that summarizes the relationship between $x$ and $y$ for the **entire population**. 

This true line isn't the same as the sample regression line we derive from a sample.

Assume the true population regression line is

> $$\mu_y=\beta_0+\beta_1x$$

where $\mu_y$ is the true population mean of all the $y$'s of the population for any given $x$. 

From samples, we know each $x$ in the population can have multiple $y$'s associated with it. 

```ad-note
We're assuming an idealized case where the points $(x, \mu_y)$ are exactly linear.
```

The values on the line will misss most of the $y$'s. We can find [[linear model|residual]]s: 

> $$\epsilon = y - \mu_y$$

Therefore, 

> $$y = \beta_0 + \beta_1x + \epsilon$$

## Population vs. Sample
Regression inference:

Collect a sample and *estimate the population's $\beta$'s* by finding a regression line

$$\hat{y}=b_0+b_1x$$

where $b_0\approx \beta_0$ and $b_1\approx \beta_1$. 

The residuals $e = y-\hat{y}$ are the sample based versions of $\epsilon$. 

Using sample information, we can create [[confidence interval]]s and [[hypothesis testing|hypothesis tests]] for population parameters. 

| Sample | Population |
| ------ | ---------- |
| $e$    | $\epsilon$ |
| $b_0$  | $\beta_0$  |
| $b_1$  | $\beta_1$  |

Estimating population parameters using sample information is based on:
1. Assuming linearity
    - make a scatterplot of the data to check for linearity
2. Assuming independence
    - fit a regression and find the residuals
    - plot the residuals against time (if possible) and check for evidence of patterns
3. Assuming equal variance
    - make a scatterplot of the residuals against $x$ or the predicted values. This plot shouldn't exhibit a "fan" or "cone" shape
4. Assuming normal population
    - make a histogram and normal probability plot of the residuals

## Error of $b_1$
For similar samples, the **standard error of the slope** is a measure of the variability of $b_1$ about the true slope $\beta_1$. 

This variation is calculated using the [[linear model|standard error]] of $b_1$: $SE(b_1)$.

Three aspects affect $SE(b_1)$:

1. Spread of the $y$'s around the **sample** regression line, or the [[linear model|residual]] standard deviation $s_e$.
    - Less scatter around the line means the slope will be more consistent between samples, so lower $b_1$ variation and thus lower $SE(b_1)$. 
2. Spread of $x$'s around their mean, or standard deviation of $x$, $s_x$. 
    - Increassing $s_x$ decreases $SE(b_1)$ since we'll have more entries for different values of $x$.
3. Sample size, $n$.
    - Increasing $n$ decreases $SE(b_1)$ since we have more consistent estimates between samples.
    
> $$SE(b_1)=\frac{s_e}{s_x\sqrt{n-1}}$$

When we standardize the slopes by subtracting the mode mean and dividing by their standard error, we get a [[confidence interval and hypothesis testing for the population mean|Student's t]] model with $n-2$ degrees of freedom:

> $$t_{n-2}\sim \frac{b_1-\beta_1}{SE(b_1)}$$

This t-statistic can be used for hypothesis testing and confidence intervals.

So, we can test $H_0: \beta_1=\beta_{10}$ vs. $H_A: \beta_1\neq\beta_{10}$ where we usually take $\beta_{10}=0$ to test whether the slope is significantly different from $0$. 

Overall,

> $$SE(b_1)=\frac{s_e}{s_x\sqrt{n-1}}$$

> $$s_e = \sqrt \frac{\sum(y-\hat{y})^2}{n-2}$$

> $$s_x = \sqrt \frac{\sum(x-\overline{x})^2}{n-1}$$

## [[confidence interval|Confidence Interval]] for $\beta_1$

> $$b_1\pm t^*_{n-2}\times SE(b_1)$$

If $\beta_{10}$ isn't in the confidence interval, we can reject the null hypothesis. 
