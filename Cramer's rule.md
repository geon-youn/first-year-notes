---
alias:
tags: MATH_1B03
---
# Cramer's Rule
**Cramer's rule** is a way for finding the solution for each variable. It differs from [[Gaussian elimination]] since it uses [[determinant|determinants]].

```ad-info
title: Idea of Cramer's Rule
Let $A \vec{x} = \vec{b}$, where $\det A \neq 0$.
Define 
$$
A_j(\vec{b})=\begin{bmatrix}
\vec{a_1}&\cdots&\vec{a_{j-1}}&\vec{b}&\vec{a_{j+1}}&\cdots&\vec{a_n}
\end{bmatrix}$$
where $\vec{b}$ replaces the $j$th column in $A$, and 
$$[\mathbb{I}_n]_j(\vec{x})=\begin{bmatrix}
\vec{e_1}&\cdots&\vec{e_{j-1}}&\vec{x}&\vec{e_{j+1}}&\cdots&\vec{e_n}
\end{bmatrix}
$$
where $\vec{x}$ replaces the $j$th column in $\mathbb{I}_n$. Then,
$$
\begin{align*}
A[\mathbb{I}_n]_j(\vec{x})&=\begin{bmatrix}
A\vec{e_1}&\cdots&A\vec{e_{j-1}}&A\vec{x}&A\vec{e_{j+1}}&\cdots&A\vec{e_n}
\end{bmatrix}\\
&=\begin{bmatrix}
\vec{a_1}&\cdots&\vec{a_{j-1}}&\vec{b}&\vec{a_{j+1}}&\cdots&\vec{a_n}
\end{bmatrix}\\
&=A_j(\vec{b})
\end{align*}
$$
So, taking the derivative of both sides, 
$$
\begin{align*}
\det(A)\det([\mathbb{I}_n]_j(\vec{x}))&=\det(A_j(\vec{b}))\\
\vec{x}_j&=\frac{\det(A_j(\vec{b}))}{\det(A)}\\
&=\frac{\begin{vmatrix}
\vec{a_1}&\cdots&\vec{a_{j-1}}&\vec{b}&\vec{a_{j+1}}&\cdots&\vec{a_n}
\end{vmatrix}}{\begin{vmatrix}
\vec{a_1}&\cdots&\vec{a_{j-1}}&\vec{a_j}&\vec{a_{j+1}}&\cdots&\vec{a_n}
\end{vmatrix}}
\end{align*}
$$
The key idea is that $\det([\mathbb{I}_n]_j(\vec{x}))=\vec{x_j}$ because $[\mathbb{I}_n]_j(\vec{x})$ can be turned into a [[triangular]] matrix through [[replacement]] (no effect on determinant), so its determinant is $1^{n-1}\vec{x_j}=\vec{x_j}$. 
```

```ad-success
title: Cramer's Rule
Given an $n \times n$ matrix $A$ and we want to solve $A\vec{x}=\vec{b}$,
$$\vec{x_j}=\frac{\begin{vmatrix}
\vec{a_1}&\cdots&\vec{a_{j-1}}&\vec{b}&\vec{a_{j+1}}&\cdots&\vec{a_n}
\end{vmatrix}}{\begin{vmatrix}
\vec{a_1}&\cdots&\vec{a_{j-1}}&\vec{a_j}&\vec{a_{j+1}}&\cdots&\vec{a_n}
\end{vmatrix}}$$
```