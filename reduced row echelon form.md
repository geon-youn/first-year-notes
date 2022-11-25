---
alias: RREF
tags: MATH_1B03
---
# Reduced Row Echelon Form
A system is in **reduced row echelon form** if it has the properties of a [[row echelon form]] and
1. All leading entries are equal to 1.
2. Leading entries are the only nonzero entries in their columns.

```ad-example
$$\text{REF}\Rightarrow\text{RREF}$$
$$\begin{bmatrix}1 & 4 & 21\\
0 & 1 & -13\\
0 & 0 & 0\end{bmatrix}\Rightarrow\begin{bmatrix}1 & 0 & 73\\
0 & 1 & -13\\
0 & 0 & 0\end{bmatrix}$$
```

```ad-note
title: Uniqueness
Each matrix is [[row equivalent]] to one and only one reduced echelon matrix. 
```