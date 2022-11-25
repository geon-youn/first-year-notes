---
alias: linearization, tangent plane approximation
tags: MATH_1ZB3
created: Monday March 28, 2022; 15:17:03 
---
# Linear approximation
When we find the [[tangent plane]] of a [[functions of two variables]] $z=f(x,y)$ at a specific point $P(x_0,y_0,z_0)$, the function $L$ is called the **linearization** of $f$ at $(x_0,y_0)$ and the approximation of $L$ is called the **linear approximation** or **tangent plane approximation** of $f$ at $(x_0,y_0)$. 

```ad-tip
$L$ is equivalent to $z$, but as a linear approximation.
```

In general, the equation of the tangent plane of $f$ at $(a,b,f(a,b))$ is

> $$z=f(a,b)+f_x(a,b)(x-a)+f_y(a,b)(y-b)$$

The linear function whose graph is this tangent plane

> $$L(x,y)=f(a,b)+f_x(a,b)(x-a)+f_y(a,b)(y-b)$$

is called the **linearization** of $f$ at $(a,b)$ and the approximation

> $$f(x,y)\approx f(a,b)+f_x(a,b)(x-a)+f_y(a,b)(y-b)$$

is called the **linear approximation** or **tangent plane approximation** of $f$ at $(a,b)$. 

For a [[functions of three or more variables]], we have

$$f(x,y,z)\approx f(a,b,c)+f_x(a,b,c)(x-a)+f_y(a,b,c)(y-b)+f_z(a,b,c)(z-c)$$