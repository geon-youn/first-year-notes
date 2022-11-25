---
alias: deviation, standard deviation, Bienayame's formula, Chebyshev's inequality
tags: COMPSCI_1DM3
created: Monday March 21, 2022; 11:06:56 
---
# Variance
The **deviation** of [[random variable]] $X$ at $s\in S$ is $X(s)-E(X)$, the difference between the value of $X$ and the [[expected value]] of $X$.

The **variance** of $X$ is

> $$\begin{align*}
V(X)&=\sum_{s\in S}(X(s)-E(X))^2p(s)\\
&=E((X-E(X))^2) & \text{by definition of expected value}\\
&=E(X^2)-E(X)^2 & \text{by distributing $^2$ and grouping}
\end{align*}$$

$V(X)$ is the weighted average of the square of the deviation of $X$. The **standard deviation** of $X$, denoted by $\sigma(X)$ is 

> $$\sigma(X)=\sqrt{V(X)}$$

Linearity of variance
> $$V(aX+b)=a^2V(X)$$

## Bienayame's formula
If $X$ and $Y$ are two independent random variables on a [[Pierre-Simon Laplace's classical theory of probability|sample space]] $S$, then $V(X+Y)=V(X)+V(Y)$. Furthermore if $X_i,i=1,2,\dots,n$, with $n$ a positive integer, are pairwise independent random variables on $S$, then

> $$V(X_1+X_2+\dots+X_n)=V(X_1)+V(X_2)+\dots+V(X_n)$$

## Chebyschev's inequality
Let $X$ be a random variable on a sample space $S$ with probability function $p$. If $r$ is a positive real number (representing [[variance|standard deviation]]), then

> $$p(|X(s)-E(X)|\geq r)\leq \frac{V(X)}{r^2}$$

"The probability that the absolute difference between the value of $X$ at $s$ and the expected value is greater than $r$ standard deviations from the mean is less than the variance divided by the standard deviation squared."