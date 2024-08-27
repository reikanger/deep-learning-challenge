# Deep Learning Challenge

## Overview
The goal of this deep learning model is to help the nonprofit foundation Alphabet Soup select applicants for funding with the best chance of success in their ventures. The model attempts to predict whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing
Target Variables:
- IS_SUCCESSFUL

Feature Variables:
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS
- ASK_AMT 

Removed Variables (neither targets nor features):
- EIN
- NAME

### Compiling Training and Evaluating the Model

The model did not achieve the target performance, as it only achieved an accuracy of 72.34 percent, and a loss of 55.65 percent.

Steps Taken to Increase Model Performance
- modified cutoff of APPLICATION_TYPE
- modified cutoff of CLASSIFICATION
- modified cutoff of hidden nodes in layer 1
- modified cutoff of hidden nodes in layer 2

## Summary
The model's performance did not meet expectations, reaching an accuracy of 72.34% and a loss of 55.65%. Further analysis, optimization, and trying different models may be necessary to increase the model's effectiveness.
