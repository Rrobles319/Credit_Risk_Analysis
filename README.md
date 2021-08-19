# Credit_Risk_Analysis
Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

## Overview
Using the credit card credit dataset from LendingClub, we will also access imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Our goal in this analysis is the application of machine learning to solve a real-world challenge: credit card risk. Resampling is necessary in assessing credit risk as it is an an inherently unbalanced classification problem, as good loans easily outnumber risky loans.

## Results
 The following images and bulleted list describe the balanced accuracy scores and the precision and recall scores of all six machine learning models:

RandomOverSampler Results:
  - Balanced Accuracy Score: .505
  - Precision: 0.99
  - Recall: 0.99
![Nrandomba1](https://user-images.githubusercontent.com/80009944/129771175-4d4bf0fd-8599-4130-a099-4320f2c3fc18.PNG)


SMOTE Results:
  - Balanced Accuracy Score: .654
  - Precision: 0.99
  - Recall: 0.68
![SMOTEBA2](https://user-images.githubusercontent.com/80009944/129771195-d2abcf6f-143d-44d6-bed2-210590b61619.PNG)

UnderSampling Results:
  - Balanced Accuracy Score: .654
  - Precision: 0.99
  - Recall: 0.40
![UnderBA3](https://user-images.githubusercontent.com/80009944/129771209-cf1551da-35a6-4a9e-96b8-e65a0968ce2d.PNG)

SMOTEEN Results:
  - Balanced Accuracy Score: .544
  - Precision: 0.99
  - Recall: 0.57
![Smoteenba4](https://user-images.githubusercontent.com/80009944/129771220-cc36278c-0a6e-4681-abb7-37161e860437.PNG)

BalancedRandomForestResults:
  - Balanced Accuracy Score: .645
  - Precision: 0.99
  - Recall: 0.57
![ENSba5](https://user-images.githubusercontent.com/80009944/129771234-8accc15f-d6f5-4ee6-9cfb-29e9b7b7e633.PNG)

Ensemble Results:
  - Balanced Accuracy Score: .645
  - Precision: 0.99
  - Recall: 0.57
![BA6](https://user-images.githubusercontent.com/80009944/129771478-6c684d0a-c4ec-4b9a-978e-3a23ee4b91b2.PNG)

## Summary
The results of the various machine learning models reveal the pivital relationship between precision and recall. On one hand, high sensitivy means more at high accounts are detected with possible more false postives. High precision indicates that, of the identified accounts, most are in fact high risk, leaving potential for many missed high risk accounts. When focusing specifically on the identfication of high risk accounts, both precision and recall are significantly inconclusive. Thus, none of these 6 models are effective in consistently minimizing the volume of high risk accounts.
































