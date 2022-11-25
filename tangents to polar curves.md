---
alias: 
tags: COMPSCI_1DM3
created: Monday March 14, 2022; 18:16:52 
---
# Tangents to polar curves
To find a tangent line to a [[polar curves|polar curve]] $r=f(\theta)$, we regard $\theta$ as a parameter and write its [[parametric equation]] as

> $$x=r\cos\theta=f(\theta)\cos\theta$$
> $$y=r\sin\theta=f(\theta)\sin\theta$$

Then, using the method of finding slopes of parametric curves and the product rule, we have

> $$\frac{dy}{dx}=\frac{\frac{dy}{d\theta}}{\frac{dx}{d\theta}}
=\frac{\frac{dr}{d\theta}\sin\theta+r\cos\theta}
{\frac{dr}{d\theta}\cos\theta-r\sin\theta}$$

We find horizontal tangets by finding the points where $dy/d\theta=0$, provided that $dx/d\theta\neq0$ and find vertical tangets at the points where $dx/d\theta=0$ provided that $dy/d\theta\neq0$. 