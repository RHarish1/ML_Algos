**Linear Regression Model using Least Squares Method**

This repository contains Python code for implementing a simple linear regression model using the least squares method. The code demonstrates how to fit a linear regression line to a dataset, make predictions, and evaluate the model's performance using coefficient of determination (R^2 score) and mean squared error.

### Contents:
1. **Code File**: `linear_regression.py`
   - This file contains the Python code for implementing linear regression, including functions for fitting the model, making predictions, and evaluating performance.

2. **Dataset**: `File_Name.csv`
   - A sample CSV file containing the dataset with two columns: features (X) and target variable (y). Replace `File_Name.csv` with your dataset file.

### Usage:
1. **Setup Environment**:
   - Ensure you have Python installed on your system along with the necessary libraries: `numpy` and `scikit-learn`.

2. **Clone Repository**:
   - Clone this repository to your local machine using Git:
     ```
     git clone https://github.com/your_username/linear-regression.git
     ```

3. **Run the Code**:
   - Navigate to the cloned repository directory and execute the `linear_regression.py` file:
     ```
     python linear_regression.py
     ```

### Functionality:
- **Model Fitting**: The code fits a linear regression model to the provided dataset using the least squares method.
- **Prediction**: After fitting the model, it makes predictions on both training and testing sets.
- **Evaluation**: The model's performance is evaluated using the coefficient of determination (R^2 score) and mean squared error.

### Customization:
- **Dataset**: Replace `File_Name.csv` with your own dataset file in CSV format.
- **Parameters**: Adjust the test size and random state in the `train_test_split` function for splitting the dataset.

### Contributors:
- This project is maintained by [Your Name](https://github.com/your_username).

### License:
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore, modify, and use the code according to your requirements! If you encounter any issues or have suggestions for improvement, please create an issue or pull request. Happy coding!
