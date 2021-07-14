# Syria Telecom Analysis

**Author**: Bridget Coleman

## Overview

Syria Tel is a communications company.  A company can expect a certain amount of turnover in custumers.  I examined the percentage of turnover and looked at reasons for why a customer may leave.

## Business Problem

It can be more expensive to get new clients versus retaining current clients.  The question is what makes a customer leave.  Can we predict when a customer is considering changing phone services?  What incentive can we give to make them reconsider?  

## Data

The data has been collected from Kaggle.  The dataset has the information from 3,333 customers.  The dataset has information on the length of account, types of plans, minutes charged, and if they terminated the service. 

## Methods

This project focuses on why a customer may choose to leave a telecommunications company.  A certain amount of turnover is expected.  There was an imbalance to the data.  I used SMOTE to address this issue.

## Models

There were four models that I used to test the training data, Logistic Regression, Decision Tree Classifier, Bagging Classifier, and Random Forest Classifier.  The Decision Tree Classifier provided the best results.


## Results

The customers with the most service calls and total day charges are the ones most likely to leave.  The turnover rate for this company was 15% on average.  When the service calls increased the churn rated increased significantly.


## Next Steps

Test the model on a larger dataset.  

Examine the three states with the highest churn rates.  

Examine the customer service calls.  Is better customer service needed?  Can an incentive be offered after a specific number of calls?

## For More Information

Please review the full analysis in [the Jupyter Notebook](https://github.com/bkcoleman1024/Telecom-Analysis/blob/main/SyriaTelCustomers.ipynb) or [the presentation](https://github.com/bkcoleman1024/Telecom-Analysis/blob/main/Presentation.pdf).

For any additional questions, please contact Bridget Coleman, bkcoleman1024@gmail.com

## Repository Structure


```
├── SyriaTel_README.md                 
├── Telecom_Analysis.ipynb            
├── Project_Presentation.pdf            <- PDF version of project presentation
└── data                                <- Both sourced externally and generated from code

