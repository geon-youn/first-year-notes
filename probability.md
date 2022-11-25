---
alias: probability assignment rule, complement rule, multiplication rule, independent, dependent, addition rule, disjoint, mutually exclusive, general addition rule, general multiplication rule, marginal probability, conditional probability, joint probability
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 15:47:53 
---
# Probability
The **(theoretical) probability** of event $A$ can be computed with the following equation:
$$P(A)=\frac{\text{No. of outcomes in $A$}}{\text{Total no. of outcomes}}$$
if the outcomes are equally likely. 

## Probability rules
1. If the probability of an event occurring is $0$, the event can't occur. If the probability is $1$, the event always occurs. Probability is a number between $0$ and $1$: $0\leq P(A) \leq 1$. 
2. The **probability assignment rule**: the probability of the set of all possible outcomes ($S$; also called [[Pierre-Simon Laplace's classical theory of probability|sample space]]) must be $1$:
$$P(S)=1$$
3. The **complement rule**: the probability of an event occurring is 1 minus the probability that it doesn't occur:
$$P(A)=1-P(A^C)$$
where the set of outcomes are are not in event $A$ is called the *complement of $A$* and is denoted $A^C$. 
![[Pasted image 20220313155224.png]]
4. The **multiplication rule**: for **two independent events** $A$ and $B$, the probability that both $A$ and $B$ occur is the product of the probabilities of the two events:
$$P(A\text{ and } B)=P(A\cap B)=P(A)\times P(B)$$
provided that $A$ and $B$ are independent.

**[[independence|Independent events]]**: the outcome of one event does not affect the outcome of the other.
**Dependent events**: the outcome of one event affects the outcome of the other.

```ad-tip
To test for [[independence]], use the above formula. 
```

5. The **addition rule**: for **two disjoint events** $A$ and $B$, the probability that either $A$ or $B$ occurs is the sum of their probabilities:
$$P(A\text{ or }B)=P(A\cup B)=P(A)+P(B)$$
where $A$ and $B$ are disjoint. 

**Disjoint (mutually exclusive)**: if two events have no outcomes in common.

| Disjoint                             | Not disjoint                         |
| ------------------------------------ | ------------------------------------ |
| ![[Pasted image 20220313155639.png]] | ![[Pasted image 20220313155642.png]] | 

6. The **general addition rule**: calculates the probability that either of two events occurs. It doesn't require that the events be disjoint (since $P(A\text{ and }B)=0$ if disjoint):
$$P(A\text{ or }B)=P(A)+P(B)-P(A\text{ and }B)$$

7. The **general multiplication rule**: calculates the probability that both of the two events occurs. It doesn't require that the events are independent (since $P(B\mid A) = P(B)$ if independent). 
$$P(A\text{ and }B)=P(A)\times P(B\mid A)=P(B)\times P(A\mid B)$$

## Probability from tables
Events can be placed in a [[contingency table]] like the one below

| Sex/Prize Preference | Skis | Camera | Bike | Total |
| -------------------- | ---- | ------ | ---- | ----- |
| Man                  | 117  | 50     | 60   | 227   |
| Woman                | 130  | 91     | 30   | 251   |
| Total                | 247  | 141    | 90   | 478   |

### Marginal probability
**Marginal probability** depends only on totals found in the margins of the table. 

```ad-example
$$P(\text{Man})=\frac{227}{478}$$
$$P(\text{Ski})=\frac{247}{478}$$
are both marginal probabilities, but
$$P(\text{Man}\cap\text{Ski})=\frac{117}{478}$$
is not. 
```

### Joint probability
**Joint probability**: gives the probability of two events occurring together. 

```ad-example
$$P(\text{Woman}\cap\text{Camera})=\frac{91}{478}$$
```

### [[Conditional probability]]
Each row or column shows a **conditional distribution** given one event.
```ad-example
$$P(\text{Woman}|\text{Bike})=\frac{30}{90}$$
$$P(\text{Bike}|\text{Woman})=\frac{30}{231}$$
```

The sample space becomes one of the margins. 

In general, when we want the probability of an event from a conditional distribution, we write $P(B\mid A)$ and say "the probability of $B$ given $A$".

**[[Conditional probability]]**: a probability that takes into account a given condition.
$$P(B\mid A)=\frac{P(B\cap A)}{P(A)}$$