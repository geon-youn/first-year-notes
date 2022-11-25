---
alias: integrating factor
tags: MATH_1ZB3
created: Saturday March 12, 2022; 17:02:39 
---
# Linear differential equation
A first-order **linear** [[differential equation]] is of the form
$$\frac{dy}{dx} + P(x)y = Q(x)$$
where $P$ and $Q$ are continuous functions on a given interval. To solve this equation, we have to use an **integrating factor** $I(x)$ that will allow the left side to be integrated by reversing the product rule:
$$I(x)(y'+P(x)y)=(I(x)y)'$$
Then expand and cancel out terms to get
$$I(x)P(x)=I'(x)$$
which is a separable equation for $I$:
$$\begin{align*}
\frac{dI}{I}&=P(x)\,dx\\
\int\frac{dI}{I}&=\int P(x)\,dx\\
\ln|I|&=\int P(x)\, dx\\
I&=Ae^{\int P(x)\, dx}
\end{align*}$$
where $A=\pm e^C$, but since we just want a particular solution, we let $A=1$ and so $I(x)=e^{\int P(x)\, dx}$.

So, to solve the linear differential equation $y'+P(x)y=Q(x)$, multiply both sides by the integrating factor $I(x)=e^{\int P(x)\, dx}$ and then integrate both sides.