---
alias:
tags: MATH_1B03
---
# Perspective Projection
Creating a new [[dimension]] and mapping each point to a new point at the intersection of a plane and a line that passes through a source and the original point. 

```ad-example
Given
![[PerspectiveProjection.png||600]]
then, by similar triangles
![[PerspectiveProjectionST.png|600]]
$$\begin{align*}
\frac{x^*}{d}&=\frac{x}{d-z}\Rightarrow x^*=\frac{x}{1-\frac{z}{d}}\\
\frac{y^*}{d}&=\frac{y}{d-z}\Rightarrow y^*=\frac{y}{1-\frac{z}{d}}
\end{align*}$$
so, 
$$\begin{pmatrix}x^*\\y^*\\0\\1\end{pmatrix}=
\begin{pmatrix}\frac{x}{1-\frac{z}{d}}\\\frac{y}{1-\frac{z}{d}}\\0\\1\end{pmatrix}\Rightarrow \begin{pmatrix}x\\y\\0\\1-\frac{z}{d}\end{pmatrix}=\left[\begin{array}{cc|cc}
1 & 0 & 0 & 0\\
0 & 1 & 0 & 0\\
\hline
0 & 0 & 0 & 0\\
0 & 0 & \frac{-1}{d} & 1
\end{array}\right]\begin{bmatrix}x\\y\\z\\1\end{bmatrix}$$
```