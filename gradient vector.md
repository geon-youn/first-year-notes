---
alias: 
tags: MATH_1ZB3
created: Monday April 4, 2022; 15:08:15 
---
# Gradient vector
The [[directional derivative]] is actually a [[inner product|dot product]] between the *gradient* of $f$ ($\textbf{grad}\,\, f$ or $\nabla f$ which is read "del $f$") and the unit vector $\boldsymbol{u}$: 

> $$\begin{align*}
D_\boldsymbol{u}f(x,y)&=f_x(x,y)a + f_y(x,y)b\\
&=\left\langle f_x(x,y),f_y(x,y)\right\rangle\cdot\left\langle a,b\right\rangle\\
&=\nabla f(x,y)\cdot \boldsymbol{u}
\end{align*}$$

If $f$ is a [[functions of two variables]] $x$ and $y$, then the **gradient** of $f$ is the vector function $\nabla f$ defined by 

> $$\nabla f(x,y)=\left\langle f_x(x,y),f_y(x,y)\right\rangle=\frac{\partial f}{\partial x}\boldsymbol{i}+\frac{\partial f}{\partial y}\boldsymbol{j}$$

If $f$ is a [[functions of three or more variables]], then

> $$\nabla f(\boldsymbol{x})=\left\langle f_x(\boldsymbol{x}),f_y(\boldsymbol{x}),\dots \right\rangle$$