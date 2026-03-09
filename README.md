# Teaching Assistant Performance Prediction

## Project Overview

This project uses machine learning techniques to predict the **performance category of teaching assistants (TAs)** based on course and instructor related attributes.

The goal is to help educational institutions identify factors influencing TA effectiveness and improve teaching quality.

---

# Problem Statement

Universities employ teaching assistants to support instructors in courses. However, their performance can vary depending on several factors.

This project aims to build a classification model that predicts the **teaching assistant performance category** using course and instructor information.

---

# Dataset Description

The dataset contains information about teaching assistants, courses, and instructors.

Key features include:

* English speaker status
* Course instructor
* Course type
* Class size
* Semester information

Target variable:

Teaching assistant performance category.

Possible categories include:

* Low
* Medium
* High

---

# Project Workflow

## 1 Data Loading

The dataset was loaded using Pandas and basic data inspection was performed.

Initial analysis included:

* checking data types
* identifying missing values
* examining class distribution

---

## 2 Exploratory Data Analysis

Exploratory analysis was performed to understand relationships between features and the target variable.

Visualizations included:

* count plots
* feature distribution analysis
* correlation insights

This helped identify patterns influencing teaching assistant performance.

---

## 3 Data Preprocessing

Categorical variables were converted into numerical format using encoding techniques.

Typical preprocessing steps included:

* label encoding
* feature transformation
* data normalization (if required)

---

## 4 Train-Test Split

The dataset was split into training and testing datasets using:

```
train_test_split()
```

This allows evaluation of model performance on unseen data.

---

# Machine Learning Models

Multiple classification algorithms were tested.

### Logistic Regression

A baseline linear model used for classification.

---

### K-Nearest Neighbors (KNN)

A distance-based classification algorithm.

---

### Decision Tree

A tree-based model capable of capturing nonlinear relationships.

---

### Random Forest

An ensemble learning algorithm that improves prediction accuracy by combining multiple decision trees.

---

# Model Evaluation

Models were evaluated using:

* Accuracy score
* Confusion matrix
* Classification report

Evaluation metrics include:

* Precision
* Recall
* F1-score

These metrics help assess model performance across different classes.

---

# Results

Tree-based models such as Random Forest generally performed better due to their ability to capture complex relationships between features.

The final model achieved good classification accuracy in predicting teaching assistant performance categories.

---

# Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

---

# Project Structure

teaching-assistant-performance-prediction
│

├── Teaching Assistance Project.ipynb

├── requirements.txt

├── README.md

---

# Author

Yussouf R
Machine Learning Project
