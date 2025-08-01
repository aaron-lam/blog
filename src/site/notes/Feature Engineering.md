---
{"dg-publish":true,"dg-permalink":"feature-engineering","permalink":"/feature-engineering/"}
---


202502012213
tags: #machine-learning #features #preprocessing

Feature engineering involves creating new input features from existing data to improve model performance, especially important when dealing with [[Bias vs Variance\|high bias]].

**Common techniques:**

**Mathematical transformations:**

- Polynomial features: x, x², x³ for [[Polynomial Regression\|Polynomial Regression]]
- Logarithmic: log(x) for skewed distributions
- Square root, reciprocal for different relationships

**Domain-specific features:**

- Date/time: day of week, month, hour from timestamps
- Text: word counts, n-grams, sentiment scores
- Images: edges, textures, geometric shapes

**Interaction features:**

- Combining multiple features: size × location
- Ratios: income/expenses, price/square_foot

**Aggregation features:**

- Moving averages, sums over time windows
- Statistical measures: mean, std, percentiles

Good feature engineering often requires domain expertise and insights from [[Error Analysis\|Error Analysis]]. Always apply [[Feature Scaling\|Feature Scaling]] to engineered features.

The goal is creating features that make the underlying patterns more apparent to your learning algorithm.

---

# Reference

Machine Learning Yearning by Andrew Ng
