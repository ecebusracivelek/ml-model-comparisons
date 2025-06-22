# Machine Learning: Classification and Regression

This repository contains two supervised machine learning projects:

1. **Image Classification using CNNs on the CIFAR-10 dataset**
2. **Housing Price Prediction using various regression models on the California Housing dataset**

---

## 📁 Contents

- `cifar10_classification.ipynb` — Convolutional Neural Network implementation for CIFAR-10 classification.
- `californiahousing_regression.ipynb` — Regression model comparison using Scikit-learn (Linear, Ridge, Lasso, SVM, MLP, Decision Tree).
- `README.md` — Project overview and instructions.

---

## 🧠 Project 1: CIFAR-10 Image Classification

### ✅ Techniques Used

- Convolutional Neural Networks (CNN)
- Batch Normalization
- L2 Regularization
- Dropout
- Data Augmentation with `ImageDataGenerator`

### 📈 Evaluation

Two models are compared:

- **Baseline CNN**
- **Enhanced CNN** (with regularization and augmentation)

Training and validation accuracy/loss are visualized to highlight improvements.

---

## 📊 Project 2: California Housing Price Prediction

### ✅ Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Support Vector Regression (SVR)
- Multi-Layer Perceptron (MLP)
- Decision Tree Regressor

### 📉 Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score
- Coefficient comparison for linear models
- Visual regression line plots

### 📈 Additional Visuals

- Decision Tree structure
- Coefficient impact plots
- Model performance comparisons (bar charts)

---

## 💾 Dataset Sources

- **CIFAR-10**: Provided via `tensorflow.keras.datasets`
- **California Housing**: Provided via `sklearn.datasets.fetch_california_housing()`

---

## ▶️ How to Run

Install required packages (if not already installed):

```bash
pip install tensorflow scikit-learn matplotlib pandas numpy
