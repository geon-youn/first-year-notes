---
alias: standard normal distribution, asymptotic, standard normal random variable
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 17:03:11 
---
# Normal distribution
**Asymptotic**: the tails get closer to the horizontal axis, but never touch it. 

**Normal distribution**: an asymptotic symmetric bell-shaped distribution described by two variables: [[centre|mean]] ($\mu$) and standard deviation ($\sigma$). Given a [[random variable]] $X$, its normal distribution is denoted by $X \sim N(\mu, \sigma)$. 

## Adding normal variables
The sum or difference of independent normal random variables is also normal. So, if we have $X\sim N(\mu_X,\sigma_X)$ and $Y\sim N(\mu_Y,\sigma_Y)$ as two normally distributed random variables, the the distribution of their sum $L=X+Y$ and/or difference $K=X-Y$ will be
$$L\sim N(\mu_X+\mu_Y,\sqrt{\sigma_X^2+\sigma_Y^2})$$

$$K\sim N(\mu_X-\mu_Y,\sqrt{\sigma_X^2+\sigma_Y^2})$$
## Standard normal distribution
A special case of the normal distribution with mean equal to zero and a standard deviation of one. Denoted with the letter $Z$ to denote a random variable that's normal and has $E(Z)=0$ and $Var(Z)=SD(Z)=1$. 

Each value of this random variable $Z$ is actually a [[standardizing|z-score]].

$$P(X\leq x)=P(X-\mu\leq x-\mu)=P\left(\frac{X-\mu}{\sigma}\leq \frac{x-\mu}{\sigma}\right)=P(Z\leq z)$$

Any normally distributed random variable $X$ with mean $\mu$ and standard deviation $\sigma$ can be transformed into the standard normal random variable $Z$ by
$$Z=\frac{X-\mu}{\sigma}$$

Therefore, any value $x$ has a corresponding value $z$ by
$$z=\frac{x-\mu}{\sigma}$$

![[Pasted image 20220313171048.png]]
![[Pasted image 20220313171058.png]]