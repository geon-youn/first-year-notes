---
alias:
tags: MATH_1C03
---
# Archimedean Property for [[real numbers|Real Numbers]]
For every real number $x>0$, there exists a positive [[integers|integer]] such that $x<n$.

```ad-tip
title: Alternative explanation
Integers have no limit such that there will be an integer that is bigger than a real number. Another way of saying this is that 
$$\lim_{n \rightarrow \infty}\frac{1}{n}=0$$
```

For all real numbers $a,b$ $0<a<b$, there exists a positive integer $n$ such that $na>b$ and this theorem follows from the [[completeness axiom]].

## Proof
Assume that $\forall a\in\mathbb{Z}^+$, $na\leq b$. Let $A=\left\{na | n \in \mathbb{Z}^+\right\}$. Since $na\leq b$ for all $n$, then $A$ is bounded above by $b$. Since $A$ is nonempty, it follows by the completeness axiom $\exists \beta\in\mathbb{R}$, $\beta$ [[supremum and infemum|supremum]] of $A$. 

Since $a>0$, $\beta-a<\beta$.

Since $\beta$ is a least upper bound of $A$, $\beta - a$ is not an upper bound for $A$, so $\exists x\in A, \beta - a < x$. 

$$\begin{align*}
\beta-a&<x\\
\beta&<x+a=na+a=(n+1)a\\
\end{align*}$$

This contradicts the fact that $\beta$ is an upper bound of $A$. 