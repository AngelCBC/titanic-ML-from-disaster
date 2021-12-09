# titanic-ML-from-disaster
This repo consists of a Kaggle challenge called: Titanic - Machine Learning from Disaster (https://www.kaggle.com/c/titanic/overview). Consist in the use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

First, I applied some feature selection based in a Random Forest Regression and then RandomizedSearchCV to find some parameters to optimize the classification provided by the Random Forest Classifier. The accuracy obtained is 0.9147 in the train set and 0.7703 in the test set. 

WARNING! Fit the Randomized Search takes so long (>3h in my case).
