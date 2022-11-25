---
alias:
tags: COMPSCI_1JC3
---
# Two's Complement for [[machine integers|Machine Integers]] Using $2^n$ Bits
Has **one** 0; **$2^{n-1}-1$** positives; **$2^{n-1}$** negatives. Positive numbers look as expected; negative numbers have **1** as the most significant bit (since it denotes that they're negative).

You can negate a number by **inverting** its bits and adding **1**. 

$$x+(-x)=0$$

Addition and multiplication are performed using [[modular integers|modular arithmetic]].