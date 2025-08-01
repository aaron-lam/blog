---
{"dg-publish":true,"dg-permalink":"vectorization","permalink":"/vectorization/"}
---


202502012215
tags: #machine-learning #optimization #computation

Vectorization replaces explicit loops with matrix operations, dramatically speeding up machine learning computations by leveraging optimized linear algebra libraries.

**Why vectorization matters:**

- 10-100x faster than explicit loops
- Takes advantage of parallel processing (CPU/GPU)
- More concise and readable code
- Reduces bugs from manual indexing

**Example comparison:**

```python
# Non-vectorized (slow)
z = 0
for i in range(n):
    z += w[i] * x[i]

# Vectorized (fast)
z = np.dot(w, x)
```

**In machine learning:**

- [[Gradient Descent\|Gradient Descent]] updates: θ := θ - α∇J(θ)
- Forward propagation in neural networks
- Computing predictions for entire datasets at once

**Key libraries:**

- NumPy (Python), built on BLAS/LAPACK
- TensorFlow/PyTorch for deep learning
- MATLAB's built-in matrix operations

Vectorization is essential for implementing [[Gradient Descent\|Gradient Descent]] efficiently with multiple variables and large datasets.

---

# Reference

Machine Learning Yearning by Andrew Ng
