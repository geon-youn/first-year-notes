---
alias: quotient, remainder, divisor, dividend, div, mod, congruence
tags: MATH_1C03
---
# Division Algorithm
Given integers $a$ and $b$ with $b>0\Rightarrow \frac{a}{b}$.

The **divisor** is $b$ and the **dividend** is $a$. 

The **quotient** of $a$ by $b$ is the largest integer $q$ such that $bq\leq a$. 

The **remainder** is $r=a-bq$. Note that $0\leq r < b$. 

By definition of $q$ and $r$, $a=bq+r$, where $q=a\operatorname{div}b$ and $r=a\operatorname{mod}b$. 

## Theorem
Let $a,b\in\mathbb{Z}$ with $b>0$. There exists a unique pair of integers $q$ and $r$ with $0\leq r < b$ such that 
$$a=qb+r$$
$$a\equiv_br$$
$$a\equiv r(\operatorname{mod} b)$$
where it's read as "a is equivalent/[[congruence|congruent]] to modulo b to r."

## Algorithm (positive case)
Let $a,b$ be positive integers. We want to find $q,r$ such that $a=bq+r$ and $0\leq r < b$. 
```python
def division_algorithm(a: int, b: int) -> (int, int):
	q = 0
	r = a
	while r >= b:
		r -= b
		q += 1
	return (q, r)
```

## Proof
Let $S$ be a [[set]] such that $S=\left\{a-bn:n\in\mathbb{Z},a-bn\geq 0\right\}$. To apply the [[well-ordering principle]], we need to check $S$ is nonempty ($S\neq\emptyset$).

Case 1 ($a\geq0$): Let $n=0$, then $a-b\cdot 0=a\geq0$. $a\in S$ so $S$ is nonempty.

Case 2 ($a<0$): Let $n=a$, then $a-b\cdot a=(1-b)a\geq0$. $(1-b)a\in S$ so $S$ is nonempty. 

Thus by the well-ordering principle, there is a least element of $S$ and let's call it $r$. $r$ is unique. Let $q\in\mathbb{Z}$ such that $r=a-bq$. $q$ is also unique. 

## Example
The square of any integer is equal to $3k$ or $3k+1$, $k\in\mathbb{Z}$. 
$\forall n\in \mathbb{Z}$, $\exists k\in \mathbb{Z}$ such that $n^2=3k$ or $n^2=3k+1$. 
Proof: Fix $n\in\mathbb{Z}$ arbitrary. Want to show the above is true. By the division algorithm, $\exists q\in\mathbb{Z}$ such that $n=3q$ or $n=3q+1$ or $n=3q+2$. 

Case 1 ($n=3q$): $n^2=(3q)^2=3(3q^2)$ thus we have found $k=3q^2$ such that $n^2=3k$. 

Case 2 ($n=3q+1$): $n^2=(3q+1)^2=(9q^2+6q+1)=3(3q^2+2q)+1$ thus we have found $k=3q^2+2q$ such that $n^2=3k+1$.

Case 3 ($n=3q+2$): $n^2=(3q+2)^2=(9q^2+12q+4)=3(3q^2+4q+1)+1$ thus we have found $k=3q^2+4q+1$ such that $n^2=3k+1$. 

Therefore, for all $n\in\mathbb{Z}$, $n^2=3k$ or $n^2=3k+1$. 