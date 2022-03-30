# Car-Evalution

By building classification models, I was able to predict the evaluaion of the car based on their characteristics.

This dataset has 1728 records, each record representing a car evaluation. Each car evaluation is described with 7 attributes. 6 of the attributes represent car characteristics, such as buying price, price of the maintenance, number of doors, capacity in terms of persons to carry, the size of luggage boot, and estimated safety of the car. The seventh variable represents the evaluation of the car (unacceptable, acceptable, good, very good).

First, I applied nested grid search CV technique to find out the best model among Decision Tree, Logistic Regression, KNN, Naive Bayes, and SVM. Then, I used SVM as my final model and trained another model to get the best hyperparameter. The accuracy is 99%. 

More details about the dataset: https://archive.ics.uci.edu/ml/datasets/car+evaluation
