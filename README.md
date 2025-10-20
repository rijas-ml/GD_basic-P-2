Linear Regression using Gradient Descent

This project implements  Linear Regression from scratch  using the  Gradient Descent optimization algorithm.  
It trains a simple model to learn the best slope (m) and intercept (b) that minimize prediction error.



Objective

To understand how Gradient Descent iteratively updates model parameters to fit data,  without using libraries like 'sklearn.linear_model'.

 Steps Performed

1. Generated synthetic linear data ('y = 3x + 4 + noise') using NumPy  
2. Split data into train and test sets using 'train_test_split( )  
3. Implemented Gradient Descent manually (no ML libraries)  
4. Trained the model and extracted learned values of m and b  
5. Evaluated performance using:
    Mean Squared Error (MSE)
    R² Score
6. Visualized:
    Predicted vs Actual  (for test data)

 Example Output:

Trained Model:  y = 2.94x + 3.74
MSE:  17.46
R² Score:  79.72%
