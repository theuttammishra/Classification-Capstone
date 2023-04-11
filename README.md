# Classification-Capstone
this is a Capstone Project 
Project Type - Classification

Contribution - Team

Team Member 1 - Uttam Mishra

Team Member 2 - Kshitij Singh

# Problem Statement

This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.We can use the K-S chart to evaluate which customers will default on their credit card payments

# Project Summary
This project named Credit Card default prediction is aimed at predicting the probability of default for a probable customer. The data is a excel file having in total of 30001 columns and 25 rows. data had informations such as customer id, age, sex, marriage info, education level etc. with this data we have to predict the default or the probability of default for a customer.

working on this project we first started with loading the dataset and going through it to understand the variables. In the dataset we found that the column headers seem to be incorrect so we replaced it with the next actual column, which in turn was the real variable column. Now the dataset which contained information regarding the credit card bill, payment and customer related info was not analysis ready so in the next step we performed data wrangling in it. we also changed the values which were numerical in columns to their appropriate values so that it will be helpful to understand the data visualizations.

After the data wrangling we moved towards data visualization. In the data visualization we used multiple graphs including Bar graph, Pie plot, Correlation heatmap, Pairplot etc. and with the help of these we found out some crucial results. we also tried top plot the relationship between discrete features and continuous features using distplot. Next to implement our Models we needed the dataset to be more balanced and categorised. Now we introduced some new features along with data preprocessing. Also at this stage we checked for outliers and missing values. For outlier treatment we used IQR method. After that we moved to feature manipulation and Categorical Encoding. After using Onehotencoding we did data split of 30%-70% test to train and then scaled our dataset. At this stage we checked whether our dataset is balanced or imbalanced and found it to be largely imbalanced. For balancing the dataset we used SMOTE which balanced the dataset. Now our data was ready for implementing Machine Learning models.

We started with Random Forest Classifier and after predicting with the model we used the Function which we created to check the evaluation metrics. After the model we used RandomSearchCV for hyperparameter tuning and then checked important feature. And also used confusion matrix for evaluation purpose. Our second model was LightBGM we performed the similar steps as in the case of RandomForest and found its evaluation metrics and for hyperparameter tuning here we used gridsearchcv and plotted the feature importance. We again performed the same steps with XGBoost as our third model. After predicting with three different models and comparing their scores we found that RandomForestClassifier is the best model.
