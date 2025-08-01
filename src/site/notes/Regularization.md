---
{"dg-publish":true,"dg-permalink":"regularization","permalink":"/regularization/"}
---


202502012208
tags: #machine-learning #overfitting #optimization

Regularization adds a penalty term to the [[Cost Function\|Cost Function]] to prevent overfitting by constraining model complexity.

**Common regularization techniques:**

**L1 Regularization (Lasso):**

- Adds sum of absolute values of parameters
- Promotes sparsity (drives some weights to zero)
- Useful for [[Feature Engineering\|feature selection]]

**L2 Regularization (Ridge):**

- Adds sum of squared parameters
- Shrinks weights towards zero but doesn't eliminate them
- More common and stable than L1

**Dropout:**

- Randomly sets some neurons to zero during training
- Prevents co-adaptation of features
- Specific to neural networks

Regularization strength is controlled by hyperparameter λ (lambda). Higher λ means more regularization but may increase bias. Use [[Development Set vs Test Set\|validation set]] to tune λ.

Regularization is most effective when combined with [[Feature Scaling\|Feature Scaling]] to ensure penalties are applied fairly across features.

---

# Reference

Machine Learning Yearning by Andrew Ng
