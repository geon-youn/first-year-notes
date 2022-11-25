---
alias: 
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 19:26:15 
---
# Comparing two proportions
Sometimes we need to compare the value of two populations ($p_M-p_O$).

The [[population and parameters|sample statistic]] used to estimate $p_M-p_O$ is $\hat{p_M}-\hat{p_O}$ with the following distribution:

$$\hat{p_M}-\hat{p_O}\sim N\left(
p_M-p_O, 
\sqrt{
    \frac{\hat{p_M}(1-\hat{p_M})}{n_M} + 
    \frac{\hat{p_O}(1-\hat{p_O})}{n_O}}
\right)$$

Not knowing what the true population proportions for the two provinces are, we can construct a [[confidence interval]] for the difference between the two true population proportions.

$$(\hat{p_M}-\hat{p_O})\pm z^*SE(\hat{p_M}-\hat{p_O})$$

To develop a confidence interval, we follow these step:
1. Take a sample of size $n_M$ for the first population.
2. Take a sample of size $n_O$ for the second population.
3. Calculate the [[standard error]] of proportion for the first sample.
4. Calculate the standard error of proportion for the second sample.
5. Calculate the standard error of the difference of proportions (sum of the variances square rooted).
$$
\sqrt{
    \frac{\hat{p_M}(1-\hat{p_M})}{n_M} + 
    \frac{\hat{p_O}(1-\hat{p_O})}{n_O}}$$
6. Determine the critical value based on the certainty level. 