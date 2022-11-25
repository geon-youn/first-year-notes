---
alias: error type I, error type II, false positive, false negative, type 1 error, type 2 error, power, effect size
tags: COMMERCE_1DA3
created: Tuesday March 15, 2022; 14:34:15 
---
# Hypothesis tests outcomes
In any [[hypothesis testing|hypothesis test]], 4 outcomes are possible:

> 1. **Error type I (false positive)**: We reject the null hypothesis when the null hypothesis is actually true. 
Rejecting by mistake.

> 2. We reject the null hypothesis when the null hypothesis is actually not true.
> 3. We retain the null hypothesis when the null hypothesis is actually true.

> 4. **Error type II (false negative)**: we retain the null hypothesis when the null hypothesis is actually false.
Accepting by mistake.

![[Pasted image 20220315154206.png]]

## Type 1 error
When you're choosing the [[p-value|significance level]], you're actually setting the probability of type 1 error. Probability of type 1 error is $\alpha$.  $\alpha$ is the probability that determines the critical region.

If a [[population and parameters|sample statistic]] is one of those "rare" samples that falls into the critical region, we reject the null hypothesis while it was actually true.

A "rare" and "extreme" sample may fall into the critical region (probability), and lead to a true null hypothesis be rejected by error. 

If $\alpha$ is very large, you reject the null hypothesis frequently, leading to type 1 error. 

If $\alpha=0$, you won't reject any null hypothesis (since the p-value must be less than $\alpha$, but p-value is positive), and leads to type 2 error. 

![[Pasted image 20220315154241.png]]

## Type 2 error
Type II error (with probability $\beta$) is the probability of retaining (failing to reject) the null hypothesis, while it is actually not true.

![[Pasted image 20220315154250.png]]

## Power
The power of a test is the probability that it correctly rejects a false null hypothesis. The power of the test is the complement of type 2 error: $\text{power}=1-\beta$.

**Effect size**: the distance between the null hypothesis value $p_0$ and the truth $p$. 

The further $p_0$ from $p$, the greater the power. 

As $\alpha$ decreases, $p^*$ moves closer to the truth $p$, and $\beta$ increases, so power decreases. 

![[Pasted image 20220315161606.png]]

Suppose we're testing the following [[hypothesis testing|hypotheses]]:
$$\cases{H_0:p=p_0\\H_A:p>p_0}$$

Then we'll reject the null if the observed proportion $\hat{p}$ is greater than some [[confidence interval|critical value]] $p^*$. $p^*$ can be found based on the [[p-value|significance level]] of the test:

$$p^*=p_0+z^*\times SD(\hat{p})$$

|                  | Left-sided test | Two-sided test      | Right-sided test |
| ---------------- | --------------- | ------------------- | ---------------- |
| Reject null when | $$\hat{p}<p^*$$ | $$\hat{p}\neq p^*$$ | $$\hat{p}>p^*$$  |


## Increasing the sample size
If we can increase the sample size, the distribution becomes narrower ([[spread|standard deviation]] becomes smaller).

For a given $\alpha$, the probability of type II error ($\beta$) will decrease. The power of the test will increase. $\alpha$ stays the same (since you choose what it is).