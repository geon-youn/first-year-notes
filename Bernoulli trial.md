---
alias: binomial, binomial distribution
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 16:42:09 
---
# Bernoulli trial
**Bernouli trial**: a trial with the following characteristics
1. There are only two possible outcomes (success and failure) for each trial.
2. The probability of success, $p$, is the same for each trial ([[discrete probability distribution|discrete uniform distribution]]). The probability of failure is $q=1-p$. 
3. The trials are [[probability|independent]]. 

## [[binomial theorem|Binomial]] distribution

Predicting the **number of successes** in a series of Bernoulli trials:

If $n$ is the number of trials, $p$ is the probability of success, $q=1-p$ is the probability of failure, $X$ is the number of successes in $n$ trials,

$$P(X=k)=\begin{pmatrix}n\\k\end{pmatrix}p^kq^{n-k}$$

We denote by $b(k:n,p)$ the probability of $k$ successes in $n$ independent Bernoulli trials with $p$ the probability of success. Viewed as a function of $k$, $b(k:n,p)$ is the binomisal distribution
> $$b(k:n,p)=\binom{n}{k}p^kq^{n-k}$$

| Expected value | Standard deviation   |
| -------------- | -------------------- |
| $$E(X)=np$$    | $$SD(X)=\sqrt{npq}$$ | 
