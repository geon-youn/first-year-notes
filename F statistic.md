---
alias: 
tags: COMMERCE_1DA3
created: Tuesday March 29, 2022; 14:45:22 
---
# F statistic
In [[ANOVA]], we use the same concepts; variation between groups and variation within groups, to determine whether population means under study are equal.

We use a statistic called the F statistic for [[one-way ANOVA]]. **F statistic** includes both *between* and *within* variation at the same time and has the *F distribution*:

> $$F=\frac{\text{mean variance }\textbf{between }\text{groups}}{\text{mean variation }\textbf{within }\text{groups}}$$

When $F$ is *greater* than the critical value (which we can find using the F-table with the two degrees of freedom), then between group variation is larger enough than within group variation and we can reject the [[hypothesis testing|null hypothesis]]. 

```ad-tip
The $F$ test is always a one-sided (right) test. 
```

> When there is **no difference in treatments**, the ratio **[[one-way ANOVA|MST]]/[[one-way ANOVA|MSE]] follows the F-statistic**
$$F_{k-1,N-k}=\frac{MST}{MSE}=\frac{\frac{SST}{k-1}}{\frac{SSE}{N-k}}$$