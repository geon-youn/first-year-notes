---
alias: series, sum, geometric series
tags: COMPSCI_1DM3 MATH_1ZB3
created: February 14, 2022 18:05
---
# Series
Given a series $\sum^{\infty}_{n=1}a_n$, let $s_n$ denote its partial sum:
$$s_n=\sum^{n}_{i=1}a_i=a_1+a_2+\cdots+a_n$$
## Finite Geometric Series
$$\sum^{n}_{k=0}ar^k=\begin{cases}\frac{ar^{n+1}-a}{r-1} & r\neq 1\\
(n+1)a & r=1\end{cases}$$

### Proof
$$\begin{align*}
S_n&=\sum^{n}_{j=0}ar^j\\
rS_n&=r\sum^{n}_{j=0}ar^j & \text{multiply both sides by r}\\
&=\sum^n_{j=0}ar^{j+1}\\
&=\sum^{n+1}_{k=1}ar^k & \text{shift index of summation with $k=j+1$}\\
&=\left(\sum^n_{k=0}ar^k\right)+(ar^{n+1}-a) & \text{removing $k=n+1$ term and adding $k=0$ term}\\
&=S_n+(ar^{n+1}-a) & \text{substituting S for summation formula}\\\\
\hline\\
\therefore rS_n&=S_n+(ar^{n+1}-a)\\
S_n&=\frac{ar^{n+1}-a}{r-1} & \text{if $r\neq 1$}\\
S_n&=\sum^n_{j=0}ar^j=\sum^n_{j=0}a=(n+1)a & \text{if $r = 1$}
\end{align*}$$
## Infinite Geometric Series
The geometric series $\sum^{\infty}_{n=1}ar^{n-1}$ is [[divergence test for series|convergent]] if $|r| < 1$ and its sum is
$$\sum^{\infty}_{n=1}ar^{n-1}=\frac{a}{1-r}$$
Otherwise, if $|r| \geq 1$, the series is [[divergence test for series|divergent]].

```ad-abstract
Let $r=x$ and $a=1$, then
$$\sum^{\infty}_{n=0}x^n=\frac{1}{1-x}$$
```

## Polynomial Series
$$\sum^{n}_{k=1}k=\frac{n(n+1)}{2}$$
$$\sum^{n}_{k=1}k^2=\frac{n(n+1)(2n+1)}{6}$$
$$\sum^{n}_{k=1}k^3=\frac{n^2(n+1)^2}{4}$$

## Convergent Series
$$\sum^{\infty}_{k=0}x^k, |x|<1=\frac{1}{1-x}$$
And you can take the derivative of sums:
$$\sum^{\infty}_{k=0}kx^{k-1}, |x|<1=\frac{1}{(1-x)^2}$$