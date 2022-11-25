---
alias:
tags: MATH_1B03
---
# Diagonal Matrix Representation Theorem
Suppose a matrix $A$ is [[diagonalization|diagonalizable]] such that there exists an [[invertibility|invertible]] matrix $P$ and a [[diagonal]] matrix $D$ such that $A=PDP^{-1}$. Let $B=\left\{\vec{p_1},\dots,\vec{p_n}\right\}$ be a [[basis]] formed of the columns of $P$. Then, $D$ is the [[B-matrix]] for $\vec{x}\mapsto A\vec{x}$. 

$$\begin{array}{ccccc}
\vec{x}&&\begin{matrix}\rightarrow\\A\end{matrix}&&A\vec{x}\\
\\
\downarrow P^{-1}&&&&P\uparrow\\
\\
[\vec{x}]_B&&\begin{matrix}D\\\rightarrow\end{matrix}&&[A\vec{x}]_B
\end{array}$$

## Proof
Recall that $P$ is the [[change of coordinates]] matrix $P_B$ that satisfies
$$P[\vec{x}]_B=\vec{x}_j[\vec{x}]_B=P^{-1}\vec{x}$$
where $\vec{x}=c_1\vec{p_1}+\dots+c_n\vec{p_n}=[\vec{p_1},\dots,\vec{p_n}]\begin{bmatrix}c_1\\\vdots\\c_n\end{bmatrix}=P[\vec{x}]_B$. 

If a [[linear transformation]] $T(\vec{x})=A\vec{x}$, then by the [[unique representation theorem]],
$$\begin{align*}
[T]_B&=\left[[T\vec{p_1}]_B\dots[T\vec{p_n}]_B\right]\\
&=\left[[A\vec{p_1}]_B\dots[A\vec{p_n}]_B\right]\\
&=\left[P^{-1}A\vec{p_1}\dots P^{-1}A\vec{p_n}\right]\\
&=P^{-1}AP\\
&=P^{-1}(PDP^{-1})P\\
&=D
\end{align*}$$