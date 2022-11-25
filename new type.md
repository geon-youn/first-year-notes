---
alias:
tags: COMPSCI_1JC3
---
# New Type Declarations
A **new type** is semantically equivalent to a [[type]] defined by a [[algebraic data type|data declaration]] with a single one-argument constructor. For example,

```haskell
newtype new_type a b = constructor old_type_that_uses_a_and_b 
newtype Function a b = Function a -> b
newtype Vector3 a = MakeVector (a,a,a)
newtype Nat = Nat Integer
```

The `new-type` is treated as a distinct type from `old-type` during **compile time**, but as `old-type` during **run time**.