# Logistic-Regression-using-Scikit-Learn
The provided code snippet demonstrates the use of logistic regression from the scikit-learn library for binary classification. Here's a breakdown of what the code does:

1. **Importing Libraries**: The code begins by importing the necessary libraries, including NumPy for numerical computations and scikit-learn's LogisticRegression class for logistic regression.

2. **Defining Data**: The code defines the feature matrix `X`, which contains six samples with two features each, and the target vector `y`, which contains the corresponding labels for binary classification.

3. **Logistic Regression Model**: An instance of the LogisticRegression class is created as `lr_model`.

4. **Model Training**: The `fit` method of the logistic regression model (`lr_model`) is called with the feature matrix `X` and target vector `y` as arguments. This trains the logistic regression model on the provided data.

5. **Making Predictions**: The `predict` method of the logistic regression model is used to predict the labels for the training data `X`. The predicted labels are stored in the variable `y_pred`.

6. **Evaluating Accuracy**: The code prints the predicted labels (`y_pred`) and calculates the accuracy of the model on the training set using the `score` method of the logistic regression model.

Overall, this code demonstrates how to use scikit-learn to train a logistic regression model for binary classification, make predictions, and evaluate its accuracy on the training data.
