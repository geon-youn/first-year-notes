---
alias: identity, domination, idempotent, double negation, negation, commutative, associative, distributive, absorption
tags: COMPSCI_1DM3
created: January 19, 2022 11:04
---
# Key Logical Equivalences
## Identity Laws
$$p\land T\equiv p$$
$$p\lor F\equiv p$$
## Domination Laws
$$p\lor T\equiv T$$
$$p\land F\equiv F$$
## Idempotent Laws
$$p\lor p\equiv p$$
$$p\land p\equiv p$$
## Double Negation Law
$$\neg (\neg p)\equiv p$$
## Negation Laws
$$p\lor \neg p\equiv T$$
$$p\land \neg p\equiv F$$
## Commutative Laws
$$p\lor q\equiv q\lor p$$
$$p\land q\equiv q\land p$$
## Associative Laws
$$(p\land q)\land r\equiv p\land (q\land r)$$
$$(p\lor q)\lor r\equiv p\lor (q\lor r)$$
## Distributive Laws
$$(p\lor(q\land r))\equiv(p\lor q)\land (p\lor r)$$
$$(p\land(q\lor r))\equiv(p\land q)\lor (p\land r)$$
## Absorption Laws
$$p\lor(p\land q)\equiv p$$
$$p\land(p\lor q)\equiv p$$