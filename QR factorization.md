---
alias:
tags: MATH_1B03
---
# QR Factorization
If $A$ is an $m \times n$ matrix with [[linearly independent set|linearly independent]] columns, then $A$ can be factored as $A=QR$, where $Q$ is an $m \times n$ matrix whose columns form an [[orthonormal basis]] for the [[column space]] of $A$ and $R$ is an $n \times n$ upper [[triangular]] matrix with positive entries on its [[main diagonal]].

Let $A=[\vec{x_1}\cdots\vec{x_m}]$.
1. Choose an orthonormal basis $\left\{\vec{u_1},\dots,\vec{u_n}\right\}$ that spans $\operatorname{Span}A$ with the [[reverse echelon property]] (e.g. $\vec{u_k}=\frac{\vec{v_k}}{||\vec{v_k}||}$ from the [[Gram-Schmidt process]]).
2. Since $\vec{x_k}\in\operatorname{Span}\left\{\vec{u_1},\dots,\vec{u_k}\right\}$ by reverse echelon property 
$$\begin{align*}
\vec{x_k}&=r_{1k}\vec{u_1}+\dots+r_{kk}\vec{u_k}\\
		 &=\begin{bmatrix}\vec{u_1} & \cdots & \vec{u_n}\end{bmatrix}\begin{bmatrix}r_{1k}\\\vdots\\r_{kk}\\0\\\vdots\\0\end{bmatrix}\\
		 &=Q\vec{r_k}
\end{align*}$$
where we may assume $r_{kk}\geq 0$. 
3. From $\vec{x_k}=Q\vec{r_k}$, 
$$\begin{align*}
A&=\begin{bmatrix}\vec{x_1} & \cdots & \vec{x_n}\end{bmatrix}\\
 &=\begin{bmatrix}Q\vec{r_1} & \cdots & Q\vec{r_n}\end{bmatrix}\\
 &=QR
\end{align*}$$
4. Then, since $Q$ is an orthonormal matrix
$$Q^{-1}A=R=Q^TA$$
5. So, since $A$ has linearly independent columns
$$A\vec{y}=QR\vec{y}=\vec{0}$$
where $\vec{y}$ must be the zero vector. 
