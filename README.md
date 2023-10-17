# Vehicle Loan Default Prediction


## Description
This data science project aims to predict vehicle loan defaults using the CatBoost. The project achieved superior results compared to automated tools such as Auto-Sklearn, H2O, and AutoGluon, as observed in the Fraud Dataset Benchmark and Applications paper ([arXiv Link](https://arxiv.org/abs/2208.14417)).

## About Dataset
Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default.
A financial institution has hired you to accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments) on the due date. Following Information regarding the loan and loanee are provided:

- Loanee Information (Demographic data like age, income, Identity proof etc.)
- Loan Information (Disbursal details, amount, EMI, loan to value ratio etc.)
- Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.)

Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified which can be further used for minimising the default rates.

## Results

The project achieves the results superior to those obtained with the use of automated tools.

| Approach    | AUC |
|-------------|-----|
|AFD OFI      | 0.673|
|AutoGluon    | 0.669|
|H2O          | 0.67|
|Auto-sklearn | 0.664|
|CatBoost     | **0.678**|

## Links


The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/avikpaul4u/vehicle-loan-default-prediction).

The Jupyter Notebook can also be found on Kaggle [here](https://www.kaggle.com/code/ye2531/vehicle-loan-default-prediction-with-catboost/notebook).
