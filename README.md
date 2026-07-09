# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

This project builds and compares multiple Machine Learning classification models to predict whether a patient has heart disease based on their clinical and demographic information.

The project includes data preprocessing, exploratory data analysis (EDA), feature encoding, model training, evaluation, and performance comparison.

---

## 📂 Dataset Information

- **Dataset Size:** 918 records
- **Features:** 11 input features
- **Target Variable:** `HeartDisease`

### Dataset Shape

- Rows: **918**
- Columns: **12**

### Features

| Feature | Description | Data Type |
|----------|-------------|-----------|
| Age | Age of the patient | Integer |
| Sex | Gender (M/F) | Categorical |
| ChestPainType | Type of chest pain | Categorical |
| RestingBP | Resting blood pressure | Integer |
| Cholesterol | Serum cholesterol (mg/dl) | Integer |
| FastingBS | Fasting blood sugar (>120 mg/dl) | Integer |
| RestingECG | Resting electrocardiogram results | Categorical |
| MaxHR | Maximum heart rate achieved | Integer |
| ExerciseAngina | Exercise-induced angina | Categorical |
| Oldpeak | ST depression induced by exercise | Float |
| ST_Slope | Slope of the peak exercise ST segment | Categorical |
| HeartDisease | Target variable (0 = No Disease, 1 = Heart Disease) | Integer |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Machine Learning Models

The following classification algorithms were implemented and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (RBF Kernel)

---

## 📈 Model Performance

| Model | Accuracy | F1 Score |
|--------|---------:|---------:|
| K-Nearest Neighbors (KNN) | **88.59%** | **0.8986** |
| Logistic Regression | 87.50% | 0.8878 |
| Naive Bayes | 86.96% | 0.8788 |
| SVM (RBF Kernel) | 86.41% | 0.8804 |
| Decision Tree | 75.54% | 0.7644 |

---

## 🏆 Best Performing Model

Based on both **Accuracy** and **F1 Score**, the **K-Nearest Neighbors (KNN)** model achieved the best overall performance.

- **Accuracy:** **88.59%**
- **F1 Score:** **0.8986**

---
# ⚙️ Workflow

1. Load the dataset
2. Explore and understand the data
3. Handle categorical variables
4. Perform Exploratory Data Analysis (EDA)
5. Split the dataset into training and testing sets
6. Train multiple machine learning models
7. Evaluate models using Accuracy and F1 Score
8. Compare model performance
9. Select the best-performing model

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- F1 Score

These metrics help assess overall classification performance and the balance between precision and recall.

---

