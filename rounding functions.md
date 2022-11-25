---
alias: ceiling, floor
tags: COMPSCI_1DM3
created: February 10, 2022 14:11
---
# Rounding Functions
There are two main rounding functions available: ceiling and flooring.

## Ceiling
Smallest integer greater than or equal to $x$:
$$f(x)=\lceil{x}\rceil$$

## Floor
Largest integer smaller than or equal to $x$:
$$f(x)=\lfloor{x}\rfloor$$

## Properties
Where $n$ is an integer and $x$ is a real number:
- $\lfloor x \rfloor = n$ iff $n\leq x < n + 1$ or $x-1 < n \leq x$
- $\lceil x \rceil = n$ iff $n-1 < x \leq n$ or $x\leq n < x + 1$

- $x - 1 < \lfloor x \rfloor \leq x \leq \lceil x \rceil < x + 1$

- $\lceil -x \rceil = -\lceil x \rceil$
- $\lfloor -x \rfloor = - \lfloor x \rfloor$

- $\lceil x + n \rceil = \lceil x \rceil + n$
- $\lfloor x + n \rfloor = \lfloor x \rfloor + n$