# Data Science Assesment by Assembly

Application written in Python. Using Plotly and Matplotlib for Dashbaord. Using Auto ARIMA and XGBoost Regressor for Model Building

This app uses my knowledge of parquet files, Plotly and Matplotlib for dashboard building, statistics ARIMA and XGBoost Regressor to create a system forecast the number of trips per hour, and MMM to uncover which variables to use to impact the success of the future campaigns.

The data from the parquet file is added to Pandas Dataframe. 

Statistical calculations are performed on the data to provide the information about green_tripdata_2016-02. Stats include:

- Total Number of Rows and Columns
- The Average Trip Distance per time of the Day
- The Median Trip Distance per time of the Day
- The Average Trip Distance per day of the week
- Most Popular Locations During Weekdays
- Most Popular Locations During Weekends
- The Average Trip Duration and its Median
- Installing the Library required
- Splitting the dataset into train and test dataset
- Using Adfuller for Stationary Testing
- Using AIC to select the p, q, d for Auto ARIMA
- Forecasting the number of trips per hour using AUTO-ARIMA
- Using R2 and MAPE as Metrics for Best Result
- Forecasting the number of trips per hour using XGBoost Regressor
- Using R2 and MAPE as Metrics for Best Result and comparsion
---

## Technology Used

- [Python](https://www.python.org/) Programming language that lets you work quickly
and integrate systems more effectively. ([docs](https://docs.python.org/3/))
- [Auto ARIMA](https://pypi.org/project/pmdarima/) Library used for Auto ARIMA is a statistical library designed to fill the void in Python's time series analysis capabilities
- [Plotly]([https://www.sqlalchemy.org/](https://plotly.com/python/getting-started/)) The plotly Python library is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases.
- [XGBoost](https://pypi.org/project/xgboost/) XGBoost is used for supervised learning problems, where we use the training data (with multiple features) 
 to predict a target variable. 
- [parquet](https://coralogix.com/blog/parquet-file-format/#:~:text=Parquet%20file%20format%20is%20a,such%20as%20CSV%20or%20JSON.) fParquet file format is a structured data format that requires less storage space and offers high performance, compared to other unstructured data formats such as CSV or JSON. 
- [statsmodels](https://www.statsmodels.org/stable/index.html) Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration. 
---

## Run the app

Clone this repo then `cd Data-Science-Assesment`, or Open in Colab

Assuming you have Python3 installed on a MacOS, run these commands (or something similar):


---

