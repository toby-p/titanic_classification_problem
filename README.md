# titanic_classification_problem
This is my example approach to a supervised classification problem, using the Titanic survivors dataset from Kaggle.

The challenge is to train a model on the 'train.csv' data to predict survivors from the Titanic passenger list based on other known details of the passengers, such as age, sex and ticket class, and then use this model to make predictions of who survived in the 'test.csv' data.

As a classification problem the objective is to try to minimise the number of false positives and false negatives in the predictions; which is measured with the ROC-AUC metric.
