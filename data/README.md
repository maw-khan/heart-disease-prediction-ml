# 📊 Dataset Description

This dataset contains clinical and demographic information used to predict the presence of heart disease.

## Features include:
- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Cholesterol (chol)
- Fasting blood sugar (fbs)
- Maximum heart rate (thalch)
- Exercise-induced angina (exang)
- ST depression (oldpeak)
- Number of vessels (ca)
- Thalassemia (thal)

## Target:
- `num` → Heart disease severity (converted to binary in this project)

## Note:
- Missing values were handled using median/mode imputation
- Non-informative features (`id`, `dataset`) were removed
