---
alias: sampling proportion
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 17:28:55 
---
# Sample proportion
If events have only two outcomes, we call them **success** and **failure** like in [[Bernoulli trial]]. The proportion of *success* in a [[sampling|sample]] is called the **sample proportion**.

The sample proportion is most probably different from the population proportion. 

We denote population proportion by $p$ and the sample proportion by $\hat{p}$. The sample proportion $\hat{p}$ is different from each independent sample to the next. 
$$\hat{p_1}\neq\hat{p_2}\neq\hat{p_3}\neq\dots$$

If each sample has a size $n$, then each sample has a sample proportion $\hat{p}=\frac{x}{n}$, where $x$ is the number of **successes** in the sample. 

- The difference between sample proportions (**sampling error**) is not really an error. It's just the *variability* you'd expect to see from one sample to another. A better term might be **sampling variability**.
- As sample size increases, sample proportion $\hat{p}$ gets closer to the population proportion $p$. 

```ad-warning
No matter how large the sample size, there is always some sampling variability present. So $\hat{p}$ will be different every time we sample. 
```

Sample proportions are distributed ($\hat{p}$ is a [[random variable]]), and are distributed around the population proportion. Depending on the sample size, their dispersion around the population proportion is different. The distribution of sample proportions can be modeled by a [[normal distribution]] if
1. all samples are independent
2. sample size is large enough

The sample proportions ($\hat{p}$), when modeled by the normal distribution will have the [[centre|mean]] and standard deviation as:

$$E(\hat{p})=\mu(\hat{p})=p$$
$$SD(\hat{p})=\sqrt\frac{p(1-p)}{n}$$

```ad-warning
In order to model the distribution of sample proportions using normal distribution, we need to make sure the following are satisfied:

1. **Independence assumption**: the sampled values must be independent of each other.
2. **Sample size assumption**: the sample size $n$ must be large enough (usually more than 30 is fine).
3. **Randomization condition**: if your data came from an experiment, subjects should have been randomly assigned to treatments.
4. **10% condition**: if sampling has not been made with replacement, then sample size $n$ must be no larger than 10% of the population.
5. **Success/failure condition**: the sample size must be big enough so that both the number of "successes", $np$, and the number of "failures", $nq$ are expected to be at least 10:
$$\begin{align*}
np&\geq 10\\
n(1-p)=nq&\geq 10
\end{align*}$$
```