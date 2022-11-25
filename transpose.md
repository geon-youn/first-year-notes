---
alias:
tags: MATH_1B03
---
# Transpose of a Matrix
The **transpose** of a matrix is where you flip the matrix along its [[main diagonal]]. In other words, rows become columns and columns become rows. So, an $n \times m$ matrix will become a $m \times n$ matrix.

```ad-example
If 
$$A=\begin{bmatrix}\textbf{1} & 2 & 3\\4 & \textbf{5} & 6\\7 & 8 & \textbf{9} \end{bmatrix}$$
then its transpose, denoted by $^{T}$ is
$$A^{T}=\begin{bmatrix}\textbf{1} & 4 & 7\\2 & \textbf{5} & 8\\3 & 6 & \textbf{9}\end{bmatrix}$$
```

## With Multiple Matrices
When you apply the transpose to multiple matrices, the matrices are flipped:
$$(ABC)^T=C^TB^TA^T$$
$$(AB)^TC=B^TA^TC$$