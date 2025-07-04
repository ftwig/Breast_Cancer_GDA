# Breast Cancer Classification using Gaussian Discriminant Analysis (GDA)

This project implements **Gaussian Discriminant Analysis (GDA)** from scratch to classify breast cancer tumors as malignant or benign using the [Breast Cancer Wisconsin (Diagnostic) dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

## Project Overview

- **Objective**: Predict whether a tumor is **malignant (M)** or **benign (B)** based on 30 features computed from a digitized image of a breast mass.
- **Approach**: This is a generative learning approach using **Gaussian Discriminant Analysis (GDA)**. We assume class-conditional distributions are Gaussian with a shared covariance matrix.
- **Evaluation**: Performance is measured using accuracy and confusion matrix.

---

## Dataset

- **Source**: [Kaggle - UCI Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Features**: 30 numeric attributes such as radius, texture, perimeter, area, etc.
- **Target**: `Diagnosis` - M (malignant), B (benign)

---

## Key Concepts

- Gaussian Discriminant Analysis (GDA)
- Maximum Likelihood Estimation (MLE)
- Class priors (φ), class means (μ₀, μ₁), and shared covariance matrix (Σ)
- Multivariate Gaussian likelihood function
- Soft classification with hard prediction (argmax)
- Accuracy and confusion matrix as metrics

---

## Results

- **Training Accuracy**: ~96%
- Visualization includes:
  - Feature scatter plots by class
  - Confusion matrix

---
### 📌 Scatter Plot (Feature Distribution)

![Scatter Plot](Scatter_plot.png)
### 📍 1. Distribution of mean radius by Diagnosis  
![Mean Radius vs count](Radius_mean_by_Diagnosis.png))

### 📍 2. Distribution of mean texture by Diagnosis  
![Mean Texture vs count](perimeter_mean_by_diagnosis.png)

### 📍 3. Distribution of mean perimeter by Diagnosis
![Mean Perimeter vs count](texture_mean_by_diagnosis.png)

## Dependencies

Make sure the following Python libraries are installed:

```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
