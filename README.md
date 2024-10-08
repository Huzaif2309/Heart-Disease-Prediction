# Heart Disease Prediction Model

This project aims to predict the presence of heart disease in patients based on various medical attributes. The prediction is made using a logistic regression model trained on a dataset that contains relevant health metrics.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Dependencies](#dependencies)
- [Setup](#setup)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Heart disease is a leading cause of death globally. Early diagnosis and intervention can significantly reduce mortality rates. This project implements a logistic regression model to predict the likelihood of heart disease based on various risk factors.

## Dataset

The dataset used for training and testing the model is the **Heart Disease UCI** dataset.

- **Source**: [Heart Disease UCI Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- **Features**:
  - `Age`: Age of the patient
  - `Sex`: Gender of the patient (1 = male, 0 = female)
  - `CP`: Chest pain type (0-3)
  - `Trestbps`: Resting blood pressure (in mm Hg)
  - `Chol`: Serum cholesterol in mg/dl
  - `Fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
  - `RestECG`: Resting electrocardiographic results (0-2)
  - `Thalach`: Maximum heart rate achieved
  - `Exang`: Exercise induced angina (1 = yes; 0 = no)
  - `Oldpeak`: ST depression induced by exercise relative to rest
  - `Slope`: Slope of the peak exercise ST segment (0-2)
  - `Ca`: Number of major vessels (0-3) colored by fluoroscopy
  - `Thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
- **Target**:
  - `Target`: Diagnosis of heart disease (1 = presence, 0 = absence)

## Methodology

### Logistic Regression

Logistic Regression is a statistical method for predicting binary classes. In this project, it is used to predict the presence of heart disease based on various patient attributes. The logistic regression model outputs probabilities that can be interpreted as the likelihood of a patient having heart disease.

### Evaluation Metrics

To evaluate the model's performance, we use the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

## Dependencies

Ensure the following dependencies are installed before running the project:

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter (for notebooks)

| Model               | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.85     | 0.82      | 0.80   | 0.81     |



You can install the dependencies using:
```bash
pip install -r requirements.txt
