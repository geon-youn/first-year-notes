---
alias: regression line, residual, ordinary least squares, OLS, error sum of squares, SSE, least squares line, line of best fit, slope, intercept, $b_0$, $b_1$, regression model
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 15:01:56 
---
# Linear model
**Linear model (regression line)**: the line that best fits all the points.

The line is used to predict values of the [[assigning roles to variables in scatterplots|dependent]] variable for values of the independent variable. 

```ad-note
The value predicted by the line is usually not equal to the value of the data. There are some **errors** (**residuals**).

Even though we know the line isn't the "prefect" prediction, we can still work with the linear model and accept some levels of error.

Unless the points form a perfect line, we will always have some errors. 
```

A linear model can be written in the form
$$\hat{y}=b_0+b_1x$$
where $b_0$ is the $y$-intercept and $b_1$ is the slope. 

**Residual ($e$)**: the difference between the predicted values of the dependent variable ($\hat{y}$) and the actual value for the dependent variable ($y$) if there is a point. 
$$e=y-\hat{y} \Rightarrow y = \hat{y}+e$$

The standard deviation of the residuals is given as
$$s_e=\sqrt\frac{\sum e^2}{n-2}$$

Method of **ordinary least squares (OLS)**: choose the line whereby the **error sum of squares (SSE)** (the sum of the squared residuals) is minimized (minimize $\sum e^2$).

**Least squares line (line of best fit; regression line)**: the line for which SSE is the smallest.

We square the residuals so that + and - residuals don't cancel each other out and large residuals have more emphasis. 

We can find the **slope ($b_1$)** by
$$b_1=r\frac{s_y}{s_x}$$

The slope gets its
- sign from the correlation. 
- units from the ratio of the two [[spread|standard deviation]]s.

To find the **intercept ($b_0$)**, we use the means. If our line estimates the data, then it should predict $\overline{y}$ for the x-value $\overline{x}$. 
$$\overline{y}=b_0+b_1\overline{x}\Leftrightarrow b_o=\overline{y}-b_1\overline{x}$$

We'll need to check the same conditions for regression as we did for [[understanding correlation|correlation]]:
- quantitative variables condition
- linearity condition
- outlier condition