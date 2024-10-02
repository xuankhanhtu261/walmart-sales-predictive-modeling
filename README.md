# Walmart Sales Analysis and Predictive Modeling
## Overview
The dataset used in this project consists of historical sales data from Walmart, including details on weekly sales, the impact of holidays, customer price index, unemployment rate, etc. This project aims to understand the correlation between Walmart sales and different factors and leverage predict modeling to predict sales, evaluating the impact of other factors and providing insights to develop strategies for minimizing costs and maximizing economic impact. 

## Technology Used
- Programming language: Python
- Libraries:
  - Pandas
  - NumPy
  - Seaborn
  - Matplotlit.pylot
  - Sklearn

## Approach
1. Data Preprocessing
- Clean and prepare the dataset for analysis (i.e., converting data formats and creating new columns)

2. Exploratory Data Analysis (EDA)
- Plot the visualization of the features to understand the data trends
- Create a heatmap to visualize correlation matrix to examine the relationship between sales data and different variables
- Plot histograms of the features to understand the distributions

3. Clustering
- Use K-Means clustering to segment stores based on sales data

4. Machine Learning
- Implement regression model and Random Forest model to predict sales and identify key features that influence sales performance

## Key Insights
- 3 clusters might be the optimal number of clusters for this dataset.
- With the use of the Random Forest model to calculate the feature importance, unemployment rate, CPI, and fuel price were found to be the most influential factors in predicting Walmart weekly sales.

## Limitations
- Limited features: The dataset provided only a narrow set of economic factors, missing key variables like promotions, store characteristics, etc.
- Static snapshot: The analysis lacks temporal context, making it difficult to capture seasonal trends and evolving sales patterns over time.
- Weak correlations between variables: The variables used in the model have weak correlations with weekly sales, limiting their predictive power and potentially reducing the model’s overall accuracy.
- Cluster homogeneity: K-Means clusters may contain both high- and low-performing stores due to assumptions about uniformity that may not hold in sales data.
- Potential overfitting: The Random Forest model may risk overfitting to the training data, potentially reducing performance on unseen data.

## Next Steps
- Incorporate addtional features (e.g., regional demographic data)
- Test alternative clustering algorithms
- Apply other models (e.g., time-series models)





