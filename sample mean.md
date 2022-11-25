---
alias: 
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 17:41:56 
---
# Sample mean
Sample average ([[population and parameters|statistic]]) $\overline{Y}$ is a [[random variable]].

Depending on the chosen sample, this random variable could assume different values.

Suppose we took MANY different samples of the same size from this population. The frequency distribution of these $\overline{y}$'s would be the [[sampling distribution]] of $\overline{Y}$. 

Let $Y$ be the random variable representing a certain characteristic of the population. Then
- $E(Y)=\mu$ and $Var(Y)=\sigma^2$ are the [[centre|mean]] and [[spread|variance]].
- $\overline{Y}$ is the random variable representing the sample mean of samples of size $n$. 

The distribution of the sample mean ($\overline{y}$) when estimated by the [[normal distribution]] has the following parameters:

$$\begin{align*}
E(\overline{y})=\mu(\overline{y})&=\mu\\
SD(\overline{y})&=\frac{\sigma}{\sqrt n}
\end{align*}$$

Based on the [[Central Limit Theorem (CLT)]], the distribution of the sample mean $\overline{y}$ is normally distributed, regardless of the distribution of the population, if sample size $n$ is sufficiently large.

If the population is normally distributed, the sample mean $\overline{y}$ is normally distributed, regardless of the sample size. 

Like the sample proportions, a few conditions must be met:

1. **Idependence assumption**: the sampled values must be independent of each other.
2. **Randomization condition**: the data values must be sampled randomly.
3. **10% condition**: when the sample is drawn without replacement, the sample size should be no more than 10% of the population.
4. **Large enough sample condition**: if the population is [[shape|unimodal]] and symmetric, even a fairly small sample is ok. For skewed distributions, larger sample sizes are required for distribution of means to be approximately normal. 