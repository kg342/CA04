# CA04
Computer Assignment 4
This assignment takes in census data from a provided github repository https://github.com/ArinB/MSBA-CA-Data/blob/main/CA03/census_data.csv?raw=true
The provided data is then split into training and testing subsets. The target variable and independent variables are segmented to be used in several different ensemble machine learning methods. Model performance is measured against 4 different types of ensemble methods: Random Forest, AdaBoost, Gradient Boost, and XG Boost classifiers. 
A graph of accuracy performance is shown for each ensemble method as different levels of n_estimators are used to generate the models and predictions.
Finally each model is created again using the same set of hyperparameters. The accuracy and area under the curve scores are recorded for each model and printed at the end. Additionally, all the common hyperparameters are printed as well.
