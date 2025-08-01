---
{"dg-publish":true,"dg-permalink":"polynomial-regression","permalink":"/polynomial-regression/"}
---


202502012217
tags: #machine-learning #regression #feature-engineering

Polynomial regression extends linear regression by adding polynomial terms (x², x³, etc.) as features to capture non-linear relationships.

**How it works:**
Transform features: x → [x, x², x³, ..., x^n]
Then apply standard linear regression on the expanded feature set.

**Example:**
Original: y = θ₀ + θ₁x
Polynomial: y = θ₀ + θ₁x + θ₂x² + θ₃x³

**Benefits:**

- Captures curved relationships with linear methods
- More flexible than purely linear models
- Can model complex patterns in data

**Challenges:**

- Higher degree polynomials can cause overfitting ([[Bias vs Variance\|Bias vs Variance]])
- Features grow exponentially with degree
- Requires careful [[Feature Scaling\|Feature Scaling]] since x³ >> x
- May need [[Regularization\|Regularization]] to control complexity

**Best practices:**

- Start with low degrees (2-3) and increase gradually
- Use [[Learning Curves\|Learning Curves]] to detect overfitting
- Apply feature scaling before training
- Consider cross-validation for degree selection

This is a form of [[Feature Engineering\|Feature Engineering]] that transforms the problem space to make linear algorithms work on non-linear data.

---

# Reference

Machine Learning Yearning by Andrew Ng
