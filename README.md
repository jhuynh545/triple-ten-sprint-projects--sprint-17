# triple-ten-sprint-projects--sprint-17

The telecom operator Interconnect aims to predict customer churn and proactively offer at-risk clients promotional deals to retain them. The task involves building a machine learning model to forecast churn based on client data and service usage. The project's success will be evaluated using the AUC-ROC metric as the primary measure and Accuracy as a secondary metric.

Key Objectives:

Predict Churn

Develop a machine learning model to predict whether a customer is at risk of churn (target: EndDate equals "No").
Optimize Performance

Achieve a minimum AUC-ROC score of 0.85 to earn at least 5 story points.
Evaluate the model's accuracy and other relevant metrics to assess its reliability.
Deliver a Prototype

Create a prototype that meets the project's technical requirements and is suitable for further development.

Work Plan:

Exploratory Data Analysis (EDA):
Understand the dataset structure and clarify missing or unnecessary information.
Analyze the distribution of the target variable (EndDate) and key features.
Identify correlations, outliers, and any categorical features requiring encoding.

Data Preprocessing:
Handle missing values, impute where necessary, and drop irrelevant columns.
Perform feature engineering to create meaningful predictors.
Encode categorical variables using suitable methods (e.g., One-Hot Encoding or Label Encoding).
Scale numerical features for algorithms sensitive to feature magnitude.

Model Development:
Split the dataset into training, validation, and test sets.
Train multiple classification models, including:
Logistic Regression (as a baseline).
Random Forest.
Gradient Boosting (e.g., LightGBM, XGBoost, or CatBoost).
Use GridSearchCV or RandomizedSearchCV for hyperparameter tuning.

Evaluation and Optimization:
Evaluate the models using AUC-ROC and Accuracy metrics on the validation set.
Select the best-performing model and test it on the holdout set.
Optimize the final model for deployment.

Report Preparation:
Document the project process, including EDA findings, preprocessing steps, model training, and evaluation results.
Highlight the strengths and limitations of the prototype.

Deliverables:

A trained and validated machine learning model with an AUC-ROC score of at least 0.85.

A detailed project report summarizing:

Data analysis and preprocessing steps.
Model development and tuning process.
Performance metrics and evaluation results.
Recommendations for deploying and improving the model.
