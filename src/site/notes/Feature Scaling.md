---
{"dg-publish":true,"dg-permalink":"feature-scaling","permalink":"/feature-scaling/"}
---


202502012204
tags: #machine-learning #preprocessing #features

Feature scaling normalizes input features to similar ranges, preventing features with larger scales from dominating the learning process.

**Why it matters:**

- Features like house size (1000-5000 sq ft) vs. bedrooms (1-5) have vastly different scales
- [[Gradient Descent\|Gradient Descent]] converges faster with scaled features
- Distance-based algorithms (k-NN, clustering) work better with normalized data

**Common scaling methods:**

- **Normalization (Min-Max)**: Scales to [0,1] range
- **Standardization (Z-score)**: Mean=0, standard deviation=1
- **Robust scaling**: Uses median and interquartile range

Apply the same scaling parameters from training data to test data to avoid [[Data Distribution Mismatch\|Data Distribution Mismatch]].

Feature scaling is particularly important for algorithms using [[Regularization\|Regularization]] since it ensures penalties are applied fairly across all features.

---

# Reference

Machine Learning Yearning by Andrew Ng
