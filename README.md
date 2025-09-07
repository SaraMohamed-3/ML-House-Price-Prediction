# ML-HousePricePrediction
This project compares the performance of Linear Regression and Random Forest Regression models in predicting house prices.
The dataset used is housing.csv, which contains information about California housing such as median income, house age, average number of rooms, and location.

1. Data Preprocessing
Handled missing values
Encoded categorical variables (ocean_proximity) using One-Hot Encoding
Standardized features for Linear Regression (since it is sensitive to feature scales)

3. Model Training
Linear Regression 
Random Forest Regressor

3. Model Evaluation
Models were compared using:
MSE (Mean Squared Error)
MAE (Mean Absolute Error)
R² (Coefficient of Determination)

From the comparison, Random Forest generally outperforms Linear Regression, capturing non-linear relationships better.

How to Run
Clone this repository
Install required dependencies:
pip install pandas numpy scikit-learn seaborn matplotlib
Place housing.csv in the project folder
Run the notebook
