---
alias: differentiable, increment
tags: MATH_1ZB3
created: Monday March 28, 2022; 15:24:34 
---
# Differentiable for a function of several variables
For a function of one variable, $y=f(x)$, if $x$ changes from $a$ to $a+\Delta x$, we define the **increment** of $y$ as

$$\Delta y=f'(a)\Delta x + \epsilon\Delta x$$

where $\epsilon\rightarrow0$ as $\Delta x\rightarrow0$. 

With a [[functions of two variables]], $z=f(x,y)$, if $x$ changes from $a$ to $a+\Delta x$ and $y$ changes from $b$ to $b+\Delta y$, then the corresponding increment of $z$ is

$$\Delta z=f(a+\Delta x, b+\Delta y)-f(a,b)$$

So, $f$ is **differentiable** at $(a,b)$ if $\Delta z$ can be expressed in the form

> $$\Delta z=f_x(a,b)\Delta x+f_y(a,b)\Delta y+\epsilon_1\Delta x + \epsilon_2\Delta y$$

where $\epsilon_1,\epsilon_2\rightarrow0$ as $(\Delta x,\Delta y)\rightarrow0$. 

```ad-tip
title: Easier way to show the above
If the [[partial derivative of f with respect to x at (a, b)|partial derivative]]s $f_x$ and $f_y$ exist near $(a,b)$ and are continuous at $(a,b)$, then $f$ is differentiable at $(a,b)$. 
```


For a [[functions of three or more variables]], we have the increment of $w=f(x,y,z)$ as

> $$\Delta w = f(x + \Delta x, y+\Delta y, z+\Delta z)-f(x,y,z)$$