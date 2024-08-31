# Loan Default Prediction: Insights from Logistic Regression Analysis
By: Can "Jon" Ayter

## Introduction
This project develops a logistic regression model to predict loan defaults based on financial data, facilitating risk assessment and decision-making in the lending industry. The analysis aims to provide insights into the effectiveness of using machine learning techniques for credit risk evaluation.

## Data
Our dataset comprises various financial attributes of loan applicants, including:
* Loan size
* Interest rate
* Borrower income
* Debt-to-income ratio
* Number of accounts
* Derogatory marks
* Total debt
* Loan status (target variable)

## Process
### Data Preparation and Exploration
* Imported necessary libraries (NumPy, Pandas, Scikit-learn)
* Loaded the dataset from 'lending_data.csv'
* Separated features (X) and target variable (y)
* Split the data into training and testing sets using train_test_split

### Model Development
* Instantiated a LogisticRegression model
* Fitted the model using the training data
* Made predictions on the test data

### Model Evaluation
* Generated a confusion matrix
* Calculated and printed the classification report

## Results
Logistic Regression Model Performance:

* Accuracy: 0.99
* Precision: Healthy Loans (0): 1.00
* Precision: High-Risk Loans (1): 0.87
* Recall: Healthy Loans (0): 1.00
* Recall: High-Risk Loans (1): 0.89

## Key Findings
* The model exhibits high accuracy and precision for both loan classes.
* Performance is better in predicting healthy loans compared to high-risk loans.
* There is a slight class imbalance in the dataset, with a larger proportion of non-defaulting loans.

## Tools Used
* Python
* Pandas for data manipulation
* Scikit-learn for machine learning tasks
* NumPy for numerical operations

## How to Use This Project
* Clone the repository
* Install required dependencies (Pandas, Scikit-learn, NumPy)
* Run the Jupyter Notebook to see the analysis and results

## Future Work
* Implement additional machine learning models for comparison (e.g., Random Forest, Gradient Boosting)
* Address class imbalance through techniques like oversampling or undersampling
* Explore feature engineering to potentially improve model performance
* Conduct a more in-depth analysis of misclassified loans

## Summary and Recommendations
The Logistic Regression model demonstrates high accuracy and balanced performance in predicting both healthy and high-risk loans. However, the slightly lower precision and recall for high-risk loans suggest room for improvement. Given the model's robust performance, further evaluation and potential deployment are recommended. It's crucial to continuously monitor and refine the model to address class imbalance and adapt to evolving financial landscapes.

## About the Author
Can "Jon" Ayter
* [GitHub Profile](https://github.com/canayter/)
* [LinkedIn Profile](https://www.linkedin.com/in/canayter/)
