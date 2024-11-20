# Heart Disease Prediction Project

## Overview
This project implements a predictive system to determine the likelihood of heart disease using the **Logistic Regression** algorithm. The model is trained on a dataset of patient medical attributes and predicts whether a person has heart disease or not.

---

## Features
- **Data Analysis and Preprocessing**: 
  - Analyze the dataset structure.
  - Check for missing values.
  - Understand the distribution of the target variable.
  
- **Model Training**: 
  - Train a Logistic Regression model using Scikit-learn.

- **Model Evaluation**: 
  - Evaluate the model's accuracy on training and test datasets.

- **Prediction System**: 
  - Build a system to input patient data and predict the presence of heart disease.

---

## Dataset
The dataset used contains 303 samples and 14 features:

| Feature       | Description                                                        |
|---------------|--------------------------------------------------------------------|
| `age`         | Age of the patient (in years)                                      |
| `sex`         | Gender (1 = male, 0 = female)                                      |
| `cp`          | Chest pain type (categorical: 0-3)                                 |
| `trestbps`    | Resting blood pressure (in mm Hg)                                  |
| `chol`        | Serum cholesterol (in mg/dl)                                       |
| `fbs`         | Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false)             |
| `restecg`     | Resting electrocardiographic results (categorical: 0-2)            |
| `thalach`     | Maximum heart rate achieved                                        |
| `exang`       | Exercise-induced angina (1 = yes, 0 = no)                          |
| `oldpeak`     | ST depression induced by exercise relative to rest                 |
| `slope`       | Slope of the peak exercise ST segment (categorical: 0-2)           |
| `ca`          | Number of major vessels (0-4) colored by fluoroscopy               |
| `thal`        | Thalassemia (categorical: 1-3)                                     |
| `target`      | Heart disease diagnosis (1 = has heart disease, 0 = no heart disease) |

---

## Requirements
Install the necessary dependencies:
```bash
pip install numpy pandas scikit-learn
