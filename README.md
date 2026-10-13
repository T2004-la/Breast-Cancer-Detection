# Breast Cancer Detection: A Comparative Machine Learning Analysis

This repository contains a Machine Learning project focused on diagnosing breast cancer using the standard **Wisconsin Breast Cancer Dataset**[cite: 1]. The primary objective is to train, evaluate, and compare multiple classification algorithms to achieve the highest possible accuracy and recall for medical diagnosis[cite: 1].

## 📊 Dataset Overview
- **Samples:** 569
- **Features:** 30 numeric attributes
- **Classes:** Malignant and Benign

## 🛠️ Tech Stack & Workflow
The project is implemented in **Python** using the following libraries[cite: 1]:
- **Data Handling:** Pandas, NumPy[cite: 1]
- **Machine Learning:** Scikit-learn[cite: 1]
- **Data Preprocessing:** Standard Scaling[cite: 1]

### Workflow Steps[cite: 1]:
1. Data Loading & Exploratory Inspection[cite: 1]
2. Dataset Splitting (80% Train, 20% Test)[cite: 1]
3. Feature Scaling using `StandardScaler`[cite: 1]
4. Model Training & Hyperparameter Tuning[cite: 1]
5. Performance Evaluation (Accuracy, Precision, Recall, F1-Score)[cite: 1]

## 📈 Evaluated Models & Results

Four prominent classification algorithms were trained and evaluated on the test set (114 samples)[cite: 1]. The performance comparison is summarized below:

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| **Support Vector Classifier (SVC)** | **98.24%** | **97.26%** | **100.00%** | **98.61%** |
| **Logistic Regression** | 97.37% | 97.22% | 98.59% | 97.90% |
| **K-Nearest Neighbors (KNN)** | 94.74% | 95.77% | 95.77% | 95.77% |
| **Decision Tree** | 93.86% | 95.65% | 94.37% | 95.01% |

### 🔍 Key Takeaway
The **Support Vector Classifier (SVC)** outperformed all other models, achieving an **Accuracy of 98.24%**[cite: 1]. Most importantly, it achieved a **Recall of 100%**, meaning it successfully identified every single positive (malignant) case in the test set[cite: 1]. In medical diagnostics, minimizing False Negatives (high Recall) is of paramount importance to ensure no patient goes undiagnosed.
