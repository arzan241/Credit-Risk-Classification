# Credit-Risk-Classification

# Objective of the Analysis 
The purpose of this analysis is to determine a creditworthiness of a client who is looking for a loan approval. It also helps to understand the scope of risk appetite for bad loans and potential profits on good loans.

# Data 

The data included information regarding the client’s income, interest rate, total debts, debt to income ratios etc. This info was used as features in our model. 
The data also had info regarding the status of the loan in two categories of healthy (0) and high risk (1). This info was used as labels in our model. 
Stages of Machine Learning Process and methods 
•	Once the CSV file was loaded the first step was to identify the labels and features.
•	Using the split function, the data was then split into training and testing datasets.
•	The logistic regression model was applied, and the model performance is evaluated under the parameters of accuracy score, confusion matrix and classification report. 
•	This indicates the efficiency of the model to predict healthy and high-risk labels.
•	Second regression model was applied using the resampled data.
•	The model was evaluated with the same parameters while comparing the outcomes from the previous model.

# Results 

Machine learning Model 1
•	Balanced Accuracy Score: 99.24%
•	Precision Score:
o	Healthy Loans: 100%
o	High Risk Loans: 87%
•	Recall Score:
o	Healthy Loans: 100%
o	High Risk Loans: 89%

Machine learning Model 2 
•	Balanced Accuracy Score: 99.52%
•	Precision Score:
o	Healthy Loans: 100%
o	High Risk Loans: 87%
•	Recall Score:
o	Healthy Loans: 100%
o	High Risk Loans: 100%

# Summary 

As per the original test data, the regression model achieves a perfect score under the Healthy loans category. The precision, recall and F1 score are all 100% However, that is not the case under the High-risk loans category. The overall weighted avg between the two categories indicates a 99% score. This might not portrait a completely accurate picture. The model can be trained further to improve/compare the score in the High-risk loan category. 
Even after adding the oversampled data the regression model does a great job under the Healthy loans category by achieving a perfect score. Under the High -risk loans category, the precision score outcome was similar to the previous model 87% . This may indicate a high number of false positives. The recall shows a perfect score which results in the overall F1 to be 93% 
I recommend this model as its overall outcome implied high degree of accuracy in comparison to risks i.e. overall cost of doing business. 
