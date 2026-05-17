# Student Performance Decision Tree

This project implements a Machine Learning classification model using a Decision Tree Classifier to predict student academic performance based on various study and behavioral features.

---

## Problem Statement

The goal of this project is to classify student performance into categories such as good or poor performance using features like:

- Study Hours
- Attendance Rate
- Sleep Hours
- Academic Habits

The project focuses on understanding:
- Decision Tree logic
- Classification problems
- Data preprocessing
- Overfitting concepts
- Model interpretability

---

## Technologies Used

- Python
- NumPy
- scikit-learn

---

## Dataset Information

The dataset contains student-related academic and behavioral information.

### Features Used
- Age
- Study Hours Per Day
- Attendance Rate
- Sleep Hours

### Target Variable
Student performance score converted into:
- `1` → Good Performance
- `0` → Poor Performance

---

## Preprocessing Steps

- Loaded dataset using NumPy
- Selected numerical columns
- Removed invalid (`nan`) values
- Converted continuous scores into binary classes

---

## Model Used

### Decision Tree Classifier

A Decision Tree works using if-else based splitting logic.

Example:

```text
if attendance > 75:
    predict good performance
else:
    predict poor performance
