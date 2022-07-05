# A simple Credit Card Fraud detection algorithm using various classification techniques

The data used is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains features V1 to V28 which are the principal components obtained by PCA. The time feature is neglected beacause it is of no use to the model building,the remaining features are the ‘Amount’ feature that contains the total amount of money being transacted and the ‘Class’ feature that contains whether the transaction is a fraud case or not. 

The models used were; 
Decision Tree Classifier
SVM Classifier
Random Forest Classifier 
XGBoost Classifier 
K Nearest Neighbors Classifier 
Logistic Regression

The best model with a 0.999567 Accuracy score and 0.848980 F1 score was the XGBoost Classifier.
