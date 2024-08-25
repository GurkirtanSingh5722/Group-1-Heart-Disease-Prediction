# Heart Disease Prediction

This project involves predicting the presence of heart disease in a patient using various features such as age, gender, chest pain type, resting blood pressure, cholesterol levels, etc. The prediction is made using a machine learning model trained on a dataset containing these features.

## Project Overview

The project follows these steps:
1. **Data Collection**: The dataset used for this project contains medical data related to heart disease. The features include age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, rest ECG, max heart rate, exercise-induced angina, old peak, slope, number of vessels colored by fluoroscopy, and thalassemia.

2. **Data Preprocessing**: The dataset is cleaned and preprocessed to ensure it is in a format suitable for training a machine learning model. This step includes handling missing values, encoding categorical variables, and scaling numerical features.

3. **Model Building**: A logistic regression model is used to predict whether a patient has heart disease. The model is trained on a portion of the dataset and then evaluated on a separate test set.

4. **Model Evaluation**: The performance of the model is evaluated using accuracy on the test data. The model achieved an accuracy of approximately 81.97%.

5. **Predictive System**: A predictive system is built where the user can input data for a new patient, and the system will predict whether the patient has heart disease.

## Requirements

To run the notebook, the following Python packages are required:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install these dependencies using `pip`:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
