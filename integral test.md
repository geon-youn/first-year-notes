---
alias: remainder estimate
tags: MATH_1ZB3
created: Saturday March 12, 2022; 13:03:22 
---
# Integral test
Let $f$ be a continuous, positive, decreasing function on $[1,\infty)$ and let $a_n=f(n)$. Then the [[series]] $\lim_{n \rightarrow \infty}a_n$ is [[divergence test for series|convergent]] iff the [[improper integral of type 1|improper integral]] $\int^\infty_1f(x)dx$ is convergent.

We don't have to start from 1 either. We can start at any number $c$ and make sure we take the integral starting from $c$ too. 

Also, $f$ does not always have to be decreasing, it just has to be ultimately decreasing. 

## Remainder estimate
Let $f(k)=a_k$, where $f$ is a continuous, positive, decreasing function for $x\geq n$ and $\sum a_n$ is convergent. If $R_n=s-s_n$ then
$$\int^\infty_{n+1}f(x)dx\leq R_n\leq \int^\infty_nf(x)dx$$

If we add $s_n$ to both sides, we get
$$s_n + \int^\infty_{n+1}f(x)dx\leq s\leq s_n + \int^\infty_nf(x)dx$$