# HR-Employee-Attrition Prediction Project using Python & Machine learning

Project Overview

This project aims to analyze and predict employee attrition (employee turnover) using Machine Learning techniques.

Employee attrition is a critical problem for organizations as high turnover leads to increased hiring costs, productivity loss, and operational disruption. This project uses data-driven analysis to identify key factors influencing attrition and builds a predictive model to help HR departments make proactive decisions.

🎯 Problem Statement

Organizations struggle to identify employees who are likely to leave.
The goal of this project is to:

Analyze employee data to understand attrition patterns

Identify key factors responsible for employee turnover

Build a classification model to predict whether an employee will leave

Provide actionable HR insights

📊 Dataset Description

The dataset contains employee-related information such as:

Age

Gender

Department

Job Role

Monthly Income

Job Satisfaction

Work-Life Balance

Years at Company

Overtime

Distance from Home

Education Level

Performance Rating

Attrition (Target Variable)

Target Variable:

Attrition

Yes (Employee Left)

No (Employee Stayed)

🔎 Project Workflow
 
1️⃣ Data Preprocessing

Checked and handled missing values

Encoded categorical variables

Removed irrelevant features

Converted target variable into binary format

Scaled numerical features (if applied)

2️⃣ Exploratory Data Analysis (EDA)

Performed detailed analysis to identify patterns:

Attrition distribution (class imbalance check)

Attrition by Department

Attrition by Job Role

Impact of Overtime on Attrition

Relationship between Monthly Income and Attrition

Job Satisfaction vs Attrition

Years at Company vs Attrition

Key insights were extracted before modeling.

🤖 Machine Learning Implementation


🔹 Model Type

Classification Model (e.g., Logistic Regression / Random Forest / Decision Tree — update according to your model)

🔹 Evaluation Metrics Used

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

The model predicts whether an employee is likely to leave the company based on their work-related attributes.

📈 Key Insights


Employees working overtime are more likely to leave.

Lower job satisfaction strongly correlates with higher attrition.

Employees with lower monthly income show higher turnover rates.

Employees with fewer years at the company are more likely to leave.

Work-life balance plays an important role in retention.

🛠️ Technologies Used


Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

Business Impact

This project can help HR teams:

Identify high-risk employees

Take preventive retention measures

Improve employee satisfaction

Reduce recruitment and training costs

Make data-driven HR decisions
