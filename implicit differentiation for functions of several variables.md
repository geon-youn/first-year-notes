---
alias: 
tags: MATH_1ZB3
created: Monday March 28, 2022; 15:53:19 
---
# Implicit differentiation for functions of several variables
If $F$ is [[differentiable for a function of several variables|differentiable]], we can apply [[chain rule for functions of several variables|case 1 of the chain rule]] to differentiate both sides of the equation $F(x,y)=0$ with respect to $x$:

$$\frac{\partial F}{\partial x}\frac{dx}{dx}+\frac{\partial F}{\partial y}\frac{dy}{dx}=0$$

So if $\partial F/\partial y\neq 0$, then

> $$\frac{dy}{dx}=-\frac{\frac{\partial F}{\partial x}}{\frac{\partial F}{\partial y}}=-\frac{F_x}{F_y}$$

to derive this equation, we assumed that $F(x,y)=0$ defines $y$ implicitly as a function of $x$. 

By the implicit function theorem, if $F$ is defined on a disk containing $(a,b)$, where $F(a,b)=0$, $F_y(a,b)\neq0$, and $F_x$ and $F_y$ are continuous on the disk, then the equation $F(x,y)=0$ defines $y$ as a function of $x$ near the point $(a,b)$ and the derivative of this function is given by the equation above. 

---

Now suppose that $z$ is given implicitly as a function $z=f(x,y)$ by an equation of the form $F(x,y,z)=0$. So, $F(x,y,f(x,y))=0$ for all $(x,y)$ in the domain of $f$. If $F$ and $f$ are differentiable, then we can use the chain rule to differentiate the equation $F(x,y,z)=0$

$$\frac{\partial F}{\partial x}\frac{\partial x}{\partial x}+\frac{\partial F}{\partial y}\frac{\partial y}{\partial x}+\frac{\partial F}{\partial z}\frac{\partial z}{\partial x}=0$$

but $\frac{\partial x}{\partial x}=1$ and $\frac{\partial y}{\partial x}=0$ (since the derivative of a "constant" is 0) so

$$\frac{\partial F}{\partial x}+\frac{\partial F}{\partial z}\frac{\partial z}{\partial x}=0$$

and if $\frac{\partial F}{\partial z}\neq 0$, then

> $$\frac{\partial z}{\partial x}=-\frac{\frac{\partial F}{\partial x}}{\frac{\partial F}{\partial z}}$$
> $$\frac{\partial z}{\partial y}=-\frac{\frac{\partial F}{\partial y}}{\frac{\partial F}{\partial z}}$$

and by the implicit function theorem, if $F$ is defined within a sphere containing $(a,b,c)$, where $F(a,b,c)=0$, $F_z(a,b,c)\neq 0$, and $F_x$, $F_y$, $F_z$ are continuous inside the sphere, then the equation $F(x,y,z)=0$ defines $z$ as a function of $x$ and $y$ near the point $(a,b,c)$ and this function is differentiable. 