---
alias: coprime
tags: MATH_1C03
---
# Relatively Prime
Two integers $a,b$ not both equal to zero are **relatively prime** if their [[greatest common divisor]] is 1. This fact ties with [[Euclid's lemma]]. 
$$
\operatorname{gcd}(a,b)=\left\{\begin{array}{ll}
1 & \text{if }a \nmid b\\
a & \text{if }a \mid b
\end{array}\right.
$$
$a,b$ do not have to be [[prime number]]s. 

## Alternative Explanation
Let $a$ and $b$ be integers that are not both $0$. Then $a$ and $b$ are relatively prime iff there exists $x,y\in\mathbb{Z}$ such that
$$1=xa+yb$$
by [[Bezout's identity]]. 
### Converse 
Assume $\exists x,y\in\mathbb{Z}$ such that $1=xa+yb$. We want to show the GCD of $a,b$ is equal to 1. Then, there exists $d>0$ such that $d\mid a$ and $d\mid b$, then $a=kd$ for some integer $k$ and $b=jd$ for some integer $j$. 
$$\begin{align*}
1&=xa+yb\\
&=x(kd)+y(jd)\\
&=d(xk+yj)\\
&=1
\end{align*}$$
since $d\mid 1$, then $d=1$. 