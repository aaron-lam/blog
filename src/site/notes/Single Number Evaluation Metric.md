---
{"dg-publish":true,"dg-permalink":"single-number-evaluation-metric","permalink":"/single-number-evaluation-metric/"}
---


202502012214
tags: #machine-learning #evaluation #metrics

A single number evaluation metric provides one clear number to compare different models, making it easier to choose the best performing algorithm.

**Why single numbers matter:**

- Enables quick comparison between models
- Helps teams make objective decisions
- Simplifies communication with stakeholders
- Speeds up iteration cycles

**Common single number metrics:**

**Classification:**

- Accuracy: correct predictions / total predictions
- F1-score: harmonic mean of precision and recall
- AUC-ROC: area under receiver operating curve

**Regression:**

- MSE: mean squared error
- MAE: mean absolute error
- R²: coefficient of determination

**When single metrics aren't enough:**
Sometimes you need satisficing + optimizing metrics:

- Accuracy > 95% (satisficing) AND minimize latency (optimizing)
- Precision > 80% (satisficing) AND maximize recall (optimizing)

Choose metrics that align with business objectives. Use the same metric consistently across [[Development Set vs Test Set\|dev and test sets]] to ensure fair comparisons.

---

# Reference

Machine Learning Yearning by Andrew Ng
