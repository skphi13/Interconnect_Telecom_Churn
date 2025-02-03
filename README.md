# Interconnect Telecom Churn Final Project

In this project, we are provided with a dataset from a company named Interconnect Telecom. The company wants to understand why the customers churned or stopped their service. We will utilize machine learning to identify features of the data that has high predictive power when determining which customers will churn.

## Data Description
`contract.csv` — contract information
`personal.csv` — the client's personal data
`internet.csv` — information about Internet services
`phone.csv` — information about telephone services

## Conclusion
The final model with the highest quality score was a Gradient Boosting model with cross-validation, achieving an AUC-ROC score of **0.89**. Without boosting, the Random Forest model performed well, with an AUC-ROC score of **0.827**.
