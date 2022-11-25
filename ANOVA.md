---
alias: 
tags: COMMERCE_1DA3
created: Thursday March 24, 2022; 15:13:08 
---
# ANOVA (Analysis of Variance)
Previously, we covered comparisons between two [[centre|population means]]. Sometimes, we need to compare the mean or more than two populations.

ANOVA is used when we have samples from more than two populations and we want to study hypotheses on them.

ANOVA could be:
- One-way: there's only one independent variable and you want to measure the response.
- Two-way: there's two independent variables and you want to measure the response. 

If we compare samples individually, we need many separate t-tests. Each would involve some risk of error. ANOVA keeps the risk of error low. 

To perform ANOVA, we need [[experiment design]]s (we need to design experiments such that they only have one or two independent variables). 

Three assumptions:
1. Values in each population (response) are normally distributed.
2. Variance of all populations are equal $\sigma_1=\sigma_2=\dots=\sigma_k$.
3. The observations must be independent.

Hypotheses:
- In ANOVA, generally the null hypothesis assumes that the means of all populations are equal $\mu_1=\mu_2=\dots=\mu_k$.
- The alternate hypothesis states that at least one of the population means is not equal to another population mean. In other words, "not all population means are equal."