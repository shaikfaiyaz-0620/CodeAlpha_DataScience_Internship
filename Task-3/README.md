# Car Price Prediction with Machine Learning

## Project Objective

The objective of this project is to build a machine learning regression model that predicts the selling price of a car based on its available features such as brand, year, present price, kilometers driven, fuel type, seller type, transmission, owner, and car age.

## Dataset

The dataset contains car-related information with the following features:

- Car Name
- Year
- Present Price
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Owner
- Selling Price

A derived feature called **Car Age** was also created using the manufacturing year.

> Note: The selected dataset does not contain separate features for horsepower or mileage, so these features were not artificially introduced into the model.

## Data Preprocessing

The project includes:

- Loading and inspecting the dataset
- Checking dataset information
- Checking missing values
- Generating statistical descriptions
- Checking duplicate records
- Removing duplicate records
- Creating the Car Age feature
- Separating features and target variable
- Identifying categorical and numerical features
- Encoding categorical features using One-Hot Encoding
- Splitting the data into training and testing sets

## Exploratory Data Analysis

The following visualizations were created:

- Selling Price Distribution
- Present Price vs Selling Price
- Year vs Selling Price
- Driven Kilometers vs Selling Price
- Actual vs Predicted Selling Prices

## Machine Learning Model

### Linear Regression

A **Linear Regression** model was used to predict car selling prices.

A Scikit-learn Pipeline was created to combine:

- Categorical feature encoding
- Numerical feature handling
- Linear Regression

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### Model Performance

| Metric | Result |
|---|---:|
| R² Score | Approximately 0.77 |
| MAE | Approximately 1.41 |
| RMSE | Approximately 2.43 |

The Linear Regression model achieved an R² score of approximately **0.77** on the test data.

## Feature Analysis

Coefficient analysis was performed to understand the contribution of different encoded and numerical features to the model predictions.

The top features were identified based on the absolute value of their regression coefficients.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Conclusion

The project successfully demonstrates car price prediction using machine learning.

The data was cleaned and preprocessed, duplicate records were removed, and Car Age was created as a derived feature. Categorical features were encoded using One-Hot Encoding and a Linear Regression model was trained to predict car selling prices.

The model achieved an R² score of approximately **0.77**, with an MAE of approximately **1.41** and an RMSE of approximately **2.43**.

The analysis also demonstrates the relationship between factors such as present price, manufacturing year, driven kilometers, and car selling price.
