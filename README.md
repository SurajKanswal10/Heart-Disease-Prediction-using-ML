OVERVIEW
This project utilizes machine learning to predict the likelihood of a person having heart disease based on various health parameters. The model is trained using a dataset that contains multiple features such as age, sex, blood pressure, cholesterol levels, and more, to predict if an individual has heart disease.

DATASET
The dataset used for training the model is a CSV file named data.csv, which includes the following features:
age: Age of the person
sex: Gender (0 = female, 1 = male)
cp: Chest pain type
trestbps: Resting blood pressure
chol: Serum cholesterol in mg/dl
fbs: Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false)
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise induced angina (1 = yes, 0 = no)
oldpeak: Depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment
ca: Number of major vessels colored by fluoroscopy
thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
target: 1 if the person has heart disease, 0 if they don't
Objectives
The objective of this project is to create a predictive model using machine learning to identify whether an individual is at risk of heart disease or not based on the aforementioned features. The model is built using logistic regression.

STEPS INVOLVED
Data Preprocessing---
Load the dataset and inspect the first few rows.
Check for missing values and clean the data if necessary.
Perform basic statistical analysis to understand the data distribution.
Feature Selection

The target variable (target) is separated from the feature columns.
The dataset is split into training and testing sets for model evaluation.
Model Building

Logistic Regression is used as the model for predicting heart disease.
The model is trained using the training dataset.
Predictions are made using the trained model on both the training and testing sets.
Evaluation

The model’s accuracy is assessed on both training and testing datasets.
The prediction results are compared against the true labels to evaluate performance.
Prediction

A predictive system is built where a new input can be given, and the system will predict if the person has heart disease or not based on the given parameters.
Model Evaluation
The model performance is evaluated using the accuracy score:

Accuracy on Training Data: The proportion of correctly predicted values on the training set.
Accuracy on Test Data: The proportion of correctly predicted values on the test set.
Example of Usage
To predict whether a person has heart disease or not, you can provide an input like the following:

input_data = (62, 0, 0, 140, 268, 0, 0, 160, 0, 3.6, 0, 2, 2)
This input represents the health parameters of an individual, and the model will predict whether the person has heart disease (1) or not (0).

CONLUSION
This project demonstrates how machine learning can be used to predict heart disease based on key medical features. With further improvements and a larger dataset, it can be used as a diagnostic tool to assist healthcare professionals in making more informed decisions.

TECHNOLOGIES USED
-Python
-NumPy
-Pandas
-Scikit-learn (for Logistic Regression and model evaluation)

HOW TO RUN
google colab would be best to run this project.
Make sure that the data.csv file is present in the same directory as the script or provide the correct file path.

AUTHOR
Suraj Kanswal
