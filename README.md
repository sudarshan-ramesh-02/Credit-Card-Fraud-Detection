Credit Card Fraud Detection 

Anomal detection on a real world dataset containing history of credit card user transactions classified as valid or fraud. Task is to build a machine learning model which predicts if a test transaction is valid or fraud.

The dataset is highly imbalanced with fraudulent transactions accounting for only 0.17% of recorded transactions. Therefore as a part of Exploratory data analysis, dataset balancing on the training set was performed (ie) up-sampling and down-sampling. One of the objectives of this project was to compare the performance of the model on base data and data after applying these two sampling techniques

A Random Forest Classifier model was used to train the datasets. Various performance metrics such as accuracy score, recall score, precision score, f1 score and confusion matrix were obtained to evaluate the model
