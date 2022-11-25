---
alias: limit, convergent, divergent
tags: MATH_1ZB3
created: Saturday March 12, 2022; 11:10:11 
---
# Limit of a sequence
## Intuitive definition
A [[sequences|sequence]] $\{a_n\}$ has the limit $L$ and we write
$$\lim_{n\rightarrow\infty}a_n=L$$ or $a_n\rightarrow L$ as $n\rightarrow\infty$ if we can make the terms $a_n$ as close to $L$ as we like by taking $n$ sufficiently large. 

If $\lim_{n\rightarrow \infty} a_n$ exists, we say the sequence **converges** (or is **conergent**). Otherwise, we say the sequence **diverges** (or is **divergent**). 

## Precise definition
A sequence $\{a_n\}$ has the limit $L$ and we write
$$\lim_{n\rightarrow\infty}a_n=L$$ or $a_n\rightarrow L$ as $n\rightarrow\infty$ if for every $\epsilon>0$ there is a corresponding integer $N$ such that if $n>N$, then $|a_n - L| < \epsilon$. (see [[limit]])

## Infinite limit
The notation $\lim_{n\rightarrow\infty}a_n=\infty$ means that for every positive number $M$ there is an integer $N$ such that if $n>N$ then $a_n>M$. 

An analagous definition applies for $\lim_{n\rightarrow\infty}a_n=-\infty$. 

## Into a function
If $\lim_{n \rightarrow \infty}a_n=L$ and the function $f$ is continuous at $L$, then 
$$\lim_{n \rightarrow \infty}f(a_n)=f(L)$$