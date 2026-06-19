# Loan Approval Prediction Using Machine Learning

## Project Overview

This project predicts whether a loan application will be approved or not based on applicant details such as income, education, employment status, credit history, loan amount, and property area.

The project was completed as a machine learning practice project to understand the full workflow of a classification problem, including data preprocessing, handling missing values, encoding categorical variables, model training, and evaluation.

## Dataset

The dataset contains loan application records with applicant and loan-related information.

Each row represents one loan application.

## Features

The dataset includes the following columns:

* `Loan_ID` - Unique loan application ID
* `Gender` - Gender of the applicant
* `Married` - Marital status of the applicant
* `Dependents` - Number of dependents
* `Education` - Education level of the applicant
* `Self_Employed` - Whether the applicant is self-employed
* `ApplicantIncome` - Income of the applicant
* `CoapplicantIncome` - Income of the co-applicant
* `LoanAmount` - Loan amount requested
* `Loan_Amount_Term` - Term of the loan
* `Credit_History` - Credit history of the applicant
* `Property_Area` - Location category of the property
* `Loan_Status` - Loan approval status

## Target Variable

The target column is:

* `Loan_Status`

Values:

* `Y` - Loan approved
* `N` - Loan not approved

## Objective

The objective of this project is to build a machine learning model that can predict whether a loan application is likely to be approved or rejected.

## Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* GitHub

## Project Workflow

The project follows these steps:

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check for missing values
5. Handle missing values using appropriate techniques
6. Perform basic data visualization
7. Encode categorical variables into numerical values
8. Separate features and target variable
9. Split the dataset into training and testing data
10. Train a machine learning classification model
11. Evaluate the model performance
12. Make predictions

## Model Used

The model used in this project is:

* Support Vector Machine Classifier

The SVM model was used because this is a binary classification problem where the output is either loan approved or loan not approved.

## Model Evaluation

The model was evaluated using accuracy score.

Model evaluation helps to understand how well the trained model performs on unseen test data.

## Project Structure

```text
loan-approval-prediction/
│
├── loanpred.ipynb
├── train_u6lujuX_CVtuZ9i (1).csv
└── README.md
```

## How to Run the Project

1. Clone this repository:

```bash
git clone <your-repository-link>
```

2. Open the project folder.

3. Install the required libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

4. Open the Jupyter Notebook:

```text
loanpred.ipynb
```

5. Run the notebook cells step by step.

## What I Learned

Through this project, I practiced:

* Understanding a real-world classification dataset
* Checking and handling missing values
* Using count plots for categorical data analysis
* Encoding categorical data
* Splitting data into training and testing sets
* Training an SVM classification model
* Evaluating model performance
* Managing the project using GitHub

## Conclusion

This project helped me revise the basic machine learning workflow for a classification problem. It also gave me practical experience in handling categorical data, missing values, and building a prediction model using Scikit-learn.

## Author

**Ananthu Mangalan**
