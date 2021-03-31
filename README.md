# climate_change

## Introduction

- To serve as the hub for climate-related information, data, and tools, the world bank (WB) created the climate change knowledge portal (CCKP). 
- The portal provides an online platform for access to comprehensive global, regional, and country data related to climate change and development. 
- The CCKP portal provides global data on historical climate, vulnerabilities, and impacts of country, region, and watershed views. 
- Users can evaluate climate-related vulnerabilities, risks, and actions for a particular location on the globe by interpreting climate and climate-related data at different levels of details.


## About Dataset:

- The primary data contains various series names(that could impact temperature) and the statistics from year range 1990 to 2011 for all 233 countries. The other sheets in this data contains information about countries and their regions, series names, their Ids and the source of the series data etc. The data file contains around 13k rows and around 5 megabytes in size.
- The other supportive data contains temperature and rainfall values for all the countries on monthly average statistics from year 1901 to 2016 in four different files.

## AIM:

The aim is to predict the climate changes for next 10 years and find the abnormality in the temperature, rainfall or weather. With using the series impact on the climate for previous years, come up with the predictable solution that can prevent the future unnecessary heavy climate changes. 

### Download the data: 
1) https://datacatalog.worldbank.org/dataset/climate-change-data#__sid=js3
2) https://climateknowledgeportal.worldbank.org/download-data

### ARIMA Model
- An ARIMA model is a class of statistical models for analyzing and forecasting time series data.
- It explicitly caters to a suite of standard structures in time series data, and as such provides a simple yet powerful method for making skillful time series forecasts.

ARIMA is an acronym that stands for AutoRegressive Integrated Moving Average. It is a generalization of the simpler AutoRegressive Moving Average and adds the notion of integration. This acronym is descriptive, capturing the key aspects of the model itself. Briefly, they are:

AR: Autoregression. A model that uses the dependent relationship between an observation and some number of lagged observations.
I: Integrated. The use of differencing of raw observations (e.g. subtracting an observation from an observation at the previous time step) in order to make the time series stationary.
MA: Moving Average. A model that uses the dependency between an observation and a residual error from a moving average model applied to lagged observations.
Each of these components are explicitly specified in the model as a parameter. A standard notation is used of ARIMA(p,d,q) where the parameters are substituted with integer values to quickly indicate the specific ARIMA model being used.

