---
alias:
tags: COMPSCI_1JC3
---
# Product Type
A **product type** is an [[algebraic data type]] that has one constructor and the same structure as a [[synonym type|tuple type]]. For example, 
```haskell
data Point = MakePoint Float Float
```
has the same structure as
```haskell
type Point = (Float, Float)
```