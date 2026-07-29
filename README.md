# WAEC Pass Likelihood Prediction Using Machine Learning

### 3MTT Data Science Capstone Project

**Author:** Ibrahim Shehu Ahmad

**Fellow ID:** FE/25/7761417422

![Python](https://img.shields.io/badge/Python-3.x-blue)

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)

![3MTT](https://img.shields.io/badge/3MTT-Data%20Science-green)

# WAEC Pass Likelihood Prediction Using Machine Learning

## Overview

This project was completed as part of the **3 Million Technical Talent (3MTT) Data Science Capstone Project**.

The aim of this project is to develop a machine learning model capable of predicting whether a student is likely to pass or fail an examination.

Due to the unavailability of official WAEC examination data, a publicly available Student Mathematics Performance dataset was used as a case study to demonstrate the complete machine learning workflow.

---

## Project Objectives

- Perform data preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Build machine learning classification models.
- Compare model performance.
- Identify the best-performing model.

---

## Dataset

- Source: Student Performance Mathematics Dataset (UCI Machine Learning Repository)
- Records: 395 students
- Features: 33 variables

The target variable **Pass** was created from the final Mathematics grade (G3):

- Pass = 1 (G3 ≥ 10)
- Fail = 0 (G3 < 10)

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

---

## Machine Learning Models

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree
- Random Forest

---

## Results

| Model | Accuracy |
|---------|----------|
| Logistic Regression | **94.94%** |
| Random Forest | **91.14%** |
| Decision Tree | **88.61%** |

Logistic Regression achieved the highest prediction accuracy and was selected as the final model.

---

## Repository Structure

```text
data/
images/
notebooks/
report/
README.md
requirements.txt
```

---

## Future Improvements

- Use official WAEC datasets when available.
- Develop a web application for predictions.
- Evaluate additional machine learning algorithms.
- Expand the model to cover multiple subjects.

---

## Author

**Ibrahim Shehu Ahmad**

3MTT Data Science Fellow

Fellow ID: FE/25/7761417422
