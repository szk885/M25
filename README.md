# M25
# PROJECT TITLE 
Machine Learning Model Selection and Hyperparameter Tuning Report for Stock and Cryptocurrency Price Evaluation


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
In this report, the selection of machine learning models has been discussed, hyperparameter tuning strategies, and performance metrics for a stock price prediction task. The code implementation follows the outlined strategies and provides insights into the best-performing models for the given dataset. The choice of models and hyperparameters, as well as the evaluation metric, should be adapted to the specific characteristics of the dataset and the problem at hand. The ultimate goal is to build a model that accurately predicts stock price trends. 


## DATA
YFinance is used for this project.

## MODEL 
Since the task involves predicting whether the stock price will increase or decrease (binary classification), classification the following classification models will be considered: Logistic Regression , Support Vector Classifier (SVC),  Random Forest Classifier
, K-Nearest Neighbors (KNN), Classifier XGBoost Classifier 


## HYPERPARAMETER OPTIMSATION
The main focus is on tuning 2 to 8 tunable hyperparameters for each model. The choice of hyperparameters will depend on the specific model. For hyperparameter optimization, Grid Search will be applied.
For performance evaluation of each model, ROC AUC (Receiver Operating Characteristic - Area Under the Curve) is the primary performance metric. ROC AUC is suitable for binary classification tasks like ours and provides a comprehensive measure of model performance. 


## RESULTS
Model selection and hyperparameter tuning process have been implemented in the code, which includes fetching stock data, data preprocessing, model training, and evaluation. 
The code generates a table showing the best-performing model for each algorithm, along with the best hyperparameters, training ROC AUC, and validation ROC AUC. The table is displayed in a text-based format for easy reference. 
