---
{"dg-publish":true,"dg-permalink":"bayes-theorem","permalink":"/bayes-theorem/"}
---

202408281721
tags: #statistics #philosophy 

Bayes' theorem calculates the probability of an event based on prior knowledge of conditions related to the event. It's often expressed as:

P(A|B) = (P(B|A) * P(A)) / P(B)

Where:
P(A|B) is the probability of A given B is true
P(B|A) is the probability of B given A is true
P(A) is the probability of A
P(B) is the probability of B

## Example

Let's say we're testing for a rare disease:

- 1% of the population has the disease (P(D) = 0.01)
- The test is 95% accurate for positive cases (P(T+|D) = 0.95)
- The test has a 10% false positive rate (P(T+|not D) = 0.10)

If someone tests positive, what's the probability they have the disease?

We want to find P(D|T+):

P(T+)
= P(T+|D) * P(D) + P(T+|not D) * P(not D)
= 0.95 * 0.01 + 0.10 * 0.99
= 0.1085

P(D|T+)
= (P(T+|D) * P(D)) / P(T+)
= (0.95 * 0.01) / 0.1085 ≈ 0.0876 or about 8.76%

So despite a positive test, there's only about an 8.76% chance the person actually has the disease. This counterintuitive result demonstrates the importance of considering base rates (disease prevalence) in interpreting test results.

---
# Reference

Wireless Philosophy - Unit 1: Critical Thinking