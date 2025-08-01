---
{"dg-publish":true,"dg-permalink":"bias-vs-variance","permalink":"/bias-vs-variance/"}
---


202502012205
tags: #machine-learning #model-performance #diagnostics

Bias and variance represent two sources of error that affect model performance, creating a fundamental tradeoff in machine learning.

**High Bias (Underfitting):**

- Model is too simple to capture underlying patterns
- Poor performance on both training and test sets
- Training error is high
- Small gap between training and validation error

**High Variance (Overfitting):**

- Model is too complex, memorizes training noise
- Good training performance, poor test performance
- Low training error
- Large gap between training and validation error

**Solutions:**

- High bias → More complex model, [[Feature Engineering\|Feature Engineering]], [[Polynomial Regression\|Polynomial Regression]]
- High variance → More data, [[Regularization\|Regularization]], simpler model

[[Learning Curves\|Learning Curves]] help diagnose which problem you have. The goal is finding the sweet spot that minimizes total error.

This relates to [[Human Level Performance\|Human Level Performance]] as a baseline for achievable error rates.

---

# Reference

Machine Learning Yearning by Andrew Ng
