# ❤️ Heart Disease Prediction using Machine Learning

## 🔬 End-to-End ML Pipeline with Explainability (SHAP)

---

## 📌 Overview

This project builds a machine learning model to predict the presence of heart disease using clinical features.

The pipeline includes:
- Data preprocessing
- Handling missing values
- Feature selection
- Model training & evaluation
- Explainability using SHAP

---

## 📥 Dataset

The dataset is included in the repository under the `data/` folder.

To load:

```python
df = pd.read_csv("data/heart_disease.csv")
```
---

## 🚀 Key Highlights

- Removed data leakage (`id`) and dataset bias (`dataset`)
- Compared multiple models:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Achieved **~86% accuracy** with XGBoost
- Applied **SHAP** for model interpretability

---

## 📊 Results

| Model | Accuracy | ROC-AUC |
|------|--------|--------|
| Logistic Regression | ~78% | ~0.79 |
| Random Forest | ~84% | ~0.84 |
| XGBoost | **~86%** | **~0.86** |

---

## 🌳 Feature Importance

Top predictors:
- Chest pain type (`cp`)
- Exercise-induced angina (`exang`)
- Number of vessels (`ca`)
- Thalassemia (`thal`)
- ECG-related features

---

## 🔍 Model Explainability

SHAP was used to interpret model predictions and understand feature impact.

---

## 📂 Project Structure

├── heart_disease_prediction.ipynb
├── data/
├── images/
└── README.md


---

## ⚠️ Key Learnings

- Importance of removing data leakage
- Handling dataset bias
- Model interpretability using SHAP
- Trade-off between accuracy and generalization

---

## 🚀 Future Work

- Hyperparameter tuning
- Larger datasets
- Deployment as a web app

---

## 👤 Author

**Muhammad Ali Waris Khan** 
