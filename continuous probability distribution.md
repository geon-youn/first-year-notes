---
alias: probability density function, pdf
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 16:51:22 
---
# Continuous probability distribution
A [[random variable|continuous random variable]] is a random variable that may take on any value in some interval $[a, b]$. 

The distribution of the probabilities can be shown with a curve, $f(x)$ called a **probability density function (pdf)**
![[Pasted image 20220313165211.png]]

A PDF does not provide probabilities directly. The area under the PDF between two values $a, b$ represent the probability $P(a\leq X \leq b$. The entire area under $f(x)$ equals $1$. 

Therefore, it's only meaningful to find the probability that the value of $X$ falls within some specified interval:

$$P(a\leq X\leq B=P(a < X < b)=P(a \leq X < b)=P(a < X \leq B)$$

because

$$P(X=a)=0$$

and

$$P(X=b)=0$$

Density functions must satisfy these requirements:
1. They must be non-negative for every possible value.
2. The area under the curve must exactly equal $1$. 

**Uniform density function**:

$$f(x)=\left\{\begin{array}{cr}\frac{1}{b-a} & \text{ if } a\leq x \leq b\\
0 & \text{ otherwise}\end{array}\right.$$
![[Pasted image 20220313165808.png]]

For values $c,d$ where $c\leq d$ both within the interval $[a,b]$, 
$$P(c\leq X \leq d)=\frac{d-c}{b-a}$$

Expected value:
$$E(X)=\frac{a+b}{2}$$

Variance:
$$Var(X)=\frac{(b-a)^2}{12}$$

Standard deviation:
$$SD(X)=\sqrt{\frac{(b-a)^2}{12}}$$