---
{"dg-publish":true,"dg-permalink":"human-level-performance","permalink":"/human-level-performance/"}
---


202502012209
tags: #machine-learning #benchmarking #performance

Human level performance provides a benchmark for machine learning systems, helping determine achievable error rates and guide optimization efforts.

**Why it matters:**

- Establishes theoretical lower bound (Bayes error)
- Helps distinguish between bias and variance problems
- Guides where to focus improvement efforts
- Provides business context for model performance

**When human performance is useful:**

- Tasks humans excel at (image recognition, natural language)
- Domains where human expertise is well-established
- Problems where human-level accuracy is the business requirement

**Limitation:** For some tasks, machines can surpass human performance (structured data analysis, chess), so human benchmarks become less relevant.

**Practical application:**
If your model performs much worse than humans, focus on reducing bias through better algorithms or [[Feature Engineering\|Feature Engineering]]. If close to human level, collect more data or improve [[Error Analysis\|Error Analysis]] process.

This connects to [[Bias vs Variance\|Bias vs Variance]] diagnosis - human performance helps identify the achievable baseline.

---

# Reference

Machine Learning Yearning by Andrew Ng
