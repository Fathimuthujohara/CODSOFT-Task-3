# CODSOFT-Task-3
### Sales Prediction Using Machine Learning

This project demonstrates how to use machine learning techniques in Python to predict future sales based on advertising expenditure and other factors. By leveraging these predictions, businesses can optimize their advertising strategies and maximize sales potential.

#### Steps:

1. **Load and Prepare Data**
    - Load the dataset and prepare it by extracting features and target variables.

2. **Standardize Data**
    - Standardize the features to have zero mean and unit variance.

3. **Train-Test Split**
    - Split the data into training and testing sets.

4. **Hyperparameter Tuning**
    - Use `RandomizedSearchCV` to find the best hyperparameters for the Random Forest model.

5. **Model Evaluation**
    - Evaluate the model using Mean Squared Error and R-squared.

6. **Future Predictions**
    - Prepare new data for future predictions.
    - Standardize the new data using the same scaler fitted on the training data.
    - Use the trained model to predict sales for the new data.
    - Display the predicted sales.
