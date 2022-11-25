---
alias: Maclaurin series
tags: MATH_1ZB3
created: Saturday March 12, 2022; 14:37:15 
---
# Taylor series
If $f$ has a [[power series]] representation (expansion) at $a$, that is, if 
$$f(x)=\sum^\infty_{n=0}c_n(x-a)^n$$ 
and $|x-a|<R$, then its coefficients are given by the formula 
$$c_n=\frac{f^{(n)}(a)}{n!}$$
So,
$$f(x)=\sum^\infty_{n=0}\frac{f^{(n)}(a)}{n!}(x-a)^n$$

```ad-note
title: Maclaurin series

The Maclaurin series is a special case, which is the Taylor series at $a=0$:
$$f(x)=\sum^{\infty}_{n=0}\frac{f^{(n)}(0)}{n!}x^n$$

```

## Remainder
If $f(x) = T_n(x)+R_n(x)$, where $T_n$ is the $n$th-degree Taylor polynomial of $f$ at $a$, and if 
$$\lim_{n \rightarrow \infty}R_n(x)=0$$
for $|x-a|<R$, then $f$ is equal to the sum of its Taylor series on the interval $|x - a|<R$. 

To show $\lim_{n \rightarrow \infty}R_n(x)=0$, we use [[Taylor's inequality]].