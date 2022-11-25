---
alias: radius of convergence, interval of convergence
tags: MATH_1ZB3
created: Saturday March 12, 2022; 13:58:18 
---
# Power series
A **power series** is a [[series]] of the form 
$$\sum^{\infty}_{n=0}c_nx^n=c_0+c_1x+c_2x^2+c_3x^3+\dots$$
where $x$ is a variable and the $c_n$'s are the coefficients of the series. 

When we substitute a value for $x$, we get a series of constants that we can test for [[divergence test for series|convergence]]. A power series may converge for some values of $x$ and diverge for other values of $x$. 

Generally, a power series is of the form
$$\sum^{\infty}_{n=0}c_n(x_n-a)^n$$
which is called a **power series in $(x-a)$** or a **power series centered at $a$** or a **power series about $a$**. To determine for what values of $x$ the series converges, we usually use the [[ratio test]] or the [[root test]]. 


## Radius of convergence
For a [[power series]] $\sum^\infty_{n=0}c_n(x_n-a)^n$, there are only three possibilities:
1. The series converges only when $x=a$;
2. The series converges for all $x$;
3. There is a positive number $R$ such that the series converges if $|x-a|<R$ and diverges if $|x-a|>R$. 

The number $R$ is called the **radius of convergence** of the power series. By convention, $R=0$ for case 1 and $R=\infty$ for case 2. The **interval of convergence** of a power series is the interval that consists of all values of $x$ for which the series converges:
1. $a$
2. $(-\infty,\infty)$
3. $a-R<x<a+R$

For case 3, when $x$ is at the end point: $x=a\pm R$, anything can happen; that is, it can be convergent or divergent at either point. So, there are four possibilities:
1. $(a-R, a+R)$
2. $(a-R, a+R]$
3. $[a-R, a+R)$
4. $[a-R, a+R]$