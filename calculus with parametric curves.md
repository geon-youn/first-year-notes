---
alias: tangent, area, arc length, surface area
tags: MATH_1ZB3
created: Monday March 14, 2022; 13:33:09 
---
# Calculus with parametric curves
## Tangents
Suppose $f$ and $g$ are differentiable functions and we want to find the tangent line at a point on the [[parametric equation|parametric curve]] $x=f(t)$, $y=g(t)$, where $y$ is also a differentiable function of $x$. By the chain rule,

> $$\frac{dy}{dt}=\frac{dy}{dx}\cdot\frac{dx}{dt}$$

If $dx/dt\neq 0$, we can solve for $dy/dx$:

> $$\frac{dy}{dx}=\frac{\frac{dy}{dt}}{\frac{dx}{dt}}$$

This equation lets us find the slope $dy/dx$ of the tangent to a parametric curve *without having to eliminate the parameter $t$*. 

The curve has a **horizontal tangent when $dy/dt=0$** and a **vertical tangent when $dx/dt=0$**, provided that $dy/dt \neq 0$. 

```ad-warning
If both $dx/dt=0$ and $dy/dt=0$, then we need other methods to determine the slope of the tangent. 
```

For the second derivative (concavity), we can replace $y$ by $dy/dx$:

> $$\frac{d^2y}{dx^2}=\frac{d}{dx}\left(\frac{dy}{dx}\right)=\frac{\frac{d}{dt}\left(\frac{dy}{dx}\right)}{\frac{dx}{dt}}$$

## Areas
We know that the area under a curve $y=F(x)$ from $a$ to $b$ is $\int^b_aF(x)\,dx$ where $F(x)\geq 0$. If the curve is traced out once by the parametric equations $x=f(t)$ and $y=g(t)$, $\alpha \leq t\leq \beta$, then we can calculate an area formula by using the substitution rule ($dx=f'(t)dt$), we get:

> $$A=\int^b_ay\,dx=\int^\beta_\alpha g(t)f'(t)\,dt$$

## Arc length
We already know how to find the length $L$ of a curve $C$ in the form $y=F(x)$, $a\leq x\leq b$. If $F'$ is continuous, then

> $$L=\int^b_a\sqrt{1+\left(\frac{dy}{dx}\right)^2}\,dx$$

Suppose that $C$ can also be described by the parametric equations $x=f(t)$ and $y=g(t)$, $\alpha\leq t\leq\beta$, where $dx/dt=f'(t)>0$. Then, $C$ is traversed once, from left to right, as $t$ increases from $\alpha$ to $\beta$ and $f(\alpha)=a, f(\beta)=b$. Putting it into the above formula using substitution rule, we have

> $$L=\int^b_a\sqrt{1+\left(\frac{dy}{dx}\right)^2}\,dx
= \int^\beta_\alpha\sqrt{1 + \left(\frac{dy/dt}{dx/dt}\right)^2}\frac{dx}{dt}\, dt$$

and since $dx/dt>0$, 

> $$L=\int^\beta_\alpha\sqrt{\left(\frac{dx}{dt}\right)^2+\left(\frac{dy}{dt}\right)^2}\,dt$$

$L$ is also the distance traveled by the point from $\alpha$ to $\beta$. So, its derivative gives us the velocity of that point:

> $$v(t)=s'(t)=\sqrt{\left(\frac{dx}{dt}\right)^2+\left(\frac{dy}{dt}\right)^2}$$

## Surface area
In the same way as for arc length, we can obtain a formula for [[surface area of a curve|surface area]].

> $$ds=\sqrt{\left(\frac{dx}{dt}\right)^2+\left(\frac{dy}{dt}\right)^2}\,dt$$

And for rotation around the x-axis, we have

> $$S=\int^\beta_\alpha 2\pi y\, ds$$

and rotation around the y-axis is

> $$S=\int^\beta_\alpha 2\pi x\, ds$$
