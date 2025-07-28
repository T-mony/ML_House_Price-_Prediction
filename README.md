# ML_House_Price-_Prediction
House Price Prediction
This project aims to predict house prices using a dataset containing various features of houses.

Data
The dataset used in this project is cleaned_house.csv. It contains 1460 observations and 81 features, including the sale price of the house.

Analysis
The analysis involved:

Exploring the data to understand its structure and content.
Handling missing values by filling them with appropriate values based on the feature type.
Visualizing the relationships between different features and the sale price using box plots, histograms, and scatter plots.
Identifying the top 10 most important features for predicting house prices using a Random Forest Regressor model.
Model
A Random Forest Regressor model was used to predict house prices. The model was trained on 80% of the data and tested on the remaining 20%.

RMSE: 29355.29
R^2 Score: 0.8877
These metrics indicate that the model performs reasonably well in predicting house prices.

Feature Importance
The top 10 most important features for predicting house prices were identified as:

OverallQual
GrLivArea
YearBuilt
GarageCars
TotalBsmtSF
1stFlrSF
FullBath
TotRmsAbvGrd
Fireplaces
BsmtFinSF1
These features have the most significant impact on the predicted sale price of a house.
