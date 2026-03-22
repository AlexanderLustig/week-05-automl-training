# Week 5 Report: AutoML Training & Fine-Tuned Model Evaluation
**Name:** Alexander Lustig
**Date:** March 22, 2026
**Capstone Project:** Cybersecurity Email Threat Detection
**My Component:** Phishing Image & Text Classification

## Part A: Teachable Machine Training
### Training Setup
- **Task:** Phishing vs Legitimate email screenshot classification
- **Training images per class:** 25
- **Test images per class:** 5
- **Total training time:** ~25 seconds

### Confusion Matrix
| | Predicted: Phishing | Predicted: Legitimate |
|---|---|---|
| **Actual: Phishing** | TP = 4 | FN = 1 |
| **Actual: Legitimate** | FP = 2 | TN = 3 |

### Calculated Metrics
- **Accuracy:** 70.0%
- **Precision:** 66.7%
- **Recall:** 80.0%
- **F1 Score:** 72.7%

### Interpretation
My model is better at recall (80%) than precision (66.7%). This means it is fairly good at catching actual phishing emails, but it does so by being overly sensitive—it incorrectly flagged two perfectly normal emails as phishing (False Positives).
