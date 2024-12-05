# Credit-Card-Fraud-Detection

![credit card](https://github.com/user-attachments/assets/03f74b11-586a-48a6-9114-2eb28c752fbb)

The use of online banking and credit card is increasing day by day. As the usage of credit/debit card or netbanking is increasing, the possibility of many fraud activities is also increasing. There are many incidents are happened in presently where because of lack of knowledge the credit card users are sharing their personal details, card details and one time password to a unknown fake call. And the result will be fraud happened with the account. Fraud is the problem that it is very difficult to trace the fraud person if he made call from a fake identity sim or call made by some internet services. So in this research some supervised methodologies and algorithms are used to detect fraud which gives approximate accurate results. The illegal or fraud activities put very negative impact on the business and customers loose trust on the company. It also affects the revenue and turnover of the company. In this research isolation forest algorithm is applied for classification to detect the fraud activities and the data sets are collected from the professional survey organizations.

# Problem Statement
The problem statement chosen for this project is to predict fraudulent credit card transactions with the help of machine learning models.

In this project, you will analyse customer-level data which has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group.

The dataset is taken from the Kaggle website and it has a total of 2,84,807 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.

Click this DataSet Link 👉 Credit_Card_Fraud_Detection

# Observations:

Random Forest has 93.9% more accurate the logistic regression of 92.9% and SVM of 91.7% and Decision tree of 89.7% and gaussion naive_bayes of 86.7% and KNN of 63.7%.
So overall Random Forest has the highest score 93.8% among all models. And its best parameter is- {'criterion': 'entropy', 'n_estimators': 50}.
We can also improve on this accuracy by increasing the sample size or use deep learning algorithms however at the cost of computational expense.We can also use complex anomaly detection models to get better accuracy in determining more fraudulent cases
