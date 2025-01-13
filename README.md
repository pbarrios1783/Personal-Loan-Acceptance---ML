# Personal Loan Acceptance Prediction

### 📌 Overview
This project analyzes customer data from AllLife Bank to build a predictive model for identifying individuals most likely to accept personal loan offers. By leveraging machine learning, this project aims to optimize marketing strategies and enhance customer targeting efficiency.

### 🎯 Objectives
#### Business Goals
Improve the success rate of personal loan campaigns by identifying high-potential customers.
Provide actionable insights to support data-driven marketing decisions.

#### Machine Learning Goals
Develop a reliable predictive model using customer demographic, behavioral, and financial data.
Evaluate model performance using key metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

### 🗂 Dataset
The dataset includes various attributes related to customer profiles. Key features are:

ID: Unique customer identifier.
Age: Customer's age (in years).
Experience: Number of years of professional experience.
Income: Annual income (in thousands of dollars).
Family: Number of family members.
CCAvg: Average monthly credit card spending (in thousands of dollars).
Education: Customer's education level:
1: Undergraduate
2: Graduate
3: Advanced/Professional
Mortgage: Value of the customer’s house mortgage (in thousands of dollars).
Personal_Loan: Target variable indicating loan acceptance:
1: Accepted
0: Not Accepted
Securities_Account, CD_Account, Online, CreditCard: Binary features representing customer behavior.

### 📋 Notebook Structure
1. Exploratory Data Analysis (EDA)
Data visualization to explore trends, distributions, and key predictors.
Insights into customer behaviors that influence loan acceptance.

2. Data Preprocessing
Address missing values and outliers.
Encode categorical variables and scale numerical features.
Apply class balancing techniques (if needed).

3. Model Building
Models used:
Logistic Regression
Decision Tree (with post-pruning)
Random Forest
Neural Networks
Hyperparameter tuning applied for Decision Trees and Neural Networks to optimize performance.

4. Model Evaluation
Metrics used:
Accuracy
Precision
Recall
F1-Score
ROC-AUC
Analysis of false positives and false negatives to assess business implications.

### ✅ Results
Best Performing Model: Decision Tree with Post-Pruning

#### Accuracy:
Train: 89.5%
Test: 87.8%

#### Precision:
Train: 88.1%
Test: 85.7%

#### Recall:
Train: 91.3%
Test: 89.6%

#### F1-Score:
Train: 89.7%
Test: 87.6%

ROC-AUC: 0.94

### Key Insights:

Customers with higher income and average monthly credit card spending are more likely to accept personal loans.
Graduate and professional education levels correlate with higher loan acceptance rates.

### 💡 Recommendations
Deploy the best-performing Decision Tree model with post-pruning for predicting loan acceptance.
Focus marketing efforts on customer segments identified as high potential:
High-income earners
Credit-active individuals
Customers with graduate or advanced education levels
Retrain the model periodically with updated data to ensure adaptability to changing customer behaviors.

### 🚀 How to Use
Clone this repository:
bash
Copy code
git clone https://github.com/your-repo-name/personal-loan-prediction.git
cd personal-loan-prediction
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the notebook in Jupyter or any compatible IDE:
bash
Copy code
jupyter notebook personal-loan-acceptance-prediction.ipynb

### 📈 Future Work
Expand Dataset: Incorporate additional customer attributes like spending trends and customer feedback for better predictions.
Advanced Models: Experiment with ensemble models like XGBoost or AutoML for enhanced performance.
Explainability: Add model interpretability tools (e.g., SHAP) to explain predictions to stakeholders.
