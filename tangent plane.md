---
alias: 
tags: MATH_1ZB3
created: Monday March 28, 2022; 15:08:07 
---
# Tangent plane
Suppose a surface $S$ has equation $z=f(x,y)$, where $f$ has continuous first [[partial derivative of f with respect to x at (a, b)|partial derivative]]s, and let $P(x_0, y_0, z_0)$ be a point on $S$. Let $C_1$ and $C_2$ be the curves obtained by intersecting the vertical planes $y=y_0$ and $x=x_0$ with the surface $S$. Then the point $P$ lies on both $C_1$ and $C_2$. Let $T_1$ and $T_2$ be the tangent lines to the curves $C_1$ and $C_2$ at the point $P$. Then the **tangent plane** to the surface $S$ at the point $P$ is the plane that contains both tangent lines $T_1$ and $T_2$. 

And, if $C$ is any other curve on $S$ and passes through $P$, then its tangent line at $P$ also lies in the tangent plane.

So the tangent plane to $S$ at $P$ consists of all possible tangent lines at $P$ to curves that lie on $S$ and pass through $P$. The tangent plane is the plane that most closely approximates $S$ near $P$. 

Any plane passing through $P$ has the equation

$$A(x-x_0)+B(y-y_0)+C(z-z_0)=0$$

And dividing by $C$ and letting $a=-A/C$ and $b=-B/C$, we have

> $$z-z_0=a(x-x_0)+b(y-y_0)$$

which represents the tangent plane at $P$. Then, its intersection with the plane $y=y_0$ must be the tangent line $T_1$, 

$$z-z_0=a(x-x_0)$$
 
and for $T_2$

$$z-z_0=b(y-y_0)$$

In general,

> $$z-z_0=f_x(x_0,y_0)(x-x_0)+f_y(x_0,y_0)(y-y_0)$$