# HR Employee Satisfaction Prediction - Machine Learning Project

## Overview:
In this project, I applied machine learning models to predict employee satisfaction and potential churn. The goal is to provide insights to companies about their employees and help improve retention strategies. This is particularly useful for HR departments that want to proactively address issues before employees decide to leave.

## Technologies Used:
- **Python**
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
- **Jupyter Notebook** (for interactive code and visualization)

## Project Steps:

### 1. Data Preprocessing:
   - **Data Cleaning**: Removed missing values and outliers to ensure the dataset's quality.
   - **Feature Selection**: Identified key features that could impact employee satisfaction.
   - **Encoding Categorical Variables**: Applied one-hot encoding to convert categorical variables into numerical values.

### 2. Feature Engineering:
   - Created new features based on my understanding of the data and the business context, helping improve model performance.
   - Included features like tenure, job role, satisfaction level, and last evaluation to predict churn.

### 3. Model Building:
   I experimented with multiple machine learning models to predict employee satisfaction and churn, including:
   - **Logistic Regression**: A baseline model to understand relationships between features.
   - **Random Forest**: A more robust model to account for non-linear relationships.
   - **XGBoost**: The final model I used, which gave the best results for accuracy and precision.

### 4. Model Evaluation:
   I used multiple metrics to evaluate the models:
   - **Accuracy**: To measure the overall performance of the models.
   - **Precision and Recall**: To evaluate how well the models identify satisfied and unsatisfied employees.
   - **ROC-AUC Score**: To assess how well the model distinguishes between classes.

### 5. Conclusion:
   After comparing all models, I concluded that **XGBoost** provided the best performance, achieving **85% accuracy**. The model was able to predict employee dissatisfaction and churn with great precision, making it an effective tool for HR departments to take preventive actions.

## Getting Started:
To run this project locally, make sure you have the required libraries installed. You can easily do this by running the following command:

## Check the full project here:
You can check the whole project here: [GitHub Repository](https://github.com/viniciusfrantz/data_science/blob/master/hr_emp_sat/HR_project_ML.ipynb)
