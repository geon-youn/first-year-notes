---
alias: 
tags: MATH_1ZB3
created: Monday March 21, 2022; 14:25:35 
---
# Limits of functions of two variables
Let $f$ be a [[functions of two variables]] whose domain $D$ includes points arbitrarily close to $(a, b)$. Then we say that the [[limit]]of $f(x, y)$ as $(x, y)$ approaches $(a, b)$ is $L$ and we write 

> $$\lim_{(x,y) \rightarrow (a,b)}f(x,y)=L$$

if for every number $\epsilon > 0$ there is a corresponding number $\delta > 0$ such that if
$(x,y)\in D$ and $0 < \sqrt{(x-a)^2+(y-b)^2}<\delta$ then $|f(x,y)-L|<\epsilon$. 

If any small interval $(L-\epsilon, L+\epsilon)$ is given around $L$, then we can find a disk $D_\delta$ with center $(a,b)$ and radius $\delta>0$ such that $f$ maps all the points in $D_\delta$ (except possibly at $(a,b)$) into the interval $(L-\epsilon,L+\epsilon)$. 

![[Pasted image 20220321143100.png]]

```ad-note
title: Other notations
$$\lim_{\begin{matrix}x\rightarrow a\\y\rightarrow b\end{matrix}}f(x,y)=L$$
and
$$f(x,y)\rightarrow L\,\,\,\text{ as }\,\,\,(x,y)\rightarrow(a,b)$$
```

With limits for functions of single variables, we only had to check if the function approached a value from both sides. With limits of functions of two variables, the definition only refers to the *distance* between $(x, y)$ and $(a, b)$ and not the *direction*. So if the limit exists, then $f(x, y)$ must approach the same limit no matter how $(x, y)$ approaches $(a, b)$. Then if we find two different paths of approach where $f(x, y)$ have different limits, then it follows that $\lim_{(x,y) \rightarrow (a,b)}f(x,y)$ does not exist. 

> If $f(x, y)=L_1$ as $(x, y)\rightarrow(a,b)$ along a path $C_1$ and $f(x, y)=L_2$ as $(x,y)\rightarrow(a,b)$ along a path $C_2$, where $L_1\neq L_2$, then $\lim_{(x,y) \rightarrow (a,b)}f(x,y)$ does not exist. 

You can typically solve questions like this by setting $y=b$ and approaching $x\rightarrow a$ for $C_1$ and setting $x=a$ and approaching $y\rightarrow b$ for $C_2$. You can also set a path of $y=x$. 