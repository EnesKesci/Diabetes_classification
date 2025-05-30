# 🩺 Pima Indians Diabetes Prediction with Logistic Regression & Random Forest

This project aims to predict whether individuals have diabetes using the [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). Both basic models and hyperparameter adjustments were made during the project process.

---

## 📌 Project Goal

Using machine learning classification algorithms (especially Logistic Regression and Random Forest):
- Evaluate model performance
- Accurately predict individuals with diabetes (especially recall-oriented)
- Automatically find the best model settings with GridSearchCV

---
## 📊 Used Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---
## 🧠 Methods Used

- Missing data analysis and filling (`fillna`)
- Outlier detection and cleaning (IQR method)
- Feature engineering (log transformations, standardization)
- Train/Test split (`train_test_split`)
- Logistic Regression (with class_weight balance)
- Random Forest (optimization with GridSearchCV)
- Model evaluation (accuracy, precision, recall, f1-score, confusion matrix.

---

## 🌲 Best Model Results (Random Forest + GridSearchCV)

| Metric | Value |
|--|-------|
| Accuracy | 0.74 |
| Recall (1) | 0.84 ✅ |
| F1-score (1) | 0.68 |

---

## 📁 Files

- `diabetes_classification.ipynb`: Notebook file of the cleaned and optimized model
- `README.md`: Project description
- `diabetes.csv`: Dataset

---

## 📌 Data Source

Kaggle: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## 📣 Note

This project is a classification application made in the learning process and should not be used for professional diagnostic purposes in the health field.

---
