---
alias: 
tags: MATH_1ZB3
created: Saturday March 12, 2022; 15:30:37 
---
# Surface area of a curve
If $f$ is positive and has a continuous derivative, then its surface area of the surface obtained by rotating the curve $y=f(x)$, $a\leq x \leq b$ about the $x$ axis as
$$S=\int^b_a2\pi y\sqrt{1+\left(\frac{dy}{dx}\right)^2}dx$$
If the curve is described as $x=g(y)$, $c\leq y\leq d$, then the formula for surface area becomes
$$S=\int^d_c2\pi y\sqrt{1+\left(\frac{dx}{dy}\right)^2}dy$$
and both formulas can be simplified to
$$S=\int 2\pi y \,ds$$

and for rotation about the $y$ axis, the surface area formula becomes 

$$S=\int 2\pi x \,ds$$

where, as before
$$ds = \sqrt{1+\left(\frac{dy}{dx}\right)^2}dx$$

or 

$$ds = \sqrt{1+\left(\frac{dx}{dy}\right)^2}dy$$

```ad-tip
Think of them as $2\pi y$ and $2\pi x$, which is the circumference of a circle traced out by the point $(x, y)$ on the curve as it's rotated about the $x$ axis or $y$ axis, respectively. 
```

