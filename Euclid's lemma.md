---
alias:
tags: MATH_1C03
---
# Euclid's Lemma
Let $a,b,c\in\mathbb{Z}$. If the [[greatest common divisor]] of $a,c$ is $1$ and $c$ [[divisible|divides]] $ab$, then $c$ divides $b$. 
$$(\exists a,b,c\in\mathbb{Z})(\operatorname{gcd}(a,c)=1\wedge c|ab\Rightarrow c|b)$$
## Alternative Explanation
If $p$ is prime and $p\nmid a$, if $p\mid ab$ then $p\mid b$. 
## Proof
Assume $\operatorname{gcd}(a,c)=1$ and $c\mid ab$. Want to show $c\mid b$.
$$\begin{align*}
1&=xa+yc\\
b&=b(xa+yc)\\
&=bxa+byc\\
&=xkc+byc\\
&=c(xk+by)
\end{align*}$$
So, $c\mid b$ by [[Bezout's identity]]. 
## Special Case
Let $p$ be a [[prime number]] and let $b_1,\dots,b_r$ be [[integers]]. If $p|b_1\dotsb_r$, then there exists $i\in\left\{1,\dots,r\right\}$ such that $p|b_i$. 
## Alternative Explanation (for two elements)
If $p$ is prime and $p\mid ab$, then $p\mid a$ or $p\mid b$. 
## Proof
We give a [[mathematical induction|proof by induction]] on $r$. 
### Base Case ($r=1$)
$p\mid b_1$
### Induction Hypothesis
Assume: If $p\mid b_1\dots b_r$, then $\exists i\in\left\{1,\dots,r\right\}$ such that $p\mid b_i$. 
### Induction Step
Assume $p\mid \left(b_1\dots b_r\right)b_{r+1}=ab$ then $p\mid a$ or $p\mid b$. 

Case I: $p\mid b_1\dots b_r\Rightarrow p\mid b_i, 1\leq i \leq r$ by the induction hypothesis.

Case II: $p\mid b_{r+1}$. 