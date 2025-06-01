# EL-Task-3
# Linear Regression on Housing Data

This code demonstrates how to build and evaluate a Linear Regression model using the "Housing.csv" dataset. The aim is to predict housing prices based on several features like area, number of bedrooms, furnishing status, etc.

# Objectives

This code walks through the following key steps in a machine learning pipeline:

1. Import and Preprocess the Dataset 
   - Load the data using pandas  
   - Handle missing values  
   - Convert categorical features to numeric using one-hot encoding

2. Split the Dataset  
   - Divide the dataset into training and testing sets using `train_test_split`  
   - This helps evaluate model performance on unseen data

3. Train a Linear Regression Model  
   - Use `LinearRegression` from scikit-learn to fit a model to the training data  
   - Predict housing prices on the test data

4. Evaluate the Model  
   - Use evaluation metrics like MAE (Mean Absolute Error), MSE (Mean Squared Error), and R² Score  
   - These metrics help understand how well the model is performing

5. Visualize Results and Interpret Coefficients  
   - Plot actual vs predicted prices to assess prediction accuracy visually  
   - Display the coefficients to understand the effect of each feature on housing price

# Tools and Libraries Used

- pandas - For data manipulation  
- numpy - For numerical operations  
- matplotlib - For visualizations  
- scikit-learn - For modeling and evaluation
