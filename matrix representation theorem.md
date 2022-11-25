---
alias:
tags: MATH_1B03
---
# Matrix Representation Theorem
Similar to the [[diagonal matrix representation theorem]], but $D$ does not have to be a [[diagonal]] matrix. So, if $A$ is the [[standard matrix]] for a [[linear transformation]] which is not diagonalizable, then there exists a matrix $C$ that maps the [[B-coordinate vector]] of $\vec{x}$ to the B-coordinate vector of $A\vec{x}$ such that
$$\begin{array}{ccccc}
\vec{x}&&\begin{matrix}\rightarrow\\A\end{matrix}&&A\vec{x}\\
\\
\downarrow P^{-1}&&&&P\uparrow\\
\\
[\vec{x}]_B&&\begin{matrix}C\\\rightarrow\end{matrix}&&[A\vec{x}]_B
\end{array}$$
then
$$A=PCP^{-1}$$
So, $C$ is the [[B-matrix]] for $A$. 