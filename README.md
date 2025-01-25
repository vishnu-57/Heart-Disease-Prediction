
# Heart Disease Prediction using Machine Learning

This project aims to predict the likelihood of heart disease in patients using machine learning algorithms. It leverages medical data to classify whether a person has a heart disease (binary classification problem: yes or no).

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Libraries and Dependencies](#libraries-and-dependencies)
- [Model Building](#model-building)



## Project Overview

The goal of this project is to predict the presence or absence of heart disease based on a variety of patient attributes. We utilize popular machine learning algorithms such as Logistic Regression, Decision Trees, and Random Forests to train models on a dataset and evaluate their performance.

## Dataset

The dataset used in this project contains information about patients such as age, sex, blood pressure, cholesterol levels, and more. It can be found in the **`heart.csv`** file. This dataset is publicly available and widely used in healthcare prediction challenges.

### Features:

- **age**: Age of the patient (in years)
- **sex**: Gender of the patient (1 = male, 0 = female)
- **cp**: Chest pain type (4 types)
- **trestbps**: Resting blood pressure
- **chol**: Serum cholesterol level
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (0, 1, 2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: Depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels colored by fluoroscopy
- **thal**: Thalassemia (3 types)
- **target**: Whether the patient has heart disease (1 = yes, 0 = no)

## Libraries and Dependencies

This project is built using Python, and it requires the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

To install the required dependencies, run:

```
pip install -r requirements.txt
```

## Model Building

1. **Data Preprocessing**: The data is cleaned, missing values are handled, and features are normalized for efficient training.
2. **Feature Selection**: Important features are identified, and irrelevant features are removed.
3. **Model Training**: We train multiple machine learning models, such as:
   - Logistic Regression
   - SVM Classifier
   - Random Forest Classifier
4. **Model Evaluation**: The models are evaluated using accuracy, precision, recall, and F1-score.


