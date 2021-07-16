![image](https://user-images.githubusercontent.com/70072015/125891305-04d87640-d7d5-4699-b07b-bcade08d84c9.png)


# Syria Telecom Analysis

**Author**: Bridget Coleman

## Overview

Syria Tel is a communications company.  A company can expect a certain amount of turnover in custumers.  I examined the percentage of turnover and looked at reasons for why a customer may leave.

## Business Problem

It can be more expensive to get new clients versus retaining current clients.  The question is what makes a customer leave.  Can we predict when a customer is considering changing phone services?  What incentive can we give to make them reconsider?  

## Data

The data has been collected from Kaggle.  The dataset has the information from 3,333 customers.  The dataset has information on the length of account, types of plans, minutes charged, and if they terminated the service. 

## Methods

The models were evaluated based on recall score and confusion matrices.  A false negative could be more costly to the company if customer is predicted to stay but ends up leaving.  

## Models

There were five models that I used to test the training data 
Logistic Regression
K-nearest Neighbors
Decision Tree
Bagged Tree
Random Forest  


## Results

The Bagged Tree model provided the best results.  When the holdout data was used the false negatives were down to 2.2%.  This was down from 3% with the testing data.  This was an improved from the baseline model, Logistic Regression.  The confusion matrix for the Logistic Regression model shows that 4.6% of the predictions result in false negatives.  

![image](https://user-images.githubusercontent.com/70072015/125891048-d4bc5f18-e5bc-48a6-9c6d-0a344c17dfe4.png)

## Next Steps

Test the model on a larger dataset.  

Examine the three states with the highest churn rates.  

Examine the customer service calls.  Is better customer service needed?  Can an incentive be offered after a specific number of calls?

Based on the feature importance chart, total day minutes and having an international plan are factors for churn.

## For More Information

Please review the full analysis in [the Jupyter Notebook](https://github.com/bkcoleman1024/Telecom-Analysis/blob/main/Updated%20SyriaTel.ipynb) or [the presentation](https://github.com/bkcoleman1024/Telecom-Analysis/blob/main/Final%20presentation.pdf).

For any additional questions, please contact Bridget Coleman, bkcoleman1024@gmail.com

images - Fig. 1. Black towers during sunset - Maria Caruso  www.unsplash.com

## Repository Structure


```
├── SyriaTel_README.md                 
├── Telecom_Analysis.ipynb            
├── Project_Presentation.pdf            <- PDF version of project presentation
└── data                                <- Both sourced externally and generated from code

