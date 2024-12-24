**House Price Prediction**
This project aims to predict house prices using machine learning. The dataset contains information about various housing attributes, including geographic features and median house value, which is the target variable. The goal is to predict the median house value based on these features.

Dataset
The dataset used for this project is sourced from Kaggle. You can access it here.
It consists of the following features:
longitude: Longitude of the house
latitude: Latitude of the house
housing_median_age: The median age of the houses
total_rooms: Total number of rooms
total_bedrooms: Total number of bedrooms
population: The population of the area
households: Number of households
median_income: Median income of residents
ocean_proximity: Proximity to the ocean (categorical variable)
median_house_value: The target variable (price of the house)
Project Structure
Data Preprocessing: The dataset undergoes several preprocessing steps, including:

Handling missing values by dropping rows with missing data.
Removing outliers using Interquartile Range (IQR).
Encoding categorical features using label encoding.
Exploratory Data Analysis (EDA): The data is visualized through:

Histograms and bar plots to explore feature distributions.
Scatter plots to analyze relationships between variables.
Heatmaps and correlation plots to understand feature correlations.
Modeling: Various machine learning models are trained to predict the target variable (house prices). The models include:

ElasticNet
Lasso Regression
Ridge Regression
Gradient Boosting Regressor
XGBoost Regressor
Model Evaluation: Each model's performance is evaluated using the R-squared (R²) score, which measures the accuracy of the model in predicting house prices. A bar plot is used to compare model performances.

Residuals and Predictions: Residual plots are created to assess model errors, and predicted vs actual value plots are generated to visually evaluate the model’s predictions.

Feature Importance: The importance of each feature in the model is visualized using XGBoost's feature importance plot.

Classification: The target variable is discretized into two categories (Low, High) to perform classification and assess the model using metrics like the ROC curve.

Key Dependencies
Python 3.x
pandas
numpy
seaborn
matplotlib
scikit-learn
xgboost
