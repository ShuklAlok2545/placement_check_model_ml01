# Student Placement Prediction using Logistic Regression

## Project Overview

This project builds a Machine Learning model to predict whether a student will get placed or not based on two features: **CGPA** and **IQ**. The model uses **Logistic Regression**, a classification algorithm used for predicting binary outcomes such as placed or not placed.

## Project Workflow

### 1. Data Loading

The first step is loading the student dataset. The dataset contains information about students such as their CGPA, IQ, and placement status.

### 2. Data Preprocessing

After loading the dataset, basic preprocessing is performed. This includes checking the dataset structure, selecting the required features (CGPA and IQ), and defining the target variable which represents the placement status.

### 3. Exploratory Data Analysis (EDA)

EDA is performed to understand the relationship between the features and the target variable. This step helps in identifying patterns and understanding how CGPA and IQ influence student placement.

### 4. Data Transformation

Since CGPA and IQ are on different scales, feature scaling is applied using **standardization**. This ensures that both features contribute equally to the model training process.

### 5. Data Visualization

A scatter plot is created to visualize the distribution of students based on CGPA and IQ. This helps in understanding how the data points are separated according to placement status.

### 6. Model Training

A **Logistic Regression model** is used to train the dataset. The model learns the relationship between CGPA, IQ, and placement outcomes.

### 7. Model Saving

After training the model, it is saved using **Pickle** so it can be reused later without retraining. This allows the model to be deployed in applications or used for future predictions.

## Conclusion

This project demonstrates a simple Machine Learning pipeline that includes data preprocessing, visualization, feature scaling, model training, and model serialization to predict student placement.
