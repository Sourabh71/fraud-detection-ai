
# 💳 AI-Based Financial Fraud Detection

This project builds a machine learning model to detect fraudulent credit card transactions using a highly imbalanced dataset.  
It combines a `RandomForestClassifier` with `SMOTE` (Synthetic Minority Over-sampling Technique) to improve fraud detection accuracy.

---

## 📂 Project Structure

```
fraud-detection-ai/
├── fraud_detection_ai_cleaned.ipynb     # Main Colab notebook (cleaned)
├── smote_fraud_model.pkl                # Final trained model
├── README.md                            # This documentation file
├── .gitignore                           # Git ignore rules for clean repo
```

---

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains 284,807 transactions
- Highly imbalanced: Only 492 fraudulent transactions

---

## 🧠 Model Overview

- **Algorithm:** Random Forest Classifier
- **Technique:** SMOTE used to oversample fraud cases
- **Evaluation Metrics:** Confusion Matrix, Precision, Recall, F1-score

### 🚀 Results:

| Metric    | Score  |
|-----------|--------|
| Accuracy  | 99.9%  |
| Precision (fraud) | 87% |
| Recall (fraud)    | 83% |
| F1 Score (fraud)  | 85% |

---

## 🛠️ Tech Stack

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn
- joblib

---

## 🧪 How to Run

1. Clone this repo or upload files to [Google Colab](https://colab.research.google.com)
2. Upload `creditcard.csv` manually to your session
3. Run `fraud_detection_ai_cleaned.ipynb`
4. Use or deploy the trained model saved as `smote_fraud_model.pkl`

---

## 👤 Author

**Saurabh Yadav**  
BBA Student | Aspiring Financial Analyst  
🏛️ Target Internships: Goldman Sachs, World Bank  
🌱 Passionate about AI in finance and fraud prevention

---
