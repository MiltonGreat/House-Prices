# House-Prices

### Summary and Recommendations

#### 1. Overview

The goal of this project is to analyze American housing prices using various statistical and machine learning techniques. The dataset includes various features related to housing, and the analysis aims to predict prices based on these features while exploring relationships and trends.

#### 2. Data

A dataset comprising various variables around housing and demographics for the top 50 American cities by population.

Variables:

- Zip Code: Zip code within which the listing is present.
- Price: Listed price for the property.
- Beds: Number of beds mentioned in the listing.
- Baths: Number of baths mentioned in the listing.
- Living Space: The total size of the living space, in square feet, mentioned in the listing.
- Address: Street address of the listing.
- City: City name where the listing is located.
- State: State name where the listing is located.
- Zip Code Population: The estimated number of individuals within the zip code. Data from Simplemaps.com.
- Zip Code Density: The estimated number of individuals per square mile within the zip code. Data from Simplemaps.com.
- County: County where the listing is located.
- Median Household income: Estimated median household income. Data from the U.S. Census Bureau.
- Latitude: Latitude of the zip code. ** Data from Simplemaps.com.**
- Longitude: Longitude of the zip code. Data from Simplemaps.com.

#### 3. Data Analysis Steps

1. Data Exploration and Visualization
2. Data Cleaning
3. Feature Engineering
4. Outlier Removal
5. Data Visualization
6. Evaluation
7. Feature Selection and Correlation Handling
8. Model Building
9. Model Evaluation
10. Visualization of Predictions

#### 4. Data Visualization

- Correlation Matrix Heatmap: Showcases relationships between features.
- Distribution of Housing Prices: Visualizes how prices are spread across the dataset.
- Average Housing Price by Zip Code: Highlights geographical price trends.
- Scatter Plots: Demonstrates relationships between housing prices, living space, and median household income.
- Box Plots: Compares price distributions across different numbers of bedrooms.
- Actual vs. Predicted Prices: Visual comparison of model predictions against actual prices.
- Feature Importance Bar Plot: Displays the significance of each feature in predicting housing prices.

#### 5. Key Findings
      
Model Performance:

- The Random Forest model significantly outperformed the Linear Regression model, achieving a low Mean Absolute Error (MAE) of approximately $2,006 compared to $42,728 for Linear Regression.
- The Random Forest model also had a high R-squared score (0.998), indicating that it explains a substantial portion of the variance in housing prices.

Feature Importance:

- 'Price per Sqft' was identified as the most important feature in predicting housing prices, followed by 'Living Space' and 'Median Household Income'.
- Other features like geographic indicators (Zip Code, Latitude, Longitude) and the number of bedrooms also played roles, but their importance was relatively lower.

Outlier Impact:

- The data cleaning steps, especially outlier removal, helped improve model performance and ensured that the analysis was not skewed by extreme values

#### 6.  Source

https://www.kaggle.com/datasets/jeremylarcher/american-house-prices-and-demographics-of-top-cities
