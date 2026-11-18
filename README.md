# House Price Prediction
Predicting median house prices in California districts using **linear regression**.

## Problem
Given features of a district (income, house age, rooms, location), predict the median house value.

## Dataset
California Housing dataset, built into scikit-learn (about 20,000 rows).

## Approach
1. Load and explore the data with Pandas
2. Split into 80% training and 20% test data
3. Train a Linear Regression model
4. Evaluate with MAE and R2 on unseen data
5. Visualise actual vs predicted prices

## Results
| Metric | Value |
|--------|-------|
| MAE    | ~0.53 |
| R2     | ~0.58 |

(Replace with the numbers you got.)

## What I learned
- Why we keep a separate test set
- How to read MAE and R2
- Linear regression is a good baseline, but more complex models could do better

## How to run
Click the "Open in Colab" badge above and choose **Runtime > Run all**.

## Tools
Python, Pandas, scikit-learn, Matplotlib
