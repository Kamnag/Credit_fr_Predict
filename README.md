Credit-Card-Fraud-Detection

To know more about the dataset please follow the link: https://www.kaggle.com/dalpozz/creditcardfraud
Install:
I am using Python 3.6.1 for this project. You need to install the folowing Python libraries.

NumPy (for documentation:http://www.numpy.org/)
Pandas (for documentation:http://pandas.pydata.org/)
Scikit-Learn (for documentation:http://scikit-learn.org/stable/)
itertools (https://docs.python.org/3/library/itertools.html)
I have been using Jupyter Notebook for this project.

Code:
The code contains in the 'Credit_Fr_Predict.py' file.

Data
The data contains in the 'creditcard.csv' file.

As the file is too big to upload in the repository, to download the file please follow the link below:
creditcard.csv.zip (https://www.kaggle.com/mlg-ulb/creditcardfraud/downloads/creditcard.csv/3)
The above file is in .zip format. Please extract the file to get the .csv file out of it.

Data Description:
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, it's recommended measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.


