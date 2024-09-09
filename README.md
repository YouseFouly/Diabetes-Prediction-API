# Diabetes-Prediction-API

This project provides a simple API built with FastAPI to predict whether a person has diabetes or not based on several health metrics. The model used for prediction is a Support Vector Machine (SVM), which was trained using the Pima Indians Diabetes Dataset.

Table of Contents
- Project Overview
- Features
- Model Details
- Technologies Used
- Acknowledgments



Project Overview

This project creates a machine learning model using SVM to predict diabetes based on key medical factors. The model is then deployed as an API using FastAPI to make predictions accessible via a POST request. This API takes in features such as glucose levels, blood pressure, and age, and returns whether the person is likely diabetic or not.

![image](https://github.com/user-attachments/assets/9fd6281f-a910-4032-aaa6-ddbe4f780ccc)



Features 

- Prediction Model: A Support Vector Machine model trained on the Pima Indians Diabetes Dataset.
- RESTful API: Built using FastAPI, the API can receive input data in JSON format and return predictions.
- Serialization: The model is serialized and saved using Python's pickle library for easy loading in the API.
  

Model Details:

The prediction model was trained using the Pima Indians Diabetes Dataset. It contains the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function (genetic factor)
- Age

Steps to Train the Model

if you want to train your own model, follow these steps:
1- Load the dataset from Kaggle or any trusted source.
2- Preprocess the data (e.g., handling missing values, feature scaling).
3- Train a Support Vector Machine (SVM) classifier using the dataset.
4- Save the trained model using pickle

![Capture333](https://github.com/user-attachments/assets/aa90abce-134c-4c93-8d00-8c77de1ac093)


![Capture2222](https://github.com/user-attachments/assets/22889036-1605-4df8-93c3-a8d0e357a53e)



Technologies Used

- FastAPI: For building the API.
- Pydantic: For data validation.
- scikit-learn: For the machine learning model (SVM).
- pickle: For model serialization and deserialization.
- Uvicorn: For running the FastAPI server.

 
Acknowledgments

special thanks to Eng Siddhardhan for the video on his youtube channel where i learned to create this model and deploy it from the begining to the end to be ready to deploy more diffrent models 
