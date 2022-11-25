---
alias:
tags: MATH_1B03
---
# Standard Matrix
Let $T : \mathbb{R}^n \mapsto \mathbb{R}^m$ be a [[linear transformation]]. Then, there exists a unique matrix $A$ such that by the [[super position principle]],
$$\begin{align*}
T(\vec{v})&=x_1T(e_1)+\dots+x_nT(e_n)\\
		  &=\begin{bmatrix}T(e_1) & \cdots & T(e_n)\end{bmatrix}\begin{bmatrix}x_1\\\vdots\\x_n \end{bmatrix}\\ 
		  &=T(\mathbb{I}_n)\vec{v}\\
		  &=A \vec{v}
\end{align*}$$
So, $A$ is the $m\times n$ matrix whose $j$th column is the vector $T(\vec{e_j})$, where $\vec{e_j}$ is the $j$th column of the [[identity matrix]] in $\mathbb{R}^n$. 

$A$ is said to be the **standard matrix for the linear transformation** $T$. 