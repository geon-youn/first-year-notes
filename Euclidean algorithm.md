---
alias:
tags: MATH_1C03
---
# Euclidean Algorithm
Let $a,b\in\mathbb{Z}$, $a\neq 0$ and $b\neq 0$. If $q,r\in\mathbb{Z}$ have the property that $a=bq+r$, then 
$$\operatorname{gcd}(a,b)=\operatorname{gcd}(b,r)$$
## Proof
Want to show $\operatorname{gcd}(a,b)=\operatorname{gcd}(b,r)$, where $a=bq+r$. 

Let $D_{a,b}$ and $D_{b,r}$ be the sets containing the [[division|divisors]] of $a,b$ and $b,r$ respectively; that is, $D_{a,b}=D_a\cap D_a$ and $D_{b,r}=D_b \cap D_r$. Then, we will show $D_{a,b}=D_{b,r}$ by [[double inclusion]]. 

### $D_{a,b}\subseteq D_{b,r}$
> Let $d\in D_{a,b}$, so $a=dn$, $b=dm$, where $n,m\in\mathbb{Z}$. $r=a-bq=dn-dmq=d(n-mq)$, thus $d|r$. So, $d\in D_{b,r}$.  So $D_{a,b}\subseteq D_{b,r}$.

### $D_{b,r} \subseteq D_{a,b}$
> Let $d\in D_{b,r}$, so $b=dn$, $r=dm$, where $n,m\in\mathbb{Z}$. $a=bq+r=dnq+dn=d(nq+m)$, thus $d|a$. So, $d\in D_{a,b}$.  So $D_{b,r}\subseteq D_{a,b}$.

Thus the [[greatest common divisor]] of $b,r$ is equal to the greatest common divisor of $a,b$. 

## Algorithm
Using the given theorem, given positive integers $a,b$. Assume without loss of generality $b<a$. We want to compute $\operatorname{gcd}(a,b)$. 

`while b does not divide a do:`
		1. use the [[division algorithm]] to compute $q,r$ such that $a=bq+r$ and $0\leq r < b$. 
		2. `a = b`
		3. `b = r`
`return b`

### Proof that the algorithm terminates
Look at $S$, the set of remainders $r$ in this algorithm. We claim that $r=0$ (i.e. eventually, $b|a$). Assume for contradiction that $0\notin S$. Then for every $r_k\in S$, $a_k=b_kq_k+r_k$, $b_k=r_kq_{k+1}+r_{k+1}$ where $0\leq r_{k+1}<b_{k+1}=r$. So no element of $S$ is smallest, which contradicts the [[well-ordering principle]] so $0\in S$ thus the algorithm eventually terminates. 