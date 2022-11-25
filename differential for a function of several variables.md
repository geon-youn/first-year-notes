---
alias: differential, total differential
tags: MATH_1ZB3
created: Monday March 28, 2022; 15:32:01 
---
# Differential for a function of several variables
For a [[differential equation]], the **differential** $dx$ is said to be an independent variable, so $dx$ can be given the value of any real number. The differential of $y$ is defined as

$$dy=f'(x)\,dx=\frac{dy}{dx}dx$$

For a [[differentiable for a function of several variables|differentiable]] [[functions of two variables]], $z=f(x,y)$, the differentials $dx$ and $dy$ are independent variables so they can be given any values. Then the differential $dz$ (**total differential**) is defined as

> $$dz=f_x(x,y)dx+f_y(x,y)dy=\frac{\partial z}{\partial x}dx+\frac{\partial z}{\partial y}dy$$

If we take $dx=\Delta x = x - a$ and $dy = \Delta y = y - b$, then the differential of $z$ is

> $$dz=f_x(a,b)(x-a)+f_y(a,b)(y-b)$$

and so the [[linear approximation]] becomes

> $$f(x,y)\approx f(a,b)+dz$$

For a [[functions of three or more variables]], we have the differential $dw$ defined as

> $$dw=\frac{\partial w}{\partial x}dx+\frac{\partial w}{\partial y}dy+\frac{\partial w}{\partial z}dz$$