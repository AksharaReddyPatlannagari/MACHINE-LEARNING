# DIABETES DATASET USING LINEAR REGRESSION

This project basically tries to fit a linear regression curve to the dataset.
The dataset has data related to diabetes patients.
It can be used to predict disease progression in an individual after an year.
All the attributes have been adjusted to a particular range already.
From the scatter plots we can observe that linear regression may actually be the good model to use in this case.
If we see the accuracy of the model it luks like we overfit the training data,bt wen we performed with a different data fr test we got the scores close to one another,so the cross validation technique used in this project might not be a good one,as we go further let's see the best cross validation techniques and improve our model.
Trying ridge regression clealy improved our test set's score,but the overall model is'nt a good fit I'm guessing its either cuz of the data or we have to perform feature engineering,or our model is too simple and it's underfitting.
Lasso regression is also nt of any use as our model is clearly underfit its not going to work,might actually reduce the efficiency.
KNN isnt any good either I think it's the dataset problem.