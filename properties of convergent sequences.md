---
alias: sum law, difference law, constant multiple law, product law, quotient law, power law, Squeeze Theorem, absolute law
tags: MATH_1ZB3
created: Saturday March 12, 2022; 11:19:58 
---
# Properties of convergent series
The difference between the [[limit]] of a function and a sequence is that $n$ is required to be an integer: 

If $\lim_{x\rightarrow \infty}f(x)=L$ and $f(n)=a_n$ when $n$ is an integer, then $\lim_{n\rightarrow \infty} a_n=L$. 

## Limit laws
Suppose that $\{a_n\}$ and $\left\{b_n\right\}$ are [[limit of a sequence|convergent]] [[sequences]] and $c$ is a constant. Then

### Sum law
$$\lim_{n\rightarrow\infty}(a_n+b_n)=\lim_{n \rightarrow \infty}a_n + \lim_{n \rightarrow \infty}b_n$$
### Difference law
$$\lim_{n\rightarrow\infty}(a_n-b_n)=\lim_{n \rightarrow \infty}a_n - \lim_{n \rightarrow \infty}b_n$$
### Constant multiple law
$$\lim_{n \rightarrow \infty}ca_n=c\lim_{n \rightarrow \infty}a_n$$
### Product law
$$\lim_{n \rightarrow \infty}(a_nb_n)=\lim_{n \rightarrow \infty}a_n\cdot\lim_{n \rightarrow \infty}b_n$$
### Quotient law
$$\lim_{n \rightarrow \infty}\frac{a_n}{b_n}=\frac{\lim_{n \rightarrow \infty}a_n}{\lim_{n \rightarrow \infty}b_n} \,\,\,\text{if $\lim_{n \rightarrow \infty}b_n\neq 0$}$$
### Power law
$$\lim_{n \rightarrow \infty}a_n^p=\left[\lim_{n \rightarrow \infty}a_n\right]^p\,\,\,\text{if $p>0$ and $a_n>0$}$$
### Squeeze Theorem for sequences
If $a_n\leq b_n\leq c_n$ for $n\geq n_0$ and $$\lim_{n \rightarrow \infty}a_n=\lim_{n \rightarrow \infty}c_n=L$$ then $$\lim_{n \rightarrow \infty}b_n=L$$
### Absolute law
If $\lim_{n \rightarrow \infty}|a_n|=0$, then $\lim_{n \rightarrow \infty}a_n=0$. 