# Diabetes-Prediction
This project focuses on the prediction of diabetes among the Pima Indian population near Phoenix, Arizona, USA, using KNN approach.

## Dataset
The Pima Indian Diabetes Dataset contains data from 768 women and includes several medical predictor variables and one target variable, Outcome. Predictor variables include the number of pregnancies, glucose concentration, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age.

## Handling Missing Data
One of the key challenges with the Pima Indian Diabetes Dataset is its missing values, particularly in columns such as Glucose, Blood Pressure, Skin Thickness, Insulin, and BMI. Our approach involves:

. Identifying missing values, which are initially recorded as zeros.

. Replacing these zeros with NaN for a more accurate representation of missing data.

. Exploring data distribution and relationships between variables through visualization.

. Imputing missing values using statistical methods or predictions from other variables for a more complete dataset.

## Exploratory Data Analysis (EDA)
We perform EDA to understand the distribution of various features and their relationship with the diabetes outcome. This includes generating pair plots to visualize the dataset's distribution and identifying any apparent patterns or clusters.

## Model Training
We utilize the K-Nearest Neighbors (KNN) algorithm for classification.

A grid search is conducted to optimize hyperparameters, including the number of neighbours and the distance metric (p).

## Result
Using KNN and an optimal number of neighbours we were able to get 82% accuracy.
