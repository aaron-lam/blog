---
{"dg-publish":true,"dg-permalink":"cost-function","permalink":"/cost-function/"}
---


202502012202
tags: #machine-learning #optimization

A cost function measures how well a machine learning model's predictions match the actual target values. It quantifies the "cost" of making wrong predictions.

**Common Cost Functions:**

- **Mean Squared Error (MSE)**: Used for [[Regression vs Classification\|regression]], penalizes large errors more heavily
- **Cross-entropy**: Used for classification, measures probability distribution difference
- **Mean Absolute Error (MAE)**: Less sensitive to outliers than MSE

The goal of training is to minimize the cost function using techniques like [[Gradient Descent\|Gradient Descent]]. The choice of cost function affects how the model learns and what types of errors it prioritizes.

A well-designed cost function should:

- Reflect the true business objective
- Be differentiable for optimization
- Have a clear global minimum

---

# Reference

Machine Learning Yearning by Andrew Ng
