---
alias: 
tags: MATH_1ZB3
created: Monday April 4, 2022; 14:56:54 
---
# Directional derivative
The **directional derivative** of $f$ at $(x_0, y_0)$ in the direction of $\boldsymbol{u}=\left\langle a, b\right\rangle$ is 

> $$D_\boldsymbol{u}f(x_0, y_0)=\lim_{h \rightarrow \infty}\frac{f(x_0+ha, y_0+hb) - f(x_0, y_0)}{h}$$

if this limit exists.

If $\boldsymbol{u}=\boldsymbol{i}=\left\langle 1, 0\right\rangle$ then $D_\boldsymbol{i}f = f_x$ which is the [[partial derivative of f with respect to x at (a, b)|partial derivative]] of $f$ with respect to $x$ and if $\boldsymbol{u}=\boldsymbol{j}=\left\langle0,1\right\rangle$ then $D_\boldsymbol{j}f = f_y$ which is the partial derivative of $f$ with respect to $y$. 

If $f$ is a [[differentiable for a function of several variables|differentiable]] function of $x$ and $y$, then $f$ has a directional derivative in the direction of any [[unit vector]] $\boldsymbol{u}=\left\langle a, b\right\rangle$ and

> $$D_\boldsymbol{u}f(x,y)=f_x(x,y)a + f_y(x,y)b$$

If the $\boldsymbol{u}$ makes an angle $\theta$ with the positive $x$ axis, then we can write $\boldsymbol{u}=\left\langle \cos\theta, \sin\theta\right\rangle$ and

> $$D_\boldsymbol{u}f(x,y)=f_x(x,y)\cos\theta + f_y(x,y)\sin\theta$$

Using the definition of the [[gradient vector]], we have

> $$D_\boldsymbol{u}=\nabla f(x,y)\cdot \boldsymbol{u}$$

For a [[functions of three or more variables]], we have

> $$D_\boldsymbol{u}f(x_0,y_0,z_0)=\lim_{h \rightarrow \infty}\frac{f(x_0+ha, y_0+hb, z_0+hc)-f(x_0,y_0,z_0)}{h}$$

if this limit exists. And in general,

> $$D_\boldsymbol{u}f(\boldsymbol{x}_0)=\lim_{h \rightarrow \infty}\frac{f(\boldsymbol{x}_0+h\boldsymbol{u})-f(\boldsymbol{x}_0)}{h}$$

And so

> $$D_\boldsymbol{u}f(\boldsymbol{x})=\nabla f(\boldsymbol{x})\cdot\boldsymbol{u}$$