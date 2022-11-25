---
alias: p bar, test statistic
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 20:42:57 
---
# Comparing two proportions for hypothesis testing
We bring together [[comparing two proportions]] and [[hypothesis testing]]. 
## Two-proportion z-test
Testing whether the difference between two proportions is equal to a give number, $K$.

In other to test
$$\left\{\begin{array}{c}
H_0:p_1-p_2=K\\
H_A:p_1-p_2\neq K
\end{array}\right.$$

we calculate the test [[population and parameters|statistic]]:

$$z=\frac{\hat{p_1}-\hat{p_2}-K}{SE(\hat{p_1}-\hat{p_2})}$$

where

$$SE(\hat{p_1}-\hat{p_2})=\sqrt{\frac{\hat{p_1}\hat{q_1}}{n_1} + \frac{\hat{p_2}\hat{q_2}}{n_2}}$$

we then obtain the corresponding [[p-value]] from the table for the [[normal distribution]].

## Two-proportion z-test for equal proportions
Testing whether two proportions are equal.

In order to test

$$\left\{\begin{array}{c}
H_0:p_1-p_2=0 \Rightarrow p_1=p_2\\
H_A:p_1-p_2\neq 0\Rightarrow p_1\neq p_2
\end{array}\right.$$

we calculate the test statistic:

$$z=\frac{\hat{p_1}-\hat{p_2}}{SE(\hat{p_1}-\hat{p_2})}$$

where

$$SE(\hat{p_1}-\hat{p_2})=\sqrt{\overline{p}\overline{q}\left(\frac{1}{n_1} + \frac{1}{n_2}\right)}$$

and 

$$\overline{p}=\frac{n_1\hat{p_1}+n_2\hat{p_2}}{n_1+n_2}$$ 

and

$$\overline{q}=1-\overline{p}$$

we then obtain the corresponding p-value from the table for the normal distribution.