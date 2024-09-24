# Loan Default Prediction: A Comparative Analysis of Machine Learning Models

## Introduction

This project aims to develop machine learning models for predicting loan default using a dataset containing various customer attributes. The financial sector heavily relies on accurate prediction of loan default for risk assessment and decision-making. The main objectives of this project are:

- Explore the dataset to understand the distribution of customer attributes and identify patterns related to loan default.
- Investigate the relationship between different customer features and loan default.
- Determine the key variables that influence the likelihood of loan default.
- Develop predictive models using machine learning algorithms and evaluate their performance in predicting loan default.
- Compare the performance of different machine learning algorithms and identify the most effective model for predicting loan default.

## Research Questions

Through these analyses, we aim to answer the following questions:

- What are the key variables that determine the chance of loan default? 
- What is the relationship between the likelihood of loan default and various customer factors including age, income, and credit history?
- Are there any noteworthy correlations, if any, between loan default and the customer features?
- Based on the provided features, which machine learning model best predicts loan defaults?


## Methodology

We will develop predictive models using various machine learning algorithms such as Logistic Regression, Random Forest, Support Vector Machine, and Gradient Boosting Classifier. The dataset will be split into training and testing sets for model training and evaluation.

1) Data Observation

The dataset contains several features that describe the financial and personal attributes of customers. These include age, income, credit history, loan amount, loan duration, and employment status. Additionally, the dataset includes the target variable, "default," which indicates whether a customer defaulted on their loan or not. 

2) Data exploration and visualization

a) Univariate Analysis

For numerical features such as age, income, loan amount, and loan duration, we will perform univariate analysis to understand their distributions and identify any outliers. This will involve visualizing histograms, box plots, and density plots to uncover patterns and assess the spread and central tendency of the data.

Similarly, for categorical features such as credit history, employment status, and housing type, we will conduct univariate analysis to examine their distributions and frequencies. Bar plots and frequency tables will be used to visualize and analyze the distribution of categorical variables.

b) Bivariate Analysis

To explore the relationship between the target variable (loan default) and other features, we will conduct bivariate analysis. This will involve visualizing the relationship between the target variable and each predictor variable using appropriate plots such as box plots, scatter plots, and bar plots. We will also compute correlation coefficients and perform statistical tests to quantify the strength and significance of relationships between variables.

3) Identification of predictor variables using statistical tests

Correlation analysis and Anova F-test are performed for numerical features to identify numerical predictors. Chi-Square test is performed on categorical features to identify categorical predictors.

4) Data pre-processing

missing values were handled, scaled numerical features, and used one-hot encoding to transform categorical data into numerical format as part of the preprocessing step. 

5) Data Preparation: splitting into training and testing sets

"MinMaxScaler" normalization is done for numerical features before splitting the data into training and testing sets in 80:20 ratio.

6) Model training and evaluation

Models like logistic regression, random forest classifier, support vector machines and Gradient boosting classifier are used to train and evaluate.

## Results

The performance of each model is reported in terms of accuracy, precision, recall, and F1-score. Additionally, the ROC curves, precision-recall curves, and confusion matrices were analysed to evaluate the performance of the models.

## Discussion

Discussion on the observations made from models trained and evaluated on the dataset and studies that are needed to be done to further improve the predictive accuracy of the model.

## Conclusion

Based on our analysis, conclusions were drawn about the key variables influencing loan default and identify the best-performing machine learning model for predicting loan default.



