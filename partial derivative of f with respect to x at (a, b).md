---
alias: partial derivative
tags: MATH_1ZB3
created: Monday March 28, 2022; 14:12:45 
---
# Partial derivative of f with respect to x at (a, b)
If $f$ is a [[functions of two variables]] $x$ and $y$ and we let only $x$ vary while keeping $y$ fixed, say $y=b$, where $b$ is a constant, then we're really considering a function of a single variable $x$, namely $g(x)=f(x,b)$. If $g$ has a derivative at $a$, then we call it the **partial derivative of $f$ with respect to $x$ at $(a, b)$** and denote it by $f_x(a, b)$. Thus

> $$f_x(a, b)=g'(a)\,\,\,\text{where }\,\,\,g(x)=f(x,b)$$

By the definition of a derivative, we have

> $$g'(a)=\lim_{h\rightarrow 0}\frac{g(a+h)-g(a)}{h}=\lim_{h\rightarrow0}\frac{f(a+h,b)-f(a,b)}{h}=f_x(a,b)$$

The **partial derivative of $f$ with respect to $y$ at $(a, b)$** denoted by $f_y(a, b)$ is obtained by keeping $x$ fixed and finding the ordinary derivative at $b$ of the function $G(y)=f(a,y)$

> $$f_y(a,b)=\lim_{h\rightarrow0}\frac{f(a,b+h)-f(a,b)}{h}$$

If we let the point $(a,b)$ vary, $f_x$ and $f_y$ become functions of two variables:

> If $f$ is a function of two variables, its **partial derivatives** are the functions $f_x$ and $f_y$ where
$$f_x(x,y)=\lim_{h\rightarrow0}\frac{f(x+h,y)-f(x,y)}{h}$$
$$f_y(x,y)=\lim_{h\rightarrow0}\frac{f(x,y+h)-f(x,y)}{h}$$

> If $z=f(x,y)$, we write
$$f_x(x,y)=f_x=\frac{\partial f}{\partial x}=\frac{\partial}{\partial x}f(x,y)=\frac{\partial z}{\partial x}=f_1=D_1f=D_xf$$
$$f_y(x,y)=f_y=\frac{\partial f}{\partial y}=\frac{\partial}{\partial y}f(x,y)=\frac{\partial z}{\partial y}=f_2=D_2f=D_yf$$

> 1. To find $f_x$, regard $y$ as a constant and differentiate $f(x,y)$ with respect to $x$.
> 2. To find $f_y$, regard $x$ as a constant and differentiate $f(x,y)$ with respect to $y$. 

In general, if $u$ is a function of $n$ variables, $u=f(x_1,x_2,\dots,x_n)$, its partial derivative with respect to the $i$th variable $x_i$ is

> $$\frac{\partial u}{\partial x_1}=\lim_{h\rightarrow0}\frac{f(x_1,\dots,x_{i-1},x_i+h,x_{i+1},\dots,x_n)-f(x_1,\dots,x_i,\dots,x_n)}{h}=\frac{\partial f}{\partial x_i}=f_{x_i}=f_i=D_if$$