# RandomForest, DecisionTrees, and LogisticRegression for Credit Card Default

For this project, three Classifiers are compared when trained a Credit Card Defaulting dataset. The classifiers are:

1) Logistic Regression

2) Random Forest 

3) Decision Trees

## Dataset and Library
Scikit Learn's and PySpark's LogisticRegression, RandomForestClassifier, and DecisionTreeClassifier classes were used create each model.
The dataset consisted of 30000 rows by 24 columns of client information and payment history, including the label which was the whether they defaulted on the next payment or not. However, the label is unbalanced with 23364 cases of payment and 6636 cases of defaulting.

Please find the dataset from the University of California Irvine's Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

## Results
The Logistic Regression and Random Forest models both had similar results at 81% and 82% accuracies overall. Decision tree performed the worst, especially when predicting the clients that defaulted payments at 38% precision. Similarly, both Random Forest and Logistic Regression had worse precision for predicting defaulting clients as well. However, this may be due to training on an unbalanced dataset. 78% of the labels were for paid clients, whereas 22% were defaulting clients. As such, a more balanced labelled dataset would help improve on the precision for the defaulting classification label.

Please visit the following link for the resulting images: https://hjmok.github.io/josephmok_portfolio/#/CC
