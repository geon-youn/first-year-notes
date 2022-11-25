---
alias:
tags: MATH_1C03
---
# Bezout's Identity
Let $a$ and $b$ be [[integers]] not both equal to zero. There exists integers $n$ and $m$ such that
$$\operatorname{gcd}(a,b)=na+mb$$
For example, we apply the reverse of the [[greatest common divisor]] algorithm to write the greatest common divisor in terms of $a$ and $b$. 
```python
a = 81
b = 24
gcd(a,b)=3
# 81 = 24 * 3 + 9
# 24 = 9 * 2 + 6
# 9 = 6 * 1 + 3
# 6 = 3 * 2 + 0

# 9 = 81 - 24 * 3
# 6 = 24 - 9 * 2 = 24 - (81 - 24 * 3) * 2 = -81 * 2 + 24 * 7
# 3 = 9 - 6 = (81 - 24 * 3) - (-81 * 2 + 24 * 7)
#   = 81 - 24 * 3 + 81 * 2 - 24 * 7
#   = 81 * 3 - 24 * 10
n = 3
m = -10
print(gcd(a,b) == (n * a + m * b)) # should return True
```

If $\operatorname{gcd}(a,b)=d$, then $\operatorname{gcd}(a/d,b/d)=1$. 
## Proof
Assume $d=\operatorname{gcd}(a,b)$, then $d=na+mb$ for some integers $n,m$. We can divide both sides to get $1=n\frac{a}{d}+m\frac{b}{d}$, then $a/d$ and $b/d$ are [[relatively prime]], so their GCD is $1$. 

## n and m are not unique
Let
$$\operatorname{gcd}(a,b)=d=na+mb$$
Then
$$0=(-bk)a+(ak)b,\forall k\in\mathbb{Z}$$
So adding them together,
$$d=(n-bk)a+(m+ak)b,\forall k\in\mathbb{Z}$$
We also have that $b/d$ and $a/d$ are integers, so
$$d=(n-\frac{bk}{d})a+(m+\frac{ak}{d})b,\forall k\in\mathbb{Z}$$