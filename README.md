# Module 12 Report

## Overview of the Analysis
The purpose of this analysis is to train and evaluate a model based on loan risk. Using data from a CSV file the model helps to identify the creditworthiness of borrowers. The CSV file provided information regarding loan size, interest rate, borrower income,	debt to income, number of accounts,	derogatory marks, and total debt. With this we can then predict if a loan will be approved. 

To begin I set the loan status as the labels and the remaining columns as the features. Next, I used train_test_split to split the data into train and test sets. This helps to fit the model. From here I used the LogisticRegression. This predicts binary responses using the training data. A confusion matrix was then created to determine the accuracy of my classification model by showing the number of true positives, false positives, true negatives, and false negatives. Lastly the classification report was printed. This shows how well the machine worked based on the classes provided.

## Results
* Accuracy: The weighted average shows the model correctly predicted 99% of the time over the total number of observations.
* Precsision Class 0(healthy loans): Among positive predicitons 100% were correctly predicted.
* Precsision Class 1(high-risk loans): Among positive predicitons 85% were correctly predicted.
* Recall Class 0(healthy loans): 99% of ccorrectly predicted positive observations to all predicted observations for the class.
* Recall Class 1(high-risk loans): 91% of correctly predicted positive observations to all predicted observations for the class.

## Summary
The logistic regression model seemed to perform very well here. It performs best for healthy loans because the precision is higher for the 0's. The accuracy was 92% or higher for all instances so I would recommend this model.
