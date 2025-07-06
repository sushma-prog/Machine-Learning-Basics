# 🧠 Breast Cancer Classification: ML Model Tuning

This project builds and tunes a **Random Forest Classifier** to detect whether a breast tumor is **malignant** or **benign** using the **Breast Cancer dataset** from `sklearn.datasets`.

We followed a structured approach to model building, evaluation, validation, and tuning — ideal for beginners in ML looking to learn practical steps.

---

## 📊 Dataset
- 📁 Source: `sklearn.datasets.load_breast_cancer()`
- 🔢 Features: 30 numeric features describing tumor characteristics
- 🎯 Target: `Malignant` or `Benign`

---

## 🧪 What This Project Covers

### ✅ Part A: Train-Test Modeling
- Split dataset using `train_test_split()`
- Trained a `RandomForestClassifier`
- Calculated accuracy, precision, recall, and F1-score using `classification_report`

### ✅ Part B: Model Validation
- Applied **k-Fold Cross-Validation** using `cross_val_score()`
- Used **GridSearchCV** to tune hyperparameters
- Re-evaluated the best model with `classification_report()`

---

## 📈 Final Model Performance

| Class      | Precision | Recall | F1-Score |
|------------|-----------|--------|----------|
| Malignant  | 0.94      | 0.98   | 0.96     |
| Benign     | 0.99      | 0.96   | 0.98     |
| **Accuracy** |         |        | **0.97**  |

---

## 🧠 Techniques Used
- Random Forest Classifier
- Train-Test Split
- Classification Metrics
- k-Fold Cross-Validation
- GridSearchCV for hyperparameter tuning

---
