---
alias:
tags: COMPSCI_1JC3
---
# Floating Point Arithmetic
Arithmetic operations on [[floating point numbers]] return the floating point number that is the **best approximation** to the true value.
- `-0.0` or `0.0` is returned if the result is **too close to zero** to be represented (called **underflow**);
- `Infinity` is returned if the result is **too large** to be represented (called **positive overflow**);
- `-Infinity` is returned if the result is **too small** to be represented (called **negative overflow**);
- `NaN` (for "not a number") is returned if the result is not defined (e.g. `sqrt (-1)`).

Since floating point numbers can't precisely represent all real (or even rational) numbers, floating point arithmetic can produce inaccurate or even completely bogus results.
- Addition and multiplication are not **[[associativity|associative]]**.