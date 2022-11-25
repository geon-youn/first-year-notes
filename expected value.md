---
alias: expectation, mean
tags: COMPSCI_1DM3
created: Monday March 21, 2022; 10:31:04 
---
# Expected value
The *expected value* (or *expectation* or *mean*) of the [[random variable]] $X(s)$ on the [[Pierre-Simon Laplace's classical theory of probability|sample space]] $S$ is equal to 

> $$E(X)=\sum_{s\in S}p(s)X(s)$$

If $X$ is a random variable and $p(X=r)$ is the probability that $X=r$, so that

> $$p(X=r)=\sum_{s\in S,X(s)=r}p(s)$$

then

> $$E(X)=\sum_{r\in X(S)}p(X=r)r$$

Proof:

Suppose that $X$ is a random variable with range $X(S)$ and let $p(X=r)$ be the probability that $X$ takes the value $r$. So, $p(X=r)$ is the sum of the probabilities of the outcomes $s$ such that $X(s)=r$.

---

The expected number of successes when $n$ mutually independent [[Bernoulli trial]]s are performed is $np$ where $p$ is the probability of success on each trial.

Proof:

Let $X$ be the random variable equal to the number of success in $n$ trials. So,

$$p(X=K)=\binom{n}{k}p^kq^{n-k}$$

Hence,

$$E(X)=\sum^n_{k=1}p(X=k)k$$

And by manipulating it by substituting $p(X=k)$ and the binomial theorem, 

> $$E(X)=np$$