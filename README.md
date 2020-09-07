# Kaggle Titanic Machine Learning Competition
View Kaggle Notebook: https://www.kaggle.com/hoomanramezani/kernel67e1c4e339

The goal of this competition is to build an ML model that predicts which passengers survived the Titanic shipwreck, using the Titanic passenger dataset (ie name, age, gender, socio-economic class, etc).
     
Initially the dataset was analyzed in depth, with each features and experimental feature cross's correlation with survival tested. Our feature engineering concluded with 7 numeric features with strong predictive power towards survivablity that were ready to be fed into our model.
     
With feature engineering complete we created a model to predict survivability. The model was a sequential neural network using a Stochastic Gratient Descent algorithm and dropout regularization. The model was effective, with accuracy between 84-86% (correctly predicted if a passenger will survive 84-86% of the time). Submission of our model landed us in the top 20% of submissions on Kaggle.

The code can be viewed on the Kaggle Notebook and in the titanic.py document.
