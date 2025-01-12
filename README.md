# Vintage-Predictions-Analyzing-and-Forecasting-20th-Century-Wine-Sales-for-ABC-Estate-Wines
Project Based on Time Series Foreasting 
## Project Overview#
	This project focuses on the analysis and forecasting of wine sales trends for the 20th century, utilizing historical sales data from ABC Estate 	Wines. The goal is to extract actionable insights that can enhance sales performance and inform strategic decision-making.
## Data Description
	The dataset includes sales figures for two distinct types of wines:
	Sparkling Wine
	Rosé Wine
## Project Steps
	Data Preparation
		Load the data as time series.
		Conduct Exploratory Data Analysis (EDA) including visualizations and decomposition.
		Handle missing values and split the dataset into training and test sets (test set starts in 1991).
	Model Building
		Develop various forecasting models:
			Linear Regression
			Simple Average
			Moving Average
			Exponential Smoothing (Single, Double, Triple)
	Evaluate model performance using Root Mean Square Error (RMSE).
		Stationarity Check
		Assess the stationarity of the data.
		Apply transformations to achieve stationarity if necessary.
	ARIMA/SARIMA Modeling
		Generate ACF and PACF plots to identify AR and MA values.
		Build both Auto and Manual ARIMA/SARIMA models.
		Evaluate model performance on the test set.
	Model Comparison
		Compare all models based on performance metrics.
		Select the best-performing model and retrain it on the entire dataset.
		Forecast sales for the next 12 months.
	Insights & Recommendations
		Summarize key findings and provide actionable recommendations for ABC Estate Wines.
## Conclusion
	This project aims to leverage historical data to provide insights into wine sales trends, ultimately assisting ABC Estate Wines in optimizing their 	sales strategies for future growth.
