# House Price Prediction Project

## Project Structure
- **Data Cleaning and Preprocessing**:
  - Removed or capped outliers in the dataset (e.g., house size and price columns).
  - Imputed missing or extreme values using threshold values.
  
- **Exploratory Data Analysis**:
  - Insights gained from house prices, bedroom and bathroom distribution, and other key factors.
  - Impact of outliers and data cleanliness to ensure robust analysis.

- **Model Development**:
  - A regression model was built to predict house prices.
  - The model achieved an R² value of 0.6905, indicating that 69.05% of the variability in house prices is explained by the model.

## Model Evaluation
The performance of the regression model was evaluated using the following metrics:

- **R² (R-squared)**: 0.6905
  - The R² score measures how well the model explains the variability in the dependent variable (house prices). A score of 0.6905 means that 69.05% of the variation in house prices can be explained by the features included in the model.
  - In other words, 69.05% of the changes in house prices can be predicted based on the independent variables used in the model.

- **Mean Absolute Error (MAE)**:
  - MAE represents the average absolute differences between the predicted and actual house prices. It indicates how far off, on average, the predictions are from the real prices.

- **Mean Squared Error (MSE)**:
  - MSE is the average of the squared differences between the predicted and actual prices. This metric is more sensitive to large errors, which makes it useful for identifying significant outliers.

- **Root Mean Squared Error (RMSE)**:
  - RMSE is the square root of MSE and provides a measure of the model's prediction error in the same units as the dependent variable (house prices). Lower RMSE values indicate better model performance.

## Key Insights
1. **House Prices**: The price range varies significantly from 1.75M to 13.3M, reflecting diverse housing markets and property types.
2. **Bedroom & Bathroom Distribution**: Houses have between 1-6 bedrooms and at least 1 bathroom, representing both small and large properties.
3. **Impact of Outliers**: Outliers in size and price columns affect data analysis. Capping these values leads to clearer insights and improves the model's performance.
4. **Data Cleanliness**: The dataset is clean, with minimal missing data, ensuring more reliable model outcomes.
5. **Factors Influencing Price**: The number of bedrooms and bathrooms, along with other features, are important predictors of house prices.

## How to Run the Project
1. Install the necessary libraries listed in `requirements.txt`.
2. Load the dataset and run the notebook to execute data preprocessing and modeling.
3. Review the model's performance metrics and interpret the insights derived from the analysis.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib

##Future Work
- Experiment with more advanced machine learning models (e.g., Random Forest, XGBoost).
- Perform hyperparameter tuning to further improve model performance.
- Include additional features to increase predictive accuracy.

## Author
- KrystalG
