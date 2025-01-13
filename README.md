# Personal Loan Acceptance Prediction
Overview
This project analyzes data from AllLife Bank to build a predictive model that identifies customers most likely to accept a personal loan offer. By leveraging machine learning, the notebook aids in enhancing marketing strategies, improving conversion rates, and targeting high-potential customers effectively.

Objectives
Business Goal:

Increase the success rate of personal loan campaigns by identifying high-potential customers.
Provide actionable insights for marketing optimization.
Machine Learning Goal:

Develop a robust predictive model using customer data.
Evaluate the model using key metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
Dataset
The dataset consists of customer data, including demographic, behavioral, and financial attributes. Key features include:

ID: Unique customer identifier.
Age: Customer's age.
Experience: Professional experience in years.
Income: Annual income (in thousands of dollars).
Family: Number of family members.
CCAvg: Average monthly credit card spending.
Education: Education level:
1: Undergraduate
2: Graduate
3: Advanced/Professional
Mortgage: Mortgage value (in thousands of dollars).
Personal_Loan: Target variable (1 = Accepted, 0 = Not Accepted).
Securities_Account, CD_Account, Online, CreditCard: Binary features representing customer behavior.
Notebook Structure
1. Exploratory Data Analysis (EDA)
Data visualization to understand trends, distributions, and relationships.
Insights into customer behavior and key predictors for loan acceptance.
2. Data Preprocessing
Handling missing values and outliers.
Encoding categorical variables.
Scaling numerical features for model optimization.
3. Model Building
Models tested include:
Logistic Regression
Random Forest
Gradient Boosting
Neural Networks
Hyperparameter tuning was applied to improve performance.
4. Evaluation Metrics
Key metrics for evaluation:
Accuracy
Precision
Recall
F1-Score
ROC-AUC
Analysis of false positives and false negatives for business impact.
5. Insights & Recommendations
Key customer segments identified for targeted marketing.
Recommendations to reduce misclassifications and improve model deployment.
