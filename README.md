# lung-cancer-detection
Predicting lung cancer risk using clinical data and classification models
# 🩺 Lung Cancer Detection with Machine Learning

This project uses machine learning to predict the likelihood of lung cancer based on clinical and behavioral features. A strong classification task with real-world impact in early cancer detection.

---

## 📊 Dataset Overview
- **Source**: Kaggle – Lung Cancer Prediction Dataset
- **Features:**
  - `GENDER`, `AGE`, `SMOKING`, `YELLOW_FINGERS`, `ANXIETY`, `PEER_PRESSURE`, etc.
  - `LUNG_CANCER`: target label (Yes/No)

---

## 🔍 Exploratory Data Analysis (EDA)
- Countplots of categorical features (e.g. Smoking, Anxiety, Chronic Disease)
- Age distribution visualization
- Correlation heatmap of all features
- Categorical encoding (Yes/No → 1/0)

---

## 🧼 Preprocessing
- Converted categorical to numeric
- Checked for missing values
- Normalized features using **StandardScaler**
- Train-test split: 80/20

---

## 🧠 Models Trained
| Model                  | Description                         |
|------------------------|-------------------------------------|
| ✅ Logistic Regression | Baseline linear classifier          |
| ✅ Support Vector Machine (SVM) | Powerful for binary classification |
| ✅ K-Nearest Neighbors (KNN)    | Instance-based learner             |

---

## 📈 Evaluation Metrics
- **Accuracy**
- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-score)
- ROC-AUC (optional)

---

## ✅ Results Summary
| Model     | Accuracy |
|-----------|----------|
| Logistic Regression | ~87% |
| SVM                | ~86% |
| KNN (k=3)          | ~83% |

> Logistic Regression performed best with high precision and recall across both classes.

---

## 📌 Skills Demonstrated
- Binary classification
- Data preprocessing & encoding
- EDA with Seaborn and Matplotlib
- Evaluation using scikit-learn metrics
- Medical ML application (healthcare domain)

---

## 🔗 Links
- 📘 [Kaggle Notebook](https://www.kaggle.com/code/mahmoudehab6677/lung-cancer-detection)
