---
alias: 
tags: MATH_1ZB3
created: Saturday March 12, 2022; 13:17:21 
---
# Limit comparison test
Suppose that $\sum a_n$ and $\sum b_n$ are [[series]] with positive terms. If
$$\lim_{n \rightarrow \infty}\frac{a_n}{b_n}=c$$
where $c$ is a finite number and $c>0$, then either both series converge or both diverge. 

## Proof
Let $m$ and $M$ be positive numbers such that $m < c < M$. Because $\frac{a_n}{b_n}$ is close to $c$ for large $n$, there is an integer $N$ such that
$$m<\frac{a_n}{b_n}<M, \,\, \text{when}\,\,\,n > N$$
and so
$$mb_n<a_n<Mb_n,\,\, \text{when}\, \,\,n > N$$
If $\sum b_n$ converges, so does $\sum Mb_n$. Thus $\sum a_n$ converges by the [[direct comparison test]]. If $\sum b_n$ diverges, so does $\sum mb_n$ and $\sum a_n$ diverges by the [[direct comparison test]].