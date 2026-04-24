# Machine-Learning-Assessment
📌 Project Overview
This project focuses on predicting house prices using various machine learning regression algorithms. The goal is to build a model that can accurately estimate continuous house values based on features like the number of bedrooms, bathrooms, and square footage.

📊 Dataset
The dataset used is the House Sales in King County, USA (often referred to as the KC House Data). It includes homes sold between May 2014 and May 2015.

Key Features:

price: Sale price (Target Variable)

bedrooms: Number of bedrooms

bathrooms: Number of bathrooms

sqft_living: Square footage of the interior living space

floors: Number of floors

yr_built: The year the house was initially built

🛠️ Workflow
1. Data Loading and Preprocessing
Loading: Data is imported using pandas.

Cleaning: Checked for missing values and duplicates.

Scaling: Applied standard scaling to normalize feature ranges.

Outliers: Used boxplots to identify and handle extreme values in features like sqft_living.

2. Exploratory Data Analysis (EDA)
Histograms: To visualize the distribution of house prices (checking for skewness).

Scatter Plots: To explore relationships between price and living area.

Heatmap: To identify correlations between numerical features.

3. Model Building
We implemented and compared three regression algorithms:

Linear Regression: A baseline model that assumes a linear relationship between features and price.

Decision Tree Regressor: A non-linear model that splits data into branches to make predictions.

Random Forest Regressor: An ensemble method that combines multiple decision trees to improve accuracy and reduce overfitting.

4. Model Evaluation
The models were evaluated using the following metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score (Coefficient of Determination)

🚀 Results & Conclusion
Based on the evaluation metrics, the Random Forest Regressor typically performed the best, providing the highest R² score and lowest error rates compared to simple Linear Regression. This indicates that house prices are influenced by complex, non-linear interactions between features.
