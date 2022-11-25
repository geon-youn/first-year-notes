---
alias:
tags: MATH_1B03
---
# B-Matrix
Given a [[vector space]] $V$, there is a [[linear transformation]] $T:V\mapsto V$ that takes a vector $\vec{x}\in V$ to a vector $T\vec{x}\in V$. Then, there are related [[B-coordinate vector]]s for $\vec{x}$ and $T\vec{x}$, which are $[\vec{x}]_B$ and $[T\vec{x}]_B$ respectively, where $B$ is the [[basis]] for the finite $n$-[[dimension]] vector space $V$. Then, the **B-matrix** is the linear transformation $M:\mathbb{R}^n\mapsto \mathbb{R}^n$ that maps $[\vec{x}]_B$ to $[T\vec{x}]_B$. 
$$M[\vec{x}]_B=[T\vec{x}]_B$$
## What is $M$ in terms of $B$ and $T$?
Let $V$ be an $n$-dimensional vector space where $\vec{x}\in V$. Let $B=\left\{vec{b_1},\dots,\vec{b_m}\right\}$ be a basis for $B$.  By the [[unique representation theorem]],
$$\begin{align*}
\vec{x}&=c_1\vec{b_1}+\dots+c_n\vec{b_n}\\
T(\vec{x})&=c_1T(\vec{b_1})+\dots+c_nT(\vec{b_n})\\
[T(\vec{x})]_B&=c_1[T(\vec{b_1})]_B+\dots+c_n[T(\vec{b_n})]_B\\
&=\left[[T(\vec{b_1})]_B\dots[T(\vec{b_n})]_B\right]\begin{bmatrix}c_1\\\vdots\\c_n\end{bmatrix}\\
&=\left[[T(\vec{b_1})]_B\dots[T(\vec{b_n})]_B\right]\left[\vec{x}\right]_B
\end{align*}$$
Therefore, $M=\left[[T(\vec{b_1})]_B\dots[T(\vec{b_n})]_B\right]$. 