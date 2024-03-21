                                                                                           Parkinson's Disease Detection Project
Overview

 This repository contains code and resources for a data science project aimed at detecting Parkinson's Disease using machine learning techniques. The project utilizes a dataset containing various features extracted from biomedical voice measurements of individuals with and without Parkinson's Disease. The goal is to build a predictive model capable of accurately identifying the presence of Parkinson's Disease based on these features.

 Dataset
 
The dataset used in this project consists of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). Each column in the table is a particular voice measure, and each row corresponds to one of 195 voice recordings from these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, according to the "status" column which is set to 0 for healthy and 1 for PD. 
The Dataset can be obtained from "https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set".

This project is done using Google collab and the original file can be found on 'https://colab.research.google.com/drive/1b9Q0rnCmeCEXu0l_KtdbkNM8w_am4LqC'.

💉**** PARKINSON'S DISEASE DETECTION ****💉

![ShakesGIF](https://github.com/Poorvansh26/Parkinson-s-Disease-Detection/assets/95774345/7408f815-69da-4b6b-a4a9-7131a9c9cc04)

![YesNoGIF](https://github.com/Poorvansh26/Parkinson-s-Disease-Detection/assets/95774345/dbdd5ad2-eb5d-4ddf-af81-637eb6f31d08)

This repository contains code and resources for a data science project aimed at detecting Parkinson's Disease using machine learning techniques.
This project checks whether a person has Parkinson's Disease or not, and is based on Support Vector Machine Model (SVM).

📓**** DESCRIPTION ****

This project is based on the SVM Model and has several parts :

1. Data Loading and Exploration:

Loads a dataset from a CSV file named 'parkinsons.csv' into a DataFrame.
Displays basic information about the dataset such as its shape, data types, and missing values.
Provides descriptive statistics to understand the distribution of data.
Counts the occurrences of each class label in the dataset.

2. Data Preparation:

Separates features from the target variable.
Drops irrelevant columns ('name') from the feature set.

3. Data Splitting:

Splits the dataset into training and testing sets.

4. Data Standardization:

Standardizes the features to have a mean of 0 and a standard deviation of 1.

5. Model Training:

Trains a Support Vector Machine (SVM) classifier with a linear kernel on the standardized training data.

6. Model Evaluation:

Evaluates the trained model's performance on both the training and testing datasets using accuracy score.

7. Prediction:

Constructs an input data point for prediction.
Standardizes the input data point using the same scaling parameters as the training data.
Uses the trained model to predict whether the individual represented by the input data has Parkinson's disease.
Prints the prediction result.




