---
alias: probability mass function, pmf, discrete uniform distribution
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 16:25:13 
---
# Discrete probability distribution
It's common to describe a [[random variable|discrete random variable]] using its **probability mass function (pmf)**, which is a list of possible outcomes of the random variable and their associated probabilities. 

The probability of each value $x$ is between $0$ and $1$, 
$$0\leq P(X=x)\leq 1$$

The sum of the probabilities is $1$:
$$\sum P(X=x)=1$$

Expected value:
$$\begin{align*}
E(X)&=x_1P(x_1)+x_2P(x_2)+\dots+x_nP(x_n)\\
    &=\sum^n_{i=1}x_iP(x_i)
\end{align*}$$

[[spread|variance]]:
$$\begin{align*}
Var(X)&=[x_1-E(X)]^2P(x_1)+[x_2-E(X)]^2P(x_2)+\dots+[x_n-E(X)]^2P(x_n)\\
      &=\sum^n_{i=1}[x_i-E(X)]^2P(x_i)
\end{align*}$$

```ad-note
For a discreate random variable using pmf, $P(X=x)=P(x)$. 
```

**Discrete [[shape|uniform]] distribution $U[1,\dots, n]$**: if $X$ is a random variable where each outcome has the same probability (e.g., rolling a dice). 