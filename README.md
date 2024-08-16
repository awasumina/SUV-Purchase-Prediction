# Customer Purchase Prediction

This project aims to predict customer purchases based estimated salary using a logistic regression model. The dataset used includes user details such as `User ID`, `Gender`, `Age`, `Estimated Salary`, and whether they purchased a product (`Purchased`).

## Dataset

The dataset is a dictionary containing:
- `User ID`: Unique identifier for the user.
- `Gender`: Gender of the user.
- `Age`: Age of the user.
- `Estimated Salary`: Estimated salary of the user.
- `Purchased`: Whether the user purchased the product (1 for yes, 0 for no).


## Code Explanation

1. **Data Preparation**
   - A DataFrame is created from the given dataset.
   - Features (`Age` and `Estimated Salary`) and target variable (`Purchased`) are separated.

2. **Data Splitting**
   - The data is split into training and testing sets using `train_test_split`.

3. **Feature Scaling**
   - Features are scaled using `StandardScaler` to standardize the range of features.

4. **Model Training**
   - A logistic regression model is trained on the scaled training data.

5. **Prediction**
   - The model predicts the target variable on the testing data.

6. **Evaluation**
   - The accuracy of the model is calculated and output as a percentage.


## Results

The logistic regression model achieved an accuracy of approximately 89.6% on the test set.
  
