---
alias:
tags: MATH_1B03
---
# Complex Matrix Representation Theorem
Let $A$ be a real $2 \times 2$ with a complex [[eigenvalue]] $\lambda = a - bi$, where $b\neq 0$ and an associated [[eigenvector]] $\boldsymbol{v}$ in $\mathbb{C}^n$. Then,
$$A=PCP^{-1}$$
where $P=\begin{bmatrix}\operatorname{Re}{\boldsymbol{v}}&\operatorname{Im}{\boldsymbol{v}}\end{bmatrix}$ and $C=\begin{bmatrix}a&-b\\b&a\end{bmatrix}$. 
$$\begin{array}{ccccc}
\boldsymbol{x}&&\begin{matrix}\rightarrow\\A\end{matrix}&&A\boldsymbol{x}\\
\\
\downarrow P^{-1}&&&&P\uparrow\\
\\
\boldsymbol{u}&&\begin{matrix}C\\\rightarrow\end{matrix}&&C\boldsymbol{u}
\end{array}$$