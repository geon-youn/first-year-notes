---
alias: plausibility value, alpha level, significance level
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 20:13:07 
---
# P-value
**p-value (plausibility value)**: is a [[probability]] that answers the question: "how likely would the [[data value|data]] we observed (sample) be (or, likelihood of being produced again), **if** the [[hypothesis testing|null hypothesis]] is true".

A very low p-value indicates that the probability of getting a sample like the one we got (or one that's less likely) is too small. Therefore, the assumption that the null hypothesis is true can't be right. 
 
A very low p-value, depending on your threshold or tolerance, you might
1. conclude that the null hypothesis can't be true, or
2. still believe in the null hypothesis to be true and claim that this was one of those rare cases that a rare sample is drawn.

If the p-value is too small for you to believe that the null hypothesis holds, you have reasons to reject the null hypothesis. 

If the p-value is high (or just not low enough), we can conclude that we haven't seen anything unlikely, so we keep the null hypothesis. 

To solve for the p-value, standardize the distribution and find the probability associated with the [[standardizing|z-score]] of the data depending on the type of hypothesis testing:

| One-sided test ($<$ and $>$) | Two-sided test ($\neq$)         |
| ---------------------------- | ------------------------------- |
| $$P(Z<z)$$ $$P(p<\hat{p})$$  | $$P(Z<-z \cup Z>z)$$            |
| $$P(Z>z)$$ $$P(p>\hat{p})$$  | $$P(p<-\hat{p} \cup p>\hat{p}$$ | 

For the two-sided test, we have to find the probability of deviation in **both** directions from the null hypothesis. For the one-sided test, the p-value is the probability of deviation only *in the direction of the alternative hypothesis*, away from the null hypothesis. 

**Alpha level ($\alpha$)**: the threshold for the p-value, such that if $p < \alpha$, then we have reason to reject the null hypothesis. 

Common $\alpha$ values are $0.1$, $0.05$, and $0.01$. 

We could also use the [[confidence interval|critical value]] instead of the alpha level. Any z-value *more extreme* that the critical value means that the p-value was smaller than the significane level $\alpha$. We can do this since the critical value is derived from the significance level. 

|                | One-sided test | Two-sided test   |
| -------------- | -------------- | ---------------- |
| Critical value | $$z_\alpha$$   | $$z_{\alpha/2}$$ |

1. If the $z$ for our test statistic (sample) is **more extreme** than the critical value $z^*$ ($z$ is further away from the mean than $z^*$), then it is in the critical region, so we can reject the null hypothesis.
    - p-value is smaller than $\alpha$

2. If $z$ is **less extreme** than $z^*$, then it isn't in the critical region, so we can't (fail to) reject the null hypothesis.
    - p-value is greater than $\alpha$
    
![[Pasted image 20220313203504.png]]