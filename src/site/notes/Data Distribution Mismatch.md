---
{"dg-publish":true,"dg-permalink":"data-distribution-mismatch","permalink":"/data-distribution-mismatch/"}
---


202502012211
tags: #machine-learning #data-quality #distribution

Data distribution mismatch occurs when training data comes from a different distribution than the data you'll encounter in production.

**Common scenarios:**

- Training on high-quality studio photos, deploying on mobile phone photos
- Training on formal text, deploying on social media text
- Training on historical data, deploying in changing market conditions

**Diagnosis using Training-Dev set:**

1. Create training-dev set from same distribution as training data
2. Compare performance: training vs training-dev vs dev vs test
3. If training-dev error >> training error: variance problem
4. If dev error >> training-dev error: data mismatch problem

**Solutions:**

- Collect more data from target distribution
- [[Artificial Data Synthesis\|Artificial Data Synthesis]] (but beware of introducing artifacts)
- Domain adaptation techniques
- Feature engineering to make model more robust

**Important:** Always ensure [[Development Set vs Test Set\|dev and test sets]] come from the same distribution as your target application.

Data mismatch is often more impactful than algorithmic improvements.

---

# Reference

Machine Learning Yearning by Andrew Ng
