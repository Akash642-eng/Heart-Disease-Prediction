# Heart Disease Prediction using Machine Learning

A machine learning project that predicts whether a person has heart disease based on medical attributes such as age, cholesterol level, blood pressure, and heart rate.

---

# 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors take preventive measures.  
This project uses **machine learning classification algorithms** to predict whether a patient has heart disease.

---

# 🎯 Objectives

- Analyze heart disease data
- Train a machine learning model
- Predict whether a person has heart disease or not
- Evaluate model performance

---

# 🧠 Machine Learning Approach

- **Problem Type**: Binary Classification  
- **Target Variable**:
  - `1` → Defective Heart
  - `0` → Healthy Heart

---

# 📊 Dataset Information

The dataset contains medical attributes such as:

- Age
- Sex
- Chest pain type (4 values)
- Resting blood pressure
- Serum cholesterol in mg/dl
- Fasting blood sugar > 120 mg/dl
- Resting electrocardiographic results (values 0,1,2)
- Maximum heart rate achieved
- Exercise induced angina
- Oldpeak = ST depression induced by exercise relative to rest
- The slope of the peak exercise ST segment
- Number of major vessels (0-3) colored by flourosopy
- Thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

---

# 🛠 Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

# ⚙️ Model Used

- Logistic Regression

---

# 🧪 Model Workflow

1. Importing dependencies
2. Data collection & preprocessing
3. Feature selection
4. Train-test split
5. Model training
6. Model evaluation
7. Prediction

---

# 📈 Model Accuracy

- **Training Accuracy**: ~85%
- **Testing Accuracy**: ~80%

> Accuracy may vary based on dataset split.

---
# 📊 Visual Analysis

## Dataset Preview
[Dataset Preview](images/dataset_preview.png)

## Heart Disease Distribution
[Target Distribution](images/target_distribution.png)

## Feature Correlation Heatmap
[Correlation Heatmap](images/correlation_heatmap.png)

## Age vs Cholesterol
[Age vs Cholesterol](images/age_vs_cholesterol.png)

## Model Accuracy
[Model Accuracy](images/model_accuracy.png)




---

# 🚀 How to Run the Project

## Step 1: Clone the repository
```bash
git clone https://github.com/Akash642-eng/Heart-Disease-Prediction.git
