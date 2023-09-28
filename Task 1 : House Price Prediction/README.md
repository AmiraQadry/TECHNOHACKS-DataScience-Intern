# House Price Prediction
This project aims to predict house prices based on various features such as square footage, number of bedrooms, etc. 
It utilizes machine learning techniques to train a model on historical housing data and uses that  RF model to make predictions on new, unseen data.

# Dataset
The project uses a dataset called [House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data), 
which contains information about houses along with their corresponding prices. The dataset should be in a structured format, such as a CSV file, 
where each row represents a house and each column represents a specific feature (including the target variable, i.e., the house price).

# Model Training
The project employs a regression algorithm to train the model. The chosen algorithm for this project is the Random Forest regression algorithm, 
known for its ability to handle both numerical and categorical features effectively. However, you can experiment with different regression algorithms such as Linear Regression, 
Gradient Boosting Regression, etc., and select the one that provides the best performance for your specific use case.

# Evaluation
The model's performance is evaluated using metrics such as mean squared error (MSE), root mean squared error (RMSE), and R-squared. 
These metrics provide insights into how well the model predicts house prices compared to the actual prices in the testing set.

# Usage
To use this project, follow these steps:

- Ensure you have Python and the necessary libraries installed (e.g., pandas, scikit-learn).
- Prepare your dataset in the appropriate format (e.g., CSV file) with features and the target variable (house prices).
- Update the code to load your dataset by specifying the correct file path.
- Run the code to preprocess the data, train the model, and make predictions.
- Evaluate the model's performance using the provided metrics.

# Dependencies
- Python
- pandas
- scikit-learn
