---
alias: null hypothesis, alternative hypothesis, two-sided test, one-sided test
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 20:04:34 
---
# Hypothesis testing
**Null hypothesis ($H_0$)**: specifies a [[population and parameters|population parameter]] and proposes a value for that parameter. We usually write a null hypothesis about a [[sample proportion|proportion]] in the form 
$$H_0:p=p_0$$

**Alternative hypothesis ($H_A$)**: contains the values of the parameter that we consider plausible if we reject the null hypothesis.

We assume the null hypothesis is true until we have enough evidence, as verified by the [[p-value]] that we can reject the null hypothesis *in favour of* the alternative hypothesis. 

**Two-sided test**: significant deviations on *either side* of the null hypothesis would cause us to reject the null hypothesis in favour of the alternative
$$H_A:p\neq p_0$$

**One-sided test**: significant deviations *only on the chosen side* of the null hypothesis would cause us to reject the null hypothesis in favour of the alternative
$$H_A:p < p_0$$
$$H_A:p > p_0$$

```ad-note
For the alternative hypothesis, you can only have $\neq$, strictly less than $<$ or strictly greather than $>$. We wouldn't use $\geq$ and $\leq$ since that would include the null hypothesis. 
```

```ad-tip
- Don't put the issue that you're investigating (sample parameter) into the null hypothesis (only the population parameter).
- The issue that you're investigating should go in the alternative hypothesis (through $\neq$, $<$ and $>$).
- Don't have different numbers in the null and alternative hypotheses. 
- The numerical values are always the same:
$$\begin{array}{cc}p & \mu\end{array}$$
```

## Confidence intervals and hypothesis testing
We can construct a [[confidence interval]] around the sample proportion. If we decide to construct a 95% confidence interval around the sample proportion $\hat{p}$, then we should be $95\%$ confident that this interval contains the mean $p$. If the 95% CI doesn't contain $p$, at the [[confidence interval|significance level]] 5%, we can reject the null hypothesis. 

The idea is, if the sample proportion of the same we found $\hat{p}$ is so far from the mean that leads us to reject the null hypothesis, then a confidence interval around $\hat{p}$ using SE should not contain $p$. 

![[Pasted image 20220313203914.png]]


