# Predictive-Maintenance-for-Wind-Turbines-using-ML

## Description of the Project
The U.S. Department of Energy has released a guide on predictive maintenance procedures for wind energy, a cutting-edge renewable energy source. This method evaluates and predicts component deterioration using sensor data and analytical approaches. By accurately anticipating failure trends, operating and maintenance costs can be significantly reduced, allowing for the replacement of components before they fail. The study involves training and evaluating different machine learning algorithms to predict breakdowns in wind turbines.

## Goal
This project uses machine learning to improve wind energy production by collecting data on generator failures. The dataset consists of 40 predictors, with 20,000 observations in the training set and 5,000 observations in the test set. The goal is to build classification models to proactively repair generators and minimize maintenance costs. The model interprets predictions as true positives (TP), true negative (TN), false negatives (FN), and false positives (FP). The model shows that fixing generators is less expensive than replacing them and inspecting them.

## Description of the Data
The data is partitioned into two sets: the train set and the test set. The train set contains 20,000 rows and 41 columns, while the test set contains 5,000 rows and 41 columns. The data set consists of 40 predictor variables and 1 target variable. The target variable consists of two distinct values, 0 and 1, which represent non-failure and failure, respectively. The training data for the target variable exhibited the following distribution. There are a total of 18,890 machines in good condition, and a total of 1,110 machines that have failed and require repair before breaking down. The distribution of the test data for the target variable is as follows: There are a total of 4718 machines in good condition. Out of them, there are 282 machines that have experienced failures and require repairs to prevent them from breaking down.

The data presented is a modified version of the original sensor-gathered data. The Train.csv file is intended for the purpose of training and fine-tuning models.

- The Test.csv file should only be utilised for evaluating the performance of the final best model.
- Both datasets contain 40 predictor variables and 1 target variable.
- Data Source: https://www.kaggle.com/datasets/mariyamalshatta/renewind/data.
