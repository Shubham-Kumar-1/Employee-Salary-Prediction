# Employee Salary Prediction using Machine Learning

This project is a Machine Learning-based solution that predicts the annual salary of employees based on key attributes such as years of experience, education level, job title, and work location. It helps HR departments and job seekers get a fair, data-driven estimate of compensation, eliminating bias and guesswork.

## Problem Statement

Determining accurate and fair salaries is a challenge in many organizations. Traditional methods are manual, subjective, and inconsistent. This project aims to automate and standardize salary predictions using supervised machine learning techniques trained on real-world employee data.

## Machine Learning Pipeline

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Encoding (Label Encoding for categorical variables)  
- Model Training using Random Forest Regressor  
- Model Evaluation using MAE, RMSE, and R² Score  
- Model Saving with `joblib`  
- Salary Prediction from new inputs

## Dataset Sample

| experience | education_level | job_title        | location | salary   |
|------------|-----------------|------------------|----------|----------|
| 5          | Master           | Software Engineer| Mumbai   | 850000   |

> Note: Categorical fields are label encoded during preprocessing.

## Tech Stack

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn (for EDA)  
- scikit-learn (ML models)  
- Joblib (model serialization)

## How to Run

```bash
# Step 1: Install dependencies
pip install -r requirements.txt

# Step 2: Run training script
python employee_salary_prediction.py

# Step 3: Predict new salary
python predict_salary.py
