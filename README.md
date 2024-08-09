# Lung-Cancer-
Hi everyone this is my first Github project. This project is designed to predict the likelihood of lung cancer in individuals who differ in terms of age, gender, and lifestyle.


---------Lung Cancer Prediction Machine Learning Project-----------------


Description

Project is designed to predict the likelihood of lung cancer based on differences in age, gender, and lifestyle among individuals. It involves implementing and evaluating various machine learning models to assess the risk of lung cancer.

Content
Dataset:

The dataset includes features related to lung cancer prediction, including age, gender, smoking status, yellow fingers, anxiety, peer pressure, chronic disease, fatigue, allergy, wheezing, alcohol consumption, coughing, shortness of breath, swallowing difficulty, and chest pain.
The target variable LUNG_CANCER is a classification label indicating the presence of cancer.
Data Preprocessing:

Checking and handling missing data.
Converting categorical data to numerical values using "getdummies".
Standardization was not applied as the feature value ranges were already between 0 and 2.
Regression and Classification Models:

Regression Models:
A simple linear regression model was implemented to predict cancer risk based on the features.
Classification Models:
Random Forest , Gradient Boosting classifiers , Decision Tree and LogisticRegression were used.
Hyperparameter optimization was performed to enhance model performance.
Model performance was evaluated using metrics such as accuracy, precision, recall, and F1 score.
Hyperparameter Optimization:

Grid Search and Bayesian Optimization techniques were used to find the best hyperparameters for the models.
The model with the best performance was selected based on the optimization results.
Results and Visualization:

Performance results of the models were presented in tabular format.
Graphs comparing actual and predicted values were created to visualize model performance.
Libraries Used
numpy
pandas
scikit-learn
matplotlib
-----------------------------------------
Thanks for reading.
