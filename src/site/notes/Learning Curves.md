---
{"dg-publish":true,"dg-permalink":"learning-curves","permalink":"/learning-curves/"}
---


202502012207
tags: #machine-learning #diagnostics #model-performance

Learning curves plot training and validation error as a function of training set size, helping diagnose [[Bias vs Variance\|Bias vs Variance]] problems.

**High Bias pattern:**

- Training and validation errors converge to a high value
- Both errors plateau early
- Adding more data won't help much
- Solution: More complex model, [[Feature Engineering\|Feature Engineering]]

**High Variance pattern:**

- Large gap between training and validation error
- Training error is low, validation error is high
- Gap may decrease with more data
- Solution: More data, [[Regularization\|Regularization]], simpler model

**Healthy model:**

- Training and validation errors converge to low value
- Small gap between the two curves
- Performance improves with more data

Learning curves help decide whether to collect more data or change the model architecture. They're more informative than single-point accuracy measurements.

Use learning curves alongside [[Human Level Performance\|Human Level Performance]] benchmarks to set realistic expectations.

---

# Reference

Machine Learning Yearning by Andrew Ng
