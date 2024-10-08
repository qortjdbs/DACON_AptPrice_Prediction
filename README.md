# Seoul & Busan Apartment Price Prediction with Machine Learning

This project focuses on predicting apartment real transaction prices using machine learning algorithms. The model aims to provide accurate price predictions based on historical real estate transaction data, enhancing decision-making for investors, buyers, and other stakeholders in the real estate market.

## Key Features:
- **Data Collection**: The dataset includes historical transaction records, including apartment size, location, year of construction, floor, and transaction prices.
- **Feature Engineering**: Incorporates relevant factors like regional economic indicators, nearby amenities, and transportation options to improve prediction accuracy.
- **Machine Learning Models**: Employs various algorithms such as Linear Regression, Random Forest, and Gradient Boosting Machines (GBM) to predict prices.
- **Model Evaluation**: Evaluates the models based on mean absolute error (MAE), root mean squared error (RMSE), and R-squared to select the best-performing model.
- **Data Visualization**: Provides graphical representations of predicted versus actual prices, feature importance, and other key insights.

## Methodology:
- **Data Preprocessing**: Cleans and prepares the dataset, addressing missing values, scaling numerical features, and encoding categorical variables.
- **Model Training**: Trains multiple models and tunes hyperparameters using grid search and cross-validation to optimize performance.
- **Model Selection**: Compares the performance of various models and selects the one with the best predictive accuracy and lowest error metrics.
- **Prediction**: Uses the selected model to predict future apartment prices based on current data inputs.

## Results:
- **High Accuracy**: The Gradient Boosting Machine model demonstrated the highest accuracy, achieving a low MAE and RMSE while maintaining a strong R-squared value.
- **Key Insights**: Location and apartment size were the most important factors influencing price predictions, followed by proximity to transportation and the age of the building.
- **Visualization**: Clear visualizations of predicted vs actual prices, along with feature importance graphs, provided stakeholders with actionable insights.

## Conclusion:
This apartment price prediction model provides a reliable and accurate way to forecast real estate prices, making it useful for real estate investors, buyers, and financial institutions. Future work will focus on incorporating real-time market data and improving the model’s adaptability to dynamic market conditions.
