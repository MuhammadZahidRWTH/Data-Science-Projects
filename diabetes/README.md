# Diabetes Classification using Supervised Learning

This project focuses on using **supervised learning** techniques to classify diabetes data. The goal is to build multiple classifiers, evaluate their performance, and analyze the results. The dataset used is from a diabetes classification task, and various classifiers are trained and evaluated, including Random Forest, Gradient Boosting, AdaBoost, Logistic Regression, and Support Vector Classifier (SVC).

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation Instructions](#installation-instructions)
3. [Usage](#usage)
4. [Classifiers](#classifiers)
5. [Evaluation Metrics](#evaluation-metrics)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview

This project uses the **Diabetes Dataset**, where the goal is to predict whether a patient has diabetes based on various health metrics (e.g., glucose levels, BMI, age, etc.). The project includes the following:

- **Supervised Learning Models**: RandomForest, GradientBoosting, AdaBoost, LogisticRegression, and Support Vector Classifier (SVC).
- **Data Preprocessing**: Polynomial feature engineering, SMOTE for imbalanced data, and standard scaling.
- **Evaluation**: Performance is measured using classification reports, ROC AUC scores, and confusion matrices.
- **Output**: Results for each classifier are saved in Word documents, and an overall summary is created.

## Installation Instructions

To run this project, you will need to install the following dependencies. You can install them using `pip`:

```bash
pip install numpy pandas scikit-learn imbalanced-learn matplotlib python-docx
