# Solubility_ML_project

## Overview

This project builds a machine learning model to predict **Solubility of molecules** using **delaney_solubility_with_descriptors.csv**.
The goal is to **Determine whether they are soluble in water/solvents**.This is crucial for chemists and biologists for selecting best drug candidates

---

## Dataset

Dataset used for training and evaluation.

* **Dataset Name:** delaney_solubility_with_descriptors.csv
* **Source:** https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv
* **Number of samples:** [_1144___]
* **Number of features:** [__5__]

Example dataset link:
[[Dataset URL]](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv)

---

## Problem Statement

Predicting the solubility of chemical compounds is an important problem in pharmaceutical and chemical research. Solubility determines how well a molecule dissolves in water or biological fluids, which directly affects drug absorption and effectiveness.

**The objective of this project is to develop a machine learning model that predicts the solubility of molecules using molecular descriptors from the Delaney Solubility dataset. This helps researchers quickly identify compounds with favorable solubility properties, supporting better drug candidate selection.
**---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib 
* Scikit-learn
* Google Colab

---

## Models Used

* Linear Regression
* Random Forest

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Model Saving / Deployment

---

## Model Performance


The following models were trained and evaluated on the Delaney Solubility dataset.

| Model             | Training MSE | Training R² | Test MSE | Test R² |
| ----------------- | ------------ | ----------- | -------- | ------- |
| Linear Regression | 1.0139       | 0.7695      | 0.9991   | 0.7706  |
| Random Forest     | 1.0503       | 0.7613      | 1.0470   | 0.7596  |

### Observation

Linear Regression performed slightly better than Random Forest on the test dataset with a **Test R² score of 0.7706**, indicating a strong ability to predict molecular solubility from the given descriptors.

---


## Results

Based on the evaluation metrics, **Linear Regression performed slightly better than Random Forest** on the test dataset.
It achieved a **lower Test Mean Squared Error (0.9991)** and a **higher Test R² score (0.7706)** compared to Random Forest.

This indicates that the Linear Regression model was able to generalize slightly better for predicting molecular solubility using the given descriptors.
---

## Future Improvements

* Improve feature engineering
* Use larger dataset
* Try deep learning models
* Deploy as a web application

---

## Author

Name: **Shravani Pataskar**

---


