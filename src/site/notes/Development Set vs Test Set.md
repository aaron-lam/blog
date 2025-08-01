---
{"dg-publish":true,"dg-permalink":"dev-vs-test-set","permalink":"/dev-vs-test-set/"}
---


202502012206
tags: #machine-learning #data-splitting #evaluation

Development (validation) set is used for model selection and hyperparameter tuning, while test set provides final unbiased performance evaluation.

**Development Set:**

- Used to compare different models and algorithms
- Guides decisions about [[Feature Engineering\|Feature Engineering]] and [[Regularization\|Regularization]]
- Can be "looked at" multiple times during development
- Typically 20-25% of available data

**Test Set:**

- Used only once for final evaluation
- Provides unbiased estimate of real-world performance
- Should never influence model development decisions
- Typically 20-25% of available data

**Key principle:** Your test set should reflect the data distribution you expect in production. If dev and test sets come from different distributions, you may have [[Data Distribution Mismatch\|Data Distribution Mismatch]].

Using a [[Single Number Evaluation Metric\|Single Number Evaluation Metric]] on both sets helps make clear comparisons between models.

Never use test set performance to make model decisions - this leads to overfitting to the test set.

---

# Reference

Machine Learning Yearning by Andrew Ng
