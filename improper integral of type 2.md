---
alias: type 2, convergent, divergent, improper integral
tags: MATH_1ZB3
created: Saturday March 12, 2022; 10:35:01 
---
# Improper integral of type 2
If $f$ is continuous on $[a, b)$ and is discontinuous at $b$, then
$$\int{b}_af(x)dx=\lim_{t\rightarrow b^-}\int^{t}_{a}f(x)dx$$
if this limit exists (as a finite number).

If $f$ is continuous on $(a, b]$ and is discontinuous at $a$, then
$$\int^{b}_{a}f(x)dx=\lim_{t\rightarrow a^+}\int^{b}_{t}f(x)dx$$
if this limit exists (as a finite number).

The improper integral $\int^{b}_{a}f(x)dx$ is called **convergent** if the corresponding limit exists and **divergent** if the limit does not exist. 

If $f$ has a discontinuity at $c$, where $a<c<b$, and both $\int^{c}_{a}f(x)dx$ and $\int^{b}_{c}f(x)dx$ are convergent, then 
$$\int^{b}_{a}f(x)dx = \int^{c}_{a}f(x)dx + \int^{b}_{c}f(x)dx$$

```ad-warning
Whenever you see the symbol $\int^{b}_{a}f(x)dx$, you must decide by looking at the function $f$ on $[a, b]$, whether it is an ordinary definite integral or an improper integral.
```
