# titanic_survival_prediction
 Welcome to my solution for the Titanic Kaggle competition. This project leverages machine learning techniques to predict the survival of passengers on the Titanic based on various features such as age, gender, class, and other demographic and social information.


Table of Contents:
Dataset
Project Structure
Features and Approach
Model Performance
Results



Dataset:
The dataset can be accessed from the Kaggle competition page: Titanic - Machine Learning from Disaster.

The dataset includes:
train.csv: The training set with passenger information and survival labels.
test.csv: The test set with passenger information only.
sample_submission.csv: A sample submission file for Kaggle.

Project Structure:
notebook - Contains the Jupyter notebook(s) for data analysis, feature engineering, model training, and evaluation.
README.md - Project description and documentation.
submission.csv - Final predictions for the test set in Kaggle submission format.


Features and Approach:


Data Preprocessing:
Missing values handled with strategies like mean imputation for continuous variables and mode imputation for categorical variables. Feature engineering with categorical encoding, scaling, and handling outliers.

Machine Learning Models:
Initial experiments with baseline models like logistic regression.
Advanced models including Decision Trees, Random Forests, Gradient Boosting, and XGBoost.
Model hyperparameter tuning with Optuna for optimal performance.

Outlier Detection:
Isolation Forest used to identify and exclude potential outliers to improve model robustness.
Model Performance
The final model was evaluated using accuracy, precision, recall, and F1 score. The optimized XGBoost classifier achieved promising results in terms of accuracy and robustness.

Results
The final predictions are stored in submission.csv, formatted for Kaggle submission with id and Survived columns.
