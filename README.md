# Project - Predicting Heart Disease 

## About the Dataset:
   1. Name of the dataset - health_activity_data.csv
   2. Website : Downloaded form Kaggle
   3. Description:
    By using the data like height, weight, BMI, sleeping hours, excercise hours, heart rate, blood pressure we can analyse the heart disease of the person.
   4. Columns :  12 columns

## Objective of the Project:
    The objective of this project is to develop a machine learning model using a 
    Decision Tree Classifier to predict whether a patient is likely to have heart 
    disease based on various medical attributes. The goal is to assist in early 
    diagnosis and support clinical decision-making.

## Methodology

### Data Preprocessing

1.Removed leading/trailing whitespaces in column names
2.Handled categorical variables (e.g., encoding 'Male', 'Female')
3.Checked for missing values and outliers (if any)
4.Detected for outliers by using the IQR method.

### Feature Selection

All features were included except the target column (Heart_Disease) for training

### Splitting the Data

Dataset was split into training and test sets (e.g., 80/20 split)

### Model Building

1.Implemented a Decision Tree Classifier using sklearn
2.Default hyperparameters with random_state=42
3.Trained the model on the training dataset

### Evaluation

Predictions were made on the test set

### Evaluated using:

1.Accuracy
2.Confusion Matrix
3.Classification Report (Precision, Recall, F1-score)
