---
alias:
tags: MATH_1B03
---
# Homogeneous Coordinates
**Homogeneous coordinates** are equivalent to another coordinate, but may live in a higher [[dimension]]. Homogeneous coordinates are useful for [[computer graphics]] since they allow us to translate coordinates. 

```ad-abstract
title: Generalized homogeneous coordinates
If
$$
\begin{pmatrix}X\\Y\\Z \end{pmatrix}\in \mathbb{R}^3 \rightarrow \begin{pmatrix}X\\Y\\Z\\H \end{pmatrix}\in \mathbb{R}^4, H\neq 0
$$
then we "identify" vectors $
\begin{pmatrix}X\\Y\\Z\\H \end{pmatrix}$ and $\begin{pmatrix}X/H\\Y/H\\Z/H\\1 \end{pmatrix}$, which both lie on the same line.
```