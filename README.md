# Energy-Forecasting-
Project Title: Energy Consumption Forecasting for Tetouan City

Overview:
This project focuses on predicting energy consumption for Tetouan City using time series forecasting techniques. The goal is to develop accurate models that can provide insights into energy consumption patterns and assist in planning energy distribution efficiently.

# Project Steps:

Data Preprocessing: Cleaned and transformed energy consumption data collected from SCADA systems. Resampled data to daily frequency for analysis.

Exploratory Data Analysis (EDA): Analyzed temperature, humidity, wind speed, and energy consumption trends. Visualized the relationship between weather features and energy consumption.

Time Series Decomposition: Decomposed energy consumption data into its trend, seasonal, and residual components to identify patterns.

Stationarity Check: Performed Augmented Dickey-Fuller (ADF) tests to check for stationarity and applied differencing to make the data stationary.

Modeling - ARIMA: Developed an ARIMA model to forecast energy consumption. Determined optimal hyperparameters using ACF and PACF plots.

Model Evaluation: Evaluated the ARIMA model's performance using metrics like RMSE, MAE, and MAPE.

Visualization: Plotted historical energy consumption, forecasted values, and compared predictions with observed data.

Deployment (Optional): Created a Flask web application for model deployment. Users can input weather features to get energy consumption predictions.

Tools Used:

Python: Primary programming language for data preprocessing, analysis, modeling, and visualization.
Pandas: Data manipulation and transformation.
Matplotlib and Plotly: Data visualization and interactive plots.
Statsmodels: Building and evaluating ARIMA models.
Seaborn: Creating informative visualizations.
Flask: Developing a web application for model deployment.
HTML/CSS: Designing the user interface for the web application.
Heroku (Optional): Cloud platform for deploying the Flask web application.
Outcome:
The project provides valuable insights into energy consumption patterns in Tetouan City and offers accurate energy consumption forecasts. The deployed web application (if applicable) enables users to input weather data and obtain predictions for future energy consumption.

Skills Demonstrated:
Time series analysis, data preprocessing, modeling, visualization, web application development, model deployment.

Impact:
The project demonstrates your ability to analyze time series data, build forecasting models, and even deploy a model through a web application. It showcases your proficiency in handling end-to-end data science tasks and making valuable insights accessible to stakeholders.
