# Machine-Learning---Car-Purchase-Prediction
Car Purchase Prediction - Linear Regression &amp; Logistic Regression

**Overview**

This notebook builds a hybrid vehicle purchase predictor using supervised machine learning. A 1. Linear regression model is trained & 2. Logistic regression model is trained on historical customer data to estimate the probability (as a percentage) that a new customer will buy a hybrid vehicle.

**Dataset**

Two CSV files are used. The training file contains 5 columns: Purchase hybrid vehicle (the target, 0 or 1), plus four customer features — Age, Education, Income, and Vehicle Ownership. The test file has the same four features for new, unseen customers.

**How it works**

Features (X): Age, Education level, Income, and number of vehicles owned — all encoded as numeric values (e.g. age categories 1–5, income on a scale, etc.).
Target (Y): Whether the customer previously purchased a hybrid vehicle (binary: 0 = No, 1 = Yes).

**Model Training:** 

  1st - Linear Regression is fit on the training data. Predictions on new customers are then multiplied by 100 to express them as a percentage likelihood.
  
  2nd - Logistic Regression is fit on the training data. "Buying decision" on new customers are mapped by 0 = "Not immediate Buyer" & 1 = "Potential Buyer".
