# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose is to determine and evaluate credit risk by analysing the creditworthiness of borrowers. I do this by analysising and manipulating financial data to build a model that identify 

* Explain what financial information the data was on, and what you needed to predict.
The basic finanical data includes; loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt and existing loan status. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The basic variables included simple value counts for the balance of loan status listed as Healthy Loans or High Risk Loans. Additional variables where loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt and existing loan status. 

* Describe the stages of the machine learning process you went through as part of this analysis.
The key stages of this process include:
 1. Importing the required libraries - eg numpy, pandas, sklearn and imblear.
 2. Reading in the CSV file. 
 3. Preparing the data for analysis. eg. splitting the data into y and X dataframes. 
 4. Creating Logistic Models for Original and Resampled Data
 5. Evaluating the results through the use of confusion matrix and classification reports. 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

Linear regression is a model for describing the relationshoip betweeen a numerical response and one or more variables that explains that response. In formula terms it can simply described as y = a + bX,
where y = dependent variable, a = y intercept, b = slope and X = independent variable. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
   1. Overall accuracy = 95%
   
   2.                   Precision Recall              
     Healthy Loans       1.00      0.99      
     High_Risk Loans     0.85      0.91  
   
     
* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

   1. Overall accuracy = 99%
     
   2.                 Precision Recall
    Healthy Loan       1.00      0.99
    High_Risk Loan     0.84      0.99   
            
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Model 2 was substantially better for overall accuracy - 99% to 95%. However for Precision and Recall the Models are virtually the same. Healthy Loans are predicted equally for both models. The Original Loan data model is slightly better - 85% to 84% - for High Risk Loans. 

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Yes it does. In this scenario I believe it would be more important to predict 1's rather than 0's. As the cost of not missing out on healthy loans would far outweight the cost of managing 
High Risk Loans. Given the accuracy of the models 


If you do not recommend any of the models, please justify your reasoning.
