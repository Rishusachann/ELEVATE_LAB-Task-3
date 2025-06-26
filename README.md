# ELEVATE_LAB-Task-3

### 📝 Short Note on the Working of the Task

This task involves building a **Linear Regression model** to predict house prices using a dataset (`Housing.csv`). The process begins with importing necessary libraries and reading the dataset. Categorical features like "yes"/"no" values are converted into binary format (1 and 0) to make the data suitable for machine learning.

After preprocessing, the data is split into training and testing sets. A **Linear Regression model** is trained on the training data using `sklearn`. Predictions are made on the test data, and model performance is evaluated using metrics such as **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**, and **R² Score**.

Finally, a scatter plot is created to compare actual vs predicted prices, helping visualize the model’s accuracy.
