# Week 5: AutoML & No-Code Model Training
Trained a custom image classifier with Google Teachable Machine and compared generic vs fine-tuned Hugging Face models for the Phishing & Threat Triage component of our Cybersecurity Email Threat Detection capstone project.

## Custom Model Training
- Built a Phishing/Legitimate image classifier with Teachable Machine
- Achieved 70.0% accuracy on 10 held-out test images
- Precision: 66.7% | Recall: 80.0% | F1: 72.7%

## Fine-Tuned Model Comparison
Compared 3 models (1 generic + 2 fine-tuned) on 5 test inputs:
- Generic: distilbert-sst-2 (sentiment)
- Fine-Tuned A: mrm8488/bert-tiny-finetuned-sms-spam-detection
- Fine-Tuned B: ealvaradob/bert-finetuned-phishing

## Finding
Recommended ealvaradob/bert-finetuned-phishing for the Phishing & Threat Triage component because it is specifically optimized for cybersecurity threats rather than generic spam. Fine-tuned models showed higher performance with more relevant labels and much better handling of domain-specific edge cases.

See `report.md` for full analysis.
