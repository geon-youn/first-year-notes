---
alias: Student's t, degrees of freedom, test statistic
tags: COMMERCE_1DA3
created: Thursday March 17, 2022; 14:43:26 
---
# Confidence interval and hypothesis testing for the population mean
## Confidence interval
The [[confidence interval]] for the [[centre|mean]] follows the same logic as the confidence interval for the [[sample mean]]. 

For the population mean, there are two cases:
1. If the population [[spread|standard deviation]] is known.
2. If the population standard deviation isn't known.

Having a [[sample mean]], we can estimate the population mean by creating a confidence interval that will include the population mean with some level of certainty. 

### Case 1

When the population standard deviation is known, we have
$$SD(\overline{y})=\frac{\sigma}{\sqrt n}$$

and therefore, the confidence interval becomes
$$\overline{y}\pm z_{\alpha/2}\times\frac{\sigma}{\sqrt n}$$

### Case 2
If we don't have the population standard deviation, instead of $SD(\overline{y})$, we need to estimate it by $SE(\overline{y})$. 

So we have
$$\text{estimate}\pm\text{margin of error (ME)}$$
$$\overline{y}\pm\text{critical value}\times SE(\overline{y})$$

where, the [[standard error]] is,

$$SE(\overline{y})=\frac{s}{\sqrt{n}}$$

## Hypothesis testing

When we use the standard error for the mean, the distribution is no longer normal. The distribution will be something that we refer to as the **Student's t** distribution.

The new model is a model that is always bell-shaped (just like the [[normal distribution|standard normal distribution]], but with varying standard deviations), but the details change with the sample sizes (as $t\rightarrow\infty$, $SD\rightarrow 1$). 

The **Student's t**-models form a family of related distributions depending on a [[population and parameters|parameter]] known as **degrees of freedom**.

When certain conditions are met, the standardized sample mean

> No longer a [[standardizing|z-score]], but a **t-score** (test statistic)
$$t_{n-1}=\frac{\overline{y}-\mu}{SE(\overline{y})}$$
follows a Student's t-model with $n-1$ degrees of freedom. 

We reject the null hypothesis when the test statistic is more extreme (farther from the mean) than the critical value $t^*_{n-1}$ that we find from the t-score table based on the degrees of freedom (sample size - 1), the confidence level ($\alpha$), and the type of test (one-sided or two-sided). 

When the assumptions and conditions are met, we're ready to find the **confidence interval for the population mean**, $\mu$. The confidence interval extends on either side of the mean by an amount known as the [[confidence interval|margin of error]]:

> $$\overline{y}\pm t^*_{n-1}\times SE(\overline{y})$$

For very small samples ($n<15$), the data should follow a normal model very closely. If there are outliers or strong skewness, $t$ methods shouldn't be used.

For moderate sample sizes ($15 \leq n \leq 40$), $t$ methods will work well as long as the data are [[shape|unimodal]] and reasonable [[shape|symmetric]].

As long as sample size is large enough (and the distribution isn't extremely skewed), we can use the $t$ model without much worry by the [[Central Limit Theorem (CLT)]]. If outliers are present, analyses can be performed twice, with and without the outliers. 