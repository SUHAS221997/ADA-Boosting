Predicting Income Level Using AdaBoost
This repository contains a machine learning project aimed at predicting whether an individual earns more than $50K per year based on their demographic features using the AdaBoost algorithm. The dataset used is the Census Income Dataset (also known as the "Adult" dataset), which contains various features like age, education, marital status, occupation, and more.
AdaBoost (Adaptive Boosting) is an ensemble learning technique that combines the predictions of multiple weak learners (in this case, decision trees) to create a stronger predictive model. The goal is to build a classifier that predicts if a person’s income is above or below $50K based on the features provided.

Dataset

The Census Income Dataset is publicly available and contains demographic information. The target variable is whether a person makes more than $50K per year.
The Dataset contains Rows: 32561 & Columns: 15.

Features:
1. age: Age of the individual
2. workclass: Type of employment (e.g., private, government, self-employed)
3. fnlwgt: Final weight, which is used for weighting in census data
4. education: Highest level of education attained
5. education-num: Number of years of education
6. marital-status: Marital status (e.g., married, single)
7. occupation: Type of occupation (e.g., executive, technician)
8. relationship: Relationship status (e.g., husband, wife, not-in-family)
9. race: Race of the individual
10. sex: Gender of the individual
11. capital-gain: Capital gain in dollars
12. capital-loss: Capital loss in dollars
13. hours-per-week: Average number of hours worked per week
14. native-country: Country of origin (e.g., United States, Mexico)
15. income: The target variable, <=50K or >50K, representing the income group

Objective
The goal of this project is to predict whether an individual’s income is above or below $50K using the AdaBoost classifier. The model leverages Decision Trees as weak learners to boost performance.
