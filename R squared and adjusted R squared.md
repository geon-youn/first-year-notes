---
alias: 
tags: COMMERCE_1DA3
created: Tuesday April 12, 2022; 14:35:08 
---
# R squared and adjusted R squared
Adding a new predictor variable to a model will either keep [[variations in the model and R squared|R squared]] at the same level, or increase it; it will never decrease $R^2$. Checking $R^2$ doesn't help determine if a variable should be added to the model or not.

Adjusted $R^2$ imposes a penalty on the correlation strength of larger models, depreciating their $R^2$ values to account for an undesired increase in complexity.

If a predictor variable is added to the model, adjusted $R^2$ can
- shrink if the predictor variable doesn't contribute to the model, and
- grow if the predictor variable contributes to the model.

Adjusted $R^2$ can even become negative.

> $$\text{Adjusted $R^2$}=1-(1-R^2)\times\frac{n-1}{n-k-1}=1-(1-R^2)\times\frac{df_{SSTotal}}{df_{SSE}}$$