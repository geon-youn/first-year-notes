---
alias:
tags: MATH_1B03
---
# Orthogonal Projection
Given a vector $\vec{u}\neq\vec{0}$, $\vec{y}\in\mathbb{R}^n$, find $\alpha\in\mathbb{R}$, $\vec{z}\in\mathbb{R}^n$ such that
$$\vec{y}=\alpha\vec{u}+\vec{z}$$
where $\vec{z}$ is [[orthogonal]] to $\vec{u}$. 

If we want $\vec{z}=(\vec{y}-\alpha\vec{u})\perp\vec{u}$, then $\vec{y}\cdot\vec{u}-\alpha\vec{u}\cdot\vec{u}=0$. Then, 
$$\alpha=\frac{\vec{y}\cdot\vec{u}}{\vec{u}\cdot\vec{u}}=\frac{\vec{y}\cdot\vec{u}}{||\vec{u}||^2}$$

Then, we call $\alpha\vec{u}$ the projection of $\vec{y}$ onto $\vec{u}$ such that

$$\widehat{\vec{y}}=\operatorname{proj}_\vec{u}\vec{y}=\alpha\vec{u}=\frac{\vec{y}\cdot\vec{u}}{||\vec{u}||^2}\vec{u}$$

![[Pasted image 20211117192247.png|600]]

# Distance from vector to plane
The shortest distance from a vector to a plane is the length of the given vector minus its projection onto the plane, such that we take the length of a vector that is orthogonal to the plane ($\operatorname{proj}_{W^\perp}(\boldsymbol{y})$ in the image). Let $W$ be a [[subspace]] in $\mathbb{R}^n$. Then each $\boldsymbol{y}$ in $\mathbb{R}^n$ can be written uniquely in the form $\boldsymbol{y}=\widehat{\boldsymbol{y}}+\boldsymbol{z}$ where $\widehat{\boldsymbol{y}}$ is in $W$ and $\boldsymbol{z}$ is in $W^\perp$. If $\left\{\boldsymbol{u_1},\dots,\boldsymbol{u_p}\right\}$ is any [[orthogonal basis]]  of $W$, then
$$\widehat{\boldsymbol{y}}=\frac{\boldsymbol{y}\cdot\boldsymbol{u_1}}{\boldsymbol{u_1}\cdot\boldsymbol{u_1}}\boldsymbol{u_1} +\cdots+\frac{\boldsymbol{y}\cdot\boldsymbol{u_p}}{\boldsymbol{u_p}\cdot\boldsymbol{u_p}}\boldsymbol{u_p}$$
and $\boldsymbol{z}=\boldsymbol{y}-\widehat{\boldsymbol{y}}$. Then, the shortest distance will be the length of $\boldsymbol{z}$: $||\boldsymbol{z}||=||\boldsymbol{y}-\widehat{\boldsymbol{y}} ||$. 