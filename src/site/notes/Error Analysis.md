---
{"dg-publish":true,"dg-permalink":"error-analysis","permalink":"/error-analysis/"}
---


202502012210
tags: #machine-learning #debugging #model-improvement

Error analysis involves systematically examining misclassified examples to identify patterns and guide improvement efforts.

**The process:**

1. Collect a set of examples your algorithm misclassified
2. Look at these examples manually (eyeball test)
3. Count how many errors fall into different categories
4. Focus improvement efforts on the most frequent error types

**Example categories for image classification:**

- Blurry images: 8% of errors
- Low lighting: 15% of errors
- Mislabeled data: 6% of errors
- Animal photos (in non-animal dataset): 43% of errors

**Key insights:**

- Focus on categories that represent largest error percentages
- Don't spend time on rare error types
- Some errors may fall into multiple categories

**Mislabeled data consideration:**
If training data has incorrect labels, only fix them if they significantly impact performance and you can fix them systematically.

Error analysis guides [[Feature Engineering\|Feature Engineering]] decisions and helps prioritize which aspects of the model to improve next.

---

# Reference

Machine Learning Yearning by Andrew Ng
