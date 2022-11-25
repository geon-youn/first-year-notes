---
alias: 
tags: MATH_1ZB3
created: Monday April 4, 2022; 15:20:25 
---
# Maximizing the directional derivative
Suppose $f$ is a [[differentiable for a function of several variables|differentiable]] function of two or three variables. The maximum value of the [[directional derivative]] $D_\boldsymbol{u}f(\boldsymbol{x})$ is $\left| \nabla f(\boldsymbol{x}) \right|$ and it occurs when $\boldsymbol{u}$ has the same direction as the [[gradient vector]] $\nabla f(\boldsymbol{x})$. 

Proof:

$$D_\boldsymbol{u}f=\nabla f\cdot \boldsymbol{u}=|\nabla f||\boldsymbol{u}|\cos\theta=|\nabla f|\cos\theta$$

where $\theta$ is the angle between $\nabla f$ and $\boldsymbol{u}$. The maximum value of $\cos\theta$ is 1, which occurs when $\theta=0$ so the maximum occurs when $\boldsymbol{u}$ has the same direction as $\nabla f$. 