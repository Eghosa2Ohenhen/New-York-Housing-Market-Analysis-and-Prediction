# New-York-Housing-Market-Analysis-and-Prediction
![](images/ pexels-jack-gittoes-1274799.jpg)

## About Section:
This project involves analyzing the New York housing market dataset to gain insights into various factors affecting property prices. It includes data cleaning, exploratory data analysis (EDA), visualization, and building predictive models to estimate housing prices.

## Problem Statement:
The project aims to understand the factors influencing housing prices in different areas of New York City and to build predictive models to estimate housing prices based on various property features.

## Tools Used:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express
- Statsmodels
- Scikit-learn

## Analysis Done / Insights:

### Data Cleaning:
We began by examining our dataset to identify missing values and filtering unwanted columns. We aimed to understand the distribution of each variable and explore the relationships between features and the target variable.

### Visualization of top sublocalities by average price and average prices by property type:
The visual highlighted the significant variation in average prices across different property types. Townhouses, houses, and condos tend to have higher average prices compared to other property types. This information can be valuable for individuals interested in understanding the average market prices for various types of properties.

### Iterative analysis including price per square foot and correlation analysis:
- Correlation Matrix:
  The strong positive correlation between Bedrooms and Bathrooms suggests a close relationship, likely influenced by architectural standards or market demands. While a moderate positive correlation exists between Price and Property Size, indicating larger properties tend to have higher prices, other factors like location, amenities, and property condition also significantly influence prices. These correlations provide insights for real estate decisions, but additional factors must be considered for a comprehensive understanding of the market dynamics.

### Model Performance evaluation and comparison:
When comparing the Random Forest Regressor and Linear Regression models in terms of their performance metrics – Mean Squared Error (MSE) and R-squared (R2) – it became evident that the Random Forest model outperforms the Linear Regression model.
The Random Forest Regressor exhibits a significantly lower MSE of approximately 160232385537.55515 and a higher R-squared value of about 0.5764 compared to the Linear Regression model, which has a higher MSE of approximately 187273330264.9731 and a lower R-squared value of about 0.5049.
