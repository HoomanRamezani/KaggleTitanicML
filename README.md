# Kaggle Titanic Machine Learning Competition
Kaggle Notebook: https://www.kaggle.com/hoomanramezani/kernel67e1c4e339

     The goal of this competition is to use machine learning to create a model that predicts which passengers survived the Titanic shipwreck. A predictive model must be built that answers the question “What sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).
     
     Initially the dataset was analyzed in depth, with each feature and experimental feature cross's correlation with survival tested. Our feature engineering concluded with 7 numeric features with strong predictive power towards survivablity that were ready to be fed into our model.
     
     With feature engineering complete we created a model to predict survivability. The model was a sequential neural network with a Stochastic Gratient Descent algorithm and dropout regularization. The model was effective, with accuracy between 84-86% (correctly predicted if a passenger will survive 84-86% of the time). Submission of our model landed us in the top 20% of submissions on Kaggle.
