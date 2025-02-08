Support Vector Machine for Credit Card Classification
This project uses the Support Vector Machine (SVM) algorithm to classify credit card applications based on customer data. It works with the Universal Bank Dataset to predict whether a customer is eligible for a credit card or not.

Project Objective
The goal of the project is to predict whether a customer is eligible for a credit card using their data. This is useful for making more customer-oriented decisions and analyzing customer bases in the financial services industry.

Methods Used
Support Vector Machine (SVM):
This model separates data into two classes using a hyperplane. Customer data (age, income, family status, average credit card balance, etc.) is used to determine whether the customer qualifies for a credit card.

Dataset:
The Universal Bank dataset is used, where each customer’s data includes features like income, age, family status, average credit card balance, and more.

Project Steps
Data Preparation:

The data is cleaned and scaled.
Model Building:

Models are built using Linear SVM and Polynomial SVM kernels.
Evaluation:

The model performance is evaluated using metrics such as accuracy, confusion matrix, and others.
Results:

The accuracy and other evaluation results of the model are presented.
Installation and Usage
Required Libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn
