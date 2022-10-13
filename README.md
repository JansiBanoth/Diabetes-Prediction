# Diabetes-Prediction
Predict whether a person has diabetes or not.
Importing essential libraries
Loading the dataset
Exploring the dataset

Data Cleaning
Replacing the 0 values from ['Glucose','BloodPressure','SkinThickness','Insulin','BMI'] by NaN
To fill these Nan values the data distribution needs to be understood Plotting histogram of dataset before replacing NaN values
Replacing NaN value by mean, median depending upon distribution

Model Building
Using GridSearchCV to find the best algorithm for this problem
Creating a function to calculate best model for this problem
Using cross_val_score for gaining average accuracy
Creating Random Forest Model

Model Evaluation
Creating a confusion matrix
Plotting the confusion matrix
Classification Report
Creating a confusion matrix for training set

Predictions
reating a function for prediction
Prediction 1 Input sequence: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DPF, Age
