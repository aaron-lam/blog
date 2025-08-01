---
{"dg-publish":true,"dg-permalink":"gradient-descent","permalink":"/gradient-descent/"}
---


202502012203
tags: #machine-learning #optimization #algorithms

Gradient descent is an iterative optimization algorithm that finds the minimum of a [[Cost Function\|Cost Function]] by taking steps proportional to the negative gradient.

**How it works:**

1. Start with random parameters
2. Calculate the gradient (slope) of the cost function
3. Move in the opposite direction of the gradient
4. Repeat until convergence

**Key variants:**

- **Batch Gradient Descent**: Uses entire dataset for each update
- **Stochastic Gradient Descent (SGD)**: Uses one example at a time
- **Mini-batch**: Uses small batches, balancing efficiency and stability

The learning rate α controls step size. Too large causes overshooting, too small causes slow convergence.

For multiple variables, [[Vectorization\|Vectorization]] makes computation efficient. [[Feature Scaling\|Feature Scaling]] often helps gradient descent converge faster by normalizing input ranges.

---

# Reference

Machine Learning Yearning by Andrew Ng
