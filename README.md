# APR-CS502-
Bank Marketing Campaign Prediction
Project Overview
This project uses a logistic regression model to predict whether a client will subscribe to a term deposit based on data from a bank's telemarketing campaign. The goal is to identify the key factors that influence a client's decision, allowing for more targeted and effective marketing strategies.

This analysis is based on the "Bank Marketing Data Set" from the UCI Machine Learning Repository.

Files in this Repository
bank.csv: The dataset containing client information, campaign details, and the final subscription outcome. (Separator is ';').

customer_churn_prediction.py: A Python script that performs the entire data analysis workflow. This includes:

Loading and preprocessing the data.

Training a logistic regression model.

Evaluating the model's performance.

Visualizing the results, including a confusion matrix, ROC curve, and feature importance.

bank_marketing_report.md: A detailed report summarizing the project's methodology, findings, and strategic recommendations based on the model's output.

README.md: This file, providing an overview of the project.

How to Run the Analysis
To replicate the analysis, follow these steps:

Prerequisites: Ensure you have Python installed, along with the following libraries:

pandas

scikit-learn

matplotlib

seaborn

ipython (for displaying dataframes in some environments)

You can install these using pip:

pip install pandas scikit-learn matplotlib seaborn ipython

Download the Files: Place bank.csv and customer_churn_prediction.py in the same directory.

Execute the Script: Run the Python script from your terminal or an IDE like VS Code or Jupyter Notebook.

python customer_churn_prediction.py

Review the Output: The script will print the model's classification report and model coefficients to the console and generate plots for the confusion matrix and ROC curve.

Summary of Findings
The analysis revealed several key predictors for term deposit subscriptions:

Strongest Predictors of Subscription: Contacting clients via cellular, previous campaign success, and running campaigns in specific months (e.g., March, October) were highly effective.

Strongest Predictors of Non-Subscription: Unknown contact methods, a high number of contacts during the current campaign, and previous campaign failures were associated with lower subscription rates.

For a complete breakdown of the results and strategic recommendations, please see the bank_marketing_report.md file.
