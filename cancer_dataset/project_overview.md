# CANCER CLASSIFICATION USING SVM AND LOGISTIC REGRESSION

So the given cancer dataset has 30 attributes which values will tell us if the cancer is benign or malignant.
This is a binary classification problem.Logistic regression and Support vector machines are good with classification problems so we use these models on the dataset.
We tried to scale the features using sklearn's preproccessing module,and we tried to see the heatmap for the given features,we can improve this model maybe by feature engineering which I still have to learn.
The accuracy of the logistic regression is really good after adjusting the lambda and the confusion matrix also gave pretty good results for this model.
Coming to the support vector machines we still donot the reason for more accuracy for the test set,but the confusion matrix for SVM is also pretty good.
But we prefer Logistic regression over the support vector machines for this model as the accuracy rating are really good.
After doing it with KNN,we have really good results compared to both logistic regression and SVM,but the confusion matrix clearly shows that the logistic regression classifiers more number of stuff perfectly.
Decision trees also have pretty good results but as we can see from the accuracy scores logistic regression is still the best.