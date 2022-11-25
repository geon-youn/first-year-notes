---
alias: scalar dot product, dot product
tags: MATH_1B03
---
# Inner Product (Scalar Dot Product)
The **inner product** of two vectors $\vec{u}$ and $\vec{v}$ in $\mathbb{R}^n$ returns a scalar in $\mathbb{R}$ and is calculated by:
$$\vec{u}^T\vec{v}=\vec{v}^T\vec{u}=\vec{u}\cdot\vec{v}=u_1v_1+\dots+u_nv_n$$

```ad-note
Given a vector $\vec{\theta}$ that makes an angle $\theta$ with the [[unit vector]] $\vec{e_1}$, its dot product is $\vec{\theta}\cdot\vec{e_1}=\cos{\theta}\cdot{1}+\sin{\theta}\cdot{0}=\cos{\theta}$. So, if we had two vectors that can be turned into $\vec{u}$ and $\vec{v}$ from $\vec{\theta}$ and $\vec{e_1}$ and preserve that angle $\theta$ between the two vectors, its dot product is then $\vec{u}\cdot\vec{v}=||\vec{u}||\cdot||\vec{v}||\cos{\theta}$.

Therefore, the angle formed between two vectors is given by the following equation:
$$\cos{\theta}=\frac{\vec{u}\cdot\vec{v}}{||\vec{u}||\cdot||\vec{v}||}$$
```