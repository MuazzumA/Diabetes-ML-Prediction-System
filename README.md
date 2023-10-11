# Diabetes-ML-Prediction-System

This project focuses on predicting whether a person has diabetes based on certain health indicators. I used the PIMA Diabetes dataset and utilized a Support Vector Machine (SVM) classifier. 

# Data Collection and Analysis 

This dataset contains information about pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, and age. 

# Data Preprocessing 

Took steps to prepare the data for training. 
Data Standardization: Used StandardScalar from sci-kit-learn to scale features, this helps the model make better predictions. Data is transformed to a mean of 0 and a standard deviation of 1. 

# Model Training and Evaluation 

Train-Test Split: The dataset has been split into training and testing sets to access the model's performance. 
Model Selection/Training: Used an SVM classifier with a linear kernel to train the prediction model. 
Evaluation: Calculate accuracy scores for both set splits. 

