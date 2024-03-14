# Machine Learning Projects
**Machine Learning model projects and Dataset regarding sales and ecomeerce forecasting**


## 1. Sales Forecasting using Linear Regression Model -  [Store Sales](https://github.com/acamillemartin/forecasting_projects/blob/c42eb5f9186278b3785319aaa1657de57bcef529/Sales_Forecast_with_Linear_Regression_Model.ipynb)
- Date | Store | Item | Sales

## 2. Website Forecasting using Stats Model / Linear Reg [From GSC Data](https://github.com/acamillemartin/forecasting_projects/blob/c42eb5f9186278b3785319aaa1657de57bcef529/Website%20Forecasting/Website%20Forecasting%20from%20GSC%20Data.ipynb)
- Data | Click | Impressions | CTR | Position

## 3. Linear Regression [Ecommerce Store](https://github.com/acamillemartin/Machine_Learning_Projects/blob/dc20af328045f41b8f7d0ce717462dbe4de43f47/Ecommerce_Customers_Linear_Regression.ipynb)
 - In this file we explore the relationship between 'Avg. Session Length', 'Time on App','Time on Website', 'Length of Membership' and 'Yearly Amount Spent', using linear regression.
 - Give an answer to the company in which they should focus. 

## 4. Time Series Forecasting and EDA [Gold Prices 1950-2020](https://github.com/acamillemartin/Machine_Learning_Projects/blob/144bfb3795a5fa44a140ef5274daf3c006edb32b/Time_Series_Analysis_and_Forecasting_In_Python.ipynb)

### Exploratory Data Analysis (EDA)
I began by exploring the dataset, which contains monthly gold prices ranging from January 1950 to August 2020. Key steps in the EDA process included:
- Checking data types and basic information about the dataset.
- Visualizing the trend in gold prices over time using line plots and boxplots.
- Decomposing the time series into its trend, seasonality, and residual components.
- Analyzing the distribution of gold prices using histograms and boxplots.
- Examining rolling statistics and autocorrelation plots to understand the stationarity and autocorrelation of the time series.
- Visualizing seasonal patterns using a seasonal plot.

### Time Series Forecasting
For time series forecasting, I implemented the following models:
- **Linear Regression:** I split the dataset into training and test sets and trained a linear regression model using the training data. Then made predictions for the test set and calculated Mean Absolute Percentage Error (MAPE).
- **Naive Forecast:** I used a naive forecasting approach where the forecasted value for each time step in the test set is the last observed value from the training set. Calculated MAPE for this model as well.
- **Exponential Smoothing Model:** Finally, I applied the Exponential Smoothing model to the entire dataset and made forecasts for the test set. Were I also calculated MAPE for this model.

### Summary and Conclusion
- The EDA revealed an increasing trend in gold prices over time with noticeable seasonality.
- Linear Regression, Naive Forecasting, and Exponential Smoothing were applied for forecasting future gold prices.
- Linear Regression provided insights into the linear trend in gold prices, while Naive Forecasting served as a baseline model.
- Exponential Smoothing captured both trend and seasonality, providing more accurate forecasts.
- Based on MAPE values, the Exponential Smoothing model outperformed the other two models, indicating its effectiveness in forecasting gold prices.

In conclusion, this project demonstrated the importance of EDA in understanding the underlying patterns in time series data and the effectiveness of different forecasting models in predicting future trends in gold prices.
