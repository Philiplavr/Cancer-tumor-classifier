# 🧠 Cancer Tumor Classifier

A simple machine learning project that classifies cancer tumors as benign or malignant using the Wisconsin Breast Cancer Dataset. Built as a university project by a 2nd-year Chemical Engineering student with a strong interest in data science and machine learning.

## 📌 Features

- Uses multiple classification algorithms (KNN, Naive Bayes, Logistic Regression)
- Evaluates models based on Accuracy, Precision, Recall, and F1-score
- Compares performance using different hyperparameters
- Displays confusion matrices and provides analysis
- Built with clean, reproducible Jupyter Notebook code

## 📊 Dataset

- **Name:** Breast Cancer Wisconsin (Diagnostic) Data Set  
- **Source:** UCI Machine Learning Repository  
- **Classes:** Malignant (1), Benign (0)

## 🧪 Models Used

- **K-Nearest Neighbors (KNN)** – with varying values of `k`
- **Naive Bayes** – tested with different `var_smoothing`
- **Logistic Regression** – with and without `L2` regularization

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`

## 📈 Results Summary

| Model                | Accuracy | F1-Score |
|---------------------|----------|----------|
| KNN (k=3)           | 0.93     | 0.93     |
| KNN (k=5)           | 0.91     | 0.91     |
| Naive Bayes         | 0.90     | 0.90     |
| Logistic Regression | 0.96     | 0.97    |


KNN (k=3) and Logistic Regression with L2 regularization provided the best performance.
