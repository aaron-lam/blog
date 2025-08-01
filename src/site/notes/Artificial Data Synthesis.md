---
{"dg-publish":true,"dg-permalink":"artificial-data-synthesis","permalink":"/artificial-data-synthesis/"}
---


202502012218
tags: #machine-learning #data-augmentation #data-quality

Artificial data synthesis creates new training examples from existing data to address [[Data Distribution Mismatch\|Data Distribution Mismatch]] or insufficient training data.

**Common techniques:**

**Image data:**

- Rotation, scaling, cropping
- Color adjustments, noise addition
- Horizontal/vertical flipping
- Generative models (GANs, VAEs)

**Text data:**

- Synonym replacement
- Back-translation (translate to another language and back)
- Paraphrasing with language models
- Adding noise to embeddings

**Audio data:**

- Speed/pitch modifications
- Background noise addition
- Echo, reverb effects

**Tabular data:**

- SMOTE (Synthetic Minority Oversampling)
- Gaussian noise addition
- Interpolation between examples

**Critical warning:** Artificial data can introduce subtle artifacts that don't exist in real data. The model may learn to recognize these artifacts instead of the true underlying patterns.

**Best practices:**

- Validate synthetic data quality manually
- Test on real data frequently
- Use domain expertise to guide synthesis
- Monitor for degraded real-world performance

Synthesis helps with [[Data Distribution Mismatch\|Data Distribution Mismatch]] but should supplement, not replace, collecting real target-distribution data.

---

# Reference

Machine Learning Yearning by Andrew Ng
