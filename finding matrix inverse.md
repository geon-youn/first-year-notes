---
alias:
tags: MATH_1B03
---
# Algorithm for Finding $A^{-1}$
[[reduced row echelon form|Row reduce]] the augmented matrix $\begin{bmatrix} A & \mathbb{I}\end{bmatrix}$. If $A$ is [[row equivalent]] to $\mathbb{I}$, then $\begin{bmatrix} A & \mathbb{I}\end{bmatrix}$ is row equivalent to $\begin{bmatrix}\mathbb{I} & A^{-1}\end{bmatrix}$. Otherwise, $A$ does not have an [[invertibility|inverse]]. 