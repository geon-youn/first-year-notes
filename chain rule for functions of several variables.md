---
alias: 
tags: MATH_1ZB3
created: Monday March 28, 2022; 15:41:37 
---
# Chain rule for functions of several variables
## Case 1
If $z=f(x,y)$ is a [[functions of two variables]] and is [[differentiable for a function of several variables|differentiable]] for $x$ and $y$, where $x=g(t)$ and $y=h(t)$ are both differentiable functions of $t$, then $z$ is a differentiable function of $t$ and

> $$\frac{dz}{dt}=\frac{\partial z}{\partial x}\frac{dx}{dt} + \frac{\partial z}{\partial y}\frac{dy}{dt}$$

Proof: use the definition of [[differentiable for a function of several variables|increment]], divide both sides by $\Delta t$ and show that $\epsilon_1,\epsilon_2\rightarrow0$. 

## Case 2
If instead $x=g(s,t)$ and $y=h(s,t)$ are differentiable functions of $s$ and $t$, then

> $$\frac{\partial z}{\partial s}=\frac{\partial z}{\partial x}\frac{\partial x}{\partial s}+\frac{\partial z}{\partial y}\frac{\partial y}{\partial s}$$

and 

> $$\frac{\partial z}{\partial t}=\frac{\partial z}{\partial x}\frac{\partial x}{\partial t}+\frac{\partial z}{\partial y}\frac{\partial y}{\partial t}$$

$s$ and $t$ are independent variables, $x$ and $y$ are intermediate variables, and $z$ is the dependent variable. 

## General
Suppose $u$ is a differentiable [[functions of three or more variables|function of $n$ intermediate variables]] $x_1,\dots,x_n$, each of which is a function of $m$ independent variables $t_1,\dots,t_m$.  Then $u$ is a function of $t_1,\dots,t_m$ and

> $$\frac{\partial u}{\partial t_i}=\frac{\partial u}{\partial x_1}\frac{\partial x_1}{\partial t_i}+\frac{\partial u}{\partial x_2}\frac{\partial x_2}{\partial t_i}+\dots+\frac{\partial u}{\partial x_n}\frac{\partial x_n}{\partial t_i}$$