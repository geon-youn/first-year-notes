---
alias:
tags: COMPSCI_1JC3
---
# Floating Point Numbers
Rational numbers are represented in base 2 scientific notation with a **fixed** number of bits
$$\pm 1.m\cdot 2^e$$
where $1.m$ is called the **mantissa** and $e$ the **exponent**.

**Single-precision** floating numbers use **32** bits with 1 bit for the sign, 23 bits for the (unsigned) mantissa, and 8 bits for the (signed) exponent. **Double-precision** floating numbers use **64** bits instead with 1 bit for the sign, 52 bits for the (unsigned) mantissa, and 11 bits for the (signed) exponent. 

Floating point numbers have five special values that result from [[floating point arithmetic]].
 
## Equality
Tests for `x==y`or `x/=y`should be avoided when `x`and `y` are floating point numbers. Only a small number of real numbers are exactly represented by floating point numbers. A better way to check for equality is to compare it to a small value like `abs (x - y) < epsilon` where `epsilon` can change depending on the context.
