---
alias: within group, between group, SSE, SST, MST, MSE, mean square due to treatments, mean square due to error, sum of squares between treatments, sum of squares error
tags: COMMERCE_1DA3
created: Saturday March 26, 2022; 10:31:11 
---
# One-way ANOVA
Consider an [[ANOVA]] experiment with a single factor of $k$ levels.

> Is there evidence for differences in effectiveness for the [[experiment design|treatments]]?

Let $\mu_i$ be the mean response for treatment group $i$. Then, to answer the question, we must test the hypothesis

> $H_0:\mu_1=\mu_2=\dots=\mu_k$ (no difference in treatments).
> $H_A:$ at least one mean is different.

There's two classes of variation in a [[experiment design|factorial design]]:
1. "Between group": Variation of the group means $\mu_i$ about the grand mean.
2. "Within group": Variation of the group data about the group means.

> We can reject the null hypothesis when the "between group" variation is *larger compared to* the "within group" variation. 

We need to use a tool (test statistic called the [[F statistic]]) that measures the ratio of "between group" variation to "within group" variation.

If the value of this test statistic is higher than a certain threshold, we can conclude that the null hypothesis can't be true (at least one mean is not equal to the rest).

To quantify these two classes of variation, we introduce new measures of variability for one-factor experiments with $k$ levels:
1. The mean square due to treatments (MST; between group variation measure).
    - In each instance, $(\overline{y}_i-\overline{y})^2$ measures the between group variation. 
    - The sum of squares between treatments (SST) is 
    $$SST=\sum^{k}_{i=1}n_1(\overline{y}_i-\overline{y})^2$$
     where $n_i$ is the number of observations in each group
    - To turn this estimate of variation to variance, we divide the SST by its associated degrees of freedom:
     $$MST=\frac{SST}{k-1}$$
2. The mean square due to error (within group variation measure).
    - We compare SST with how much variation there is within each group. The sum of squares error (SSE) is
    $$SSE=\sum^{k}_{i=1}(n_i-1)s^2_i$$
    $$MSE=\frac{SSE}{N-k}$$
    where $s_i$ is the sample variance of group $i$, and $N$ is the total number of observations
3. The total sum of squares will be
$$SS_{total}=SST+SSE$$