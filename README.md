# FinetunedBERTforHateSpeechDetection 
---
Hate Speech Detection Using Fine-Tuned BERT Models

This project focuses on hate speech detection by fine-tuning individual BERT models on the **Dhate dataset** for three key tasks:

1. **Binary Classification**:
   - Column: `label`
   - Classes: `hate` / `nothate`
   - Achieved **macro F1-score**: **0.7640**

2. **Multi-Class Classification**:
   - Column: `target` (e.g., `asian`, `black`, etc.)
     - Achieved **macro F1-score**: **0.135**
   - Column: `type` (e.g., `derogatory`, `animosity`, etc.)
     - Achieved **macro F1-score**: **0.475**

### Dataset
The **Dhate dataset** was used for training and evaluation, providing diverse annotations for hate speech in terms of label, target, and type.

### Models and Methods
- Pretrained BERT models were fine-tuned individually for each task.
- Results show competitive performance compared to baseline models, with significant improvements in binary classification.

### Key Results
- Our BERT model outperformed **RoBERTa (Dhate paper)** for binary classification, achieving an F1-score of **0.7640** compared to **0.7538**.
