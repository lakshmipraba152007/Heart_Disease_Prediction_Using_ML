# ❤️ Heart Disease Prediction Using ML

A machine learning project that predicts the presence or absence of heart disease using logistic regression. This beginner-friendly implementation achieves **92.59% accuracy** on the test dataset.

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit%20Learn-1.0+-green.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-92.59%25-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Model Performance](#model-performance)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Input Features](#input-features)
- [How to Predict New Patients](#how-to-predict-new-patients)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🎯 About the Project

Heart disease is one of the most common causes of death globally. Early detection can significantly improve patient outcomes. This project uses a **Logistic Regression** model to classify whether a patient has heart disease based on various medical attributes.

This is a **beginner-friendly version** designed for those learning machine learning and medical data science. The code is simple, well-documented, and easy to understand.

**Why This Project?**
- 📚 Perfect for learning ML basics
- 🏥 Real-world medical application
- 🎓 Great for portfolio/interviews
- ⚡ Fast and efficient prediction

## 📊 Dataset

This project uses the [Heart Disease Dataset](https://www.kaggle.com/datasets/andrewmvd/heart-disease-disease) from Kaggle (UVa Machine Learning Repository).

**Dataset Statistics:**
- Total samples: 270 patients
- Classes: 2 (Absence = 0, Presence = 1)
- Features: 14 medical attributes
- Split: 80% training (216 samples), 20% testing (54 samples)

## 📈 Model Performance

### Accuracy Results

| Metric | Absence (0) | Presence (1) |
|--------|-------------|--------------|
| Precision | 0.91 | 0.95 |
| Recall | 0.97 | 0.86 |
| F1-Score | 0.94 | 0.90 |
| Support | 33 | 21 |

**Overall Metrics:**
- Accuracy: 93%
- Macro Avg F1-Score: 0.92
- Weighted Avg F1-Score: 0.93
