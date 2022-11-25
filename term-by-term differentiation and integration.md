---
alias: 
tags: MATH_1ZB3
created: Saturday March 12, 2022; 14:16:54 
---
# Term-by-term differentiation and integration
If the [[power series]] $\sum^\infty_{n=0}c_n(x-a)^n$ has [[power series|radius of convergence]] $R>0$, then the function $f$ defined by
$$f(x)=c_0+c_1(x-a)+c_2(x-a)^2+\cdots=\sum^\infty_{n=0}c_n(x-a)^n$$
is differentiable (and thus continuous) on the interval $(a-R, a+R)$ and
$$f'(x)=c_1+2c_2(x-a)+3c_2(x-a)^2+\cdots=\sum^\infty_{n=0}nc_n(x-a)^{n-1}$$
and
$$\begin{align*}
\int f(x)dx&=C+c_0(x-a)+c_1\frac{(x-a)^2}{2}+c_2\frac{(x-a)^3}{3}+\cdots\\
           &=C+\sum^\infty_{n=0}c_n\frac{(x-a)^{n+1}}{n+1}
\end{align*}$$
the radii of convergence of the power series remains as $R$. 