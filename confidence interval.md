---
alias: probability of error, significance level, margin of error, critical value
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 18:49:31 
---
# Confidence interval
**Confidence interval**: a range of values ($[\hat{p}-kSE(\hat{p}),\hat{p}+kSE(\hat{p})]$) that, with a certain level of confidence (%) contains the [[population and parameters|population parameter]].

We can have confidence intervals with any desired confidence levels. The higher the confidence level, the wider the interval. 

Confidence level = $100(1-\alpha)\%$ where $\alpha$ is the **probability of error** or the **significance level**.

The confidence interval, in general, can be expressed by: `point estimate` ($\hat{p}$) $\pm$ `margin of error` ($ME$).

The *extent* of that interval on either side of $\hat{p}$ is called the **margin of error (ME)**

The more confident we want to be, the larger the ME must be. 

To find ME, find the [[standardizing|z-score]] at $\frac{\alpha}{2}$ ($z_{\alpha/2}$) and take its absolute value; then you have $ME=z_{\alpha/2}\sqrt\frac{\hat{p}(1-\hat{p})}{n}$, which leads to the interval

$$\left[\hat{p}-z_{\alpha/2}\sqrt\frac{\hat{p}(1-\hat{p})}{n},
\hat{p}+z_{\alpha/2}\sqrt\frac{\hat{p}(1-\hat{p})}{n}\right]$$

This formula is valid only if $\hat{p}$ (approximately) follows a [[normal distribution]]. This condition is evaluated at the sample proportion $\hat{p}$ by checking for $n\hat{p}\geq 10$ and $n(1-\hat{p})\geq 10$. 

## Certainty vs. precision
Every confidence interval is a balance between **certainty** and **precision**. As ME grows, certainty grows, but precision decreases. 

For any confidence level, the number of SEs we must stretch out on either side of $\hat{p}$ is called the **critical value** $z_{\alpha/2}=z^*$. 

## Choosing the sample size
To get a narrower confidence interval without giving up confidence, we must choose a larger sample. 

For a desired ME, the minimum sample size $n$ required to estimate a $100(1-\alpha)\%$ confidence interval for the population proportion $p$ is
$$n=(\frac{z_{\alpha/2}}{ME})^2\hat{p}(1-\hat{p})$$

where $\hat{p}$ is a reasonable estimate of $p$ in the planning stage. We usually pick $\hat{p}=0.5$ as conservative measure. 

Usually, a margin of error of $5\%$ or less is acceptable. However, to cut the margin of error in half, you will have to quadruple the sample size. 