---
alias:
tags: COMPSCI_1JC3
---
# Algebraic Data Types
An **algebraic data type** (or **algebraic type** for short; also known as an **inductive type**) is a new [[type]] of new [[value]]s formed as a "[[sum type|sum]]" of "[[product type|product]]s". 

```haskell
data t = C1 t1 ... tm
       | C2 t2 ... t2m 
	   | ...
	   | Cn tn ... tnm
```

where
- `t` is the name of the new type
- `Ci` is the **value constructor** that creates new values.
- `tj` is the types that may include `t` itself ([[recursive type]]). 

Each member of the type `t` is constructed from the constructors in exactly one way, given the phrase "no junk and no confusion."

A function can be defined on `t` by **pattern matching** with respect to the value constructors. At least one pattern is needed for each **constructor** of `t`. 

The definition of the algebraic type `t` induces an **induction principle** that can be used to prove that a property holds for all members of `t`. 

## Algebraic Types as Languages
An algebraic type `A`defines a new **language `L` of expressions**. `L` is infinite when `A` s recursive. The [[First Year/expression]]s of `L` are in a [[one-to-one]] correspondence with the values of `A`. In other words, the expressions of `L` serve as **literals** for the values of `A`. So, functions on `A` can be defined using pattern matching on the different forms of expressions of `L`. 