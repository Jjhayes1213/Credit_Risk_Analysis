# Credit Risk Analysos

## Overview of Analysis
This project is working with a peer-to peer lending service, Lending Club.  We are using the credit card data base for this service to determine risk with a machine learning model.  Using the data provided we want to seperate the potential high and credit risks by training and testing samples of the data.

## Results

### Balanced Accuracy Score with Credit Risk Resampling
* 59% balanced accuracy score

### Balanced Accuracy Score with Credit Risk Ensemble
* 79% balanced accuracy score


### Precision Score with Credit Risk Resampling
* 1% high risk precision score
* 100% low risk precision score

### Precision Score with Credit Risk Ensemble
* 3% high risk precision score
* 100% low risk precision score

### Recall Score with Credit Risk Resampling
* 63% high recall score
* 55% low risk recall score

### Recall Score with Credit Risk Ensemble
* 70% high recall score
* 87% low risk recall score


## Summary
The predictions for the Credit Risk ensemble are slightly higher in scores than the Credit Risk resampling.  However I would not recommend using either of these models for commercial use.  We can accurately predict the lendors that would have low risk, however the more valuable information would be to identify those that are high risk.  None of these models have high enough scores to instill confidence in high risk predictions. There's also the concern that with the Balanced Accuracy and Recall Scores are often under 83%.  