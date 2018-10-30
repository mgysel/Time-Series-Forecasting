# Introduction

You recently started working for a company as a supply chain analyst that creates and sells video games. Many businesses have to be on point when it comes to ordering supplies to meet the demand of its customers. An overestimation of demand leads to bloated inventory and high costs. Underestimating demand means many valued customers won't get the products they want. Your manager has tasked you to forecast monthly sales data in order to synchronize supply with demand, aid in decision making that will help build a competitive infrastructure and measure company performance. You, the supply chain analyst, are assigned to help your manager run the numbers through a time series forecasting model.

You’ve been asked to provide a forecast for the next 4 months of sales and report your findings.

# Time Series Criteria

The dataset meets the time series dataset criteria because:
- the data is continuous, with monthly sales values from January 2008 to September 2013
- the values are ordered
- the values are equally spaced a month apart
- there is only one value per each month

# Conclusions

ARIMA and ETS Models were both assessed to forecast monthly video game sales for the next four months. Because the ARIMA Model displays a lower MAPE and MASE, the ARIMA Model was used for the forecast.

The next four months of video game sales are predicted to be:
- Oct 2013: $747,868
- Nov 2013: $805,244
- Dec 2013: $578,736
- Jan 2014: $573,014