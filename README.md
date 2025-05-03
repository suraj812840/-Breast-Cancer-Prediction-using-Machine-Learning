# -Breast-Cancer-Prediction-using-Machine-Learning
This project uses machine learning techniques to predict whether a breast tumor is malignant or benign based on the Breast Cancer Wisconsin (Diagnostic) dataset. The dataset includes measurements of cell nuclei from breast mass images, such as radius, texture, smoothness, and symmetry.The goal is to build an accurate classification model.
# 🎗️ Breast Cancer Prediction using Machine Learning

## 🧬 Project Overview

This project focuses on the early detection of **breast cancer** using machine learning algorithms. By training models on the well-known **Breast Cancer Wisconsin (Diagnostic) dataset**, we aim to classify whether a tumor is **malignant** or **benign** based on various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

---

## 🎯 Objective

To build a robust machine learning model that can accurately classify tumors as **malignant** or **benign**, thereby aiding early diagnosis and improving treatment outcomes.

---

## 📂 Dataset Information

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Samples**: 569
- **Features**: 30 numeric features (e.g., radius, texture, smoothness)
- **Target**: Diagnosis (M = Malignant, B = Benign)

---

## 🧰 Tools & Technologies Used

- `Python`
- `Pandas`, `NumPy` for data manipulation
- `Matplotlib`, `Seaborn` for visualization
- `Scikit-learn` for ML models and evaluation
- `Jupyter Notebook` for development

---

## 🔍 Project Workflow

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
   - Heatmaps
   - Pairplots
   - Feature correlation
3. **Data Preprocessing**
   - Handling missing values
   - Label encoding
   - Feature scaling
4. **Model Building**
   - Logistic Regression
   - Random Forest
   - SVM
   - KNN
5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
6. **Prediction on New Data**

---

## 📊 Model Performance

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 96%      |
| Random Forest      | 97%      |
| SVM                | 96%      |
| KNN                | 95%      |

> 💡 Random Forest performed best with the highest accuracy.

---

## 🧠 Key Learnings

- Feature importance in medical data
- Binary classification techniques
- Model comparison and selection
- Data preprocessing pipelines

---

## ▶️ How to Run


   git clone https://github.com/yourusername/breast-cancer-ml.git
   cd breast-cancer-ml
