# employee-attrition-prediction
Employee Attrition Prediction is a machine learning project developed using Python. The project predicts whether an employee is likely to leave a company based on various factors such as salary, age, department, job role, working hours, job satisfaction, overtime, distance from home, and years of experience.
# Employee Attrition Prediction

## Project Overview

Employee Attrition Prediction is a machine learning project developed using Python. The project predicts whether an employee is likely to leave a company based on various factors such as salary, age, department, job role, working hours, job satisfaction, overtime, distance from home, and years of experience.

## Objectives

* Analyze employee data and attrition patterns.
* Identify factors related to employee turnover.
* Preprocess numerical and categorical data.
* Train a machine learning classification model.
* Predict employee attrition.
* Calculate the probability of an employee leaving.
* Evaluate model performance.
* Visualize employee attrition patterns.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Machine Learning Algorithm

The project uses **Logistic Regression** for binary classification.

The model predicts two outcomes:

* 0 – Employee Stayed
* 1 – Employee Left

## Dataset Features

The dataset contains the following features:

* Employee ID
* Age
* Salary
* Department
* Job Role
* Working Hours per Week
* Years of Experience
* Job Satisfaction
* Overtime
* Distance from Home
* Years at Company
* Attrition

## Data Preprocessing

The project performs the following preprocessing steps:

1. Loads the employee dataset using Pandas.
2. Checks for missing values.
3. Handles missing numerical values using median imputation.
4. Handles missing categorical values using the most frequent value.
5. Standardizes numerical features using StandardScaler.
6. Converts categorical features using OneHotEncoder.
7. Splits the dataset into training and testing sets.

## Model Training

A Logistic Regression model is trained using the preprocessed employee data. The trained model is then used to predict employee attrition on the test dataset and estimate the attrition probability for a new employee.

## Model Evaluation

The model is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix
* Attrition Probability

The project also analyzes Logistic Regression coefficients to identify important factors related to employee attrition.

## Data Visualization

The project generates visualizations including:

* Employee Attrition Rate by Department
* Relationship Between Job Satisfaction and Working Hours

Generated files:

```text
attrition_by_department.png
satisfaction_vs_hours.png
```

## Project Structure

```text
Employee_Attrition_Prediction/
│
├── employee_attrition.csv
├── employee_attrition_prediction.py
├── requirements.txt
├── README.md
├── attrition_by_department.png
└── satisfaction_vs_hours.png
```

## Installation

Make sure Python is installed on your system.

Install the required libraries using:

```bash
pip install -r requirements.txt
```

## How to Run

Open the terminal in the project folder and run:

```bash
python employee_attrition_prediction.py
```

The program will:

1. Load the employee dataset.
2. Check and preprocess the data.
3. Train the Logistic Regression model.
4. Predict employee attrition.
5. Display model accuracy and evaluation results.
6. Calculate the attrition probability for a sample employee.
7. Display important factors related to attrition.
8. Generate visualization charts.

## Example Prediction

The project includes an example employee profile and predicts whether the employee is likely to stay or leave the company. It also calculates the probability of attrition.

## Dataset Note

The included employee dataset is synthetic and intended for educational and machine learning practice. It does not contain real employee information.

## Future Enhancements

* Compare Logistic Regression with Random Forest, Decision Tree, and other classification algorithms.
* Improve prediction performance through hyperparameter tuning.
* Develop a web-based interface for employee attrition prediction.
* Add more employee-related features.
* Deploy the model as a web application.
* Create an interactive HR analytics dashboard.

## Conclusion

This project demonstrates how machine learning can be applied to employee attrition analysis. It covers data preprocessing, categorical encoding, feature scaling, model training, prediction, evaluation, probability estimation, feature analysis, and visualization.

## Important Note

This project is intended for educational purposes. Model predictions should not be used as the sole basis for employment or HR decisions.
