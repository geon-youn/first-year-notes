---
alias: standardized value, z-score, empirical rule, outlier identification
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 12:34:23 
---
# Standardizing
Often we wish to compare and merge very different variables. To do so, the values are standardized by measuring how far they are from the mean. We measure the distance from the mean with the [[spread|standard deviation]], and the result is the standardized value which records how many standard deviations each value is above or below the mean.

**Standardized value (z-score)**: how many standard deviations a value is from the mean
$$z=\frac{y-\overline{y}}{s}$$

```ad-tip
A rule of thumb for identifying outliers is $|z|>3$
![[Pasted image 20220313123758.png]]
```

**Standardizing**: the process of finding the z-score of all sample values in the data. 
![[Pasted image 20220313123709.png]]

**Empirical rule**: given the sample mean $\overline{x}$, the sample standard deviation $s$ and a relatively symmetric and bell-shaped distribution, approximately
- 68% of all [[data value|observation]] fall in the interval $\overline{x}\pm s$
- 95% of all observation fall in the interval $\overline{x}\pm 2s$
- 99.7% (almost 100%) of all observation fall in the interval $\overline{x}\pm 3s$

**Outlier identification**: based on [[5-number summary and boxplots|upper fence]] and lower fence. 