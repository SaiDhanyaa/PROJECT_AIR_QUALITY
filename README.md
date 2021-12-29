# Forecasting Carbon Dioxide Emission level
## Project Overview:
* Designed a Forecasting model which forecasts CO2 emission levels, taking number of years you want to forecast as input.
* Analyzed time series for stationary and used different transformation.
* Implemented different forecasting model like ARIMA, Smoothing techniques like Holt - winter's method etc.
* Compared different model based on MAPE value which were built both on stationary and non - stationary data.
* Deployed model using Streamlit.
* Please visit the PPT provided in this repository for in-depth understanding.
## How to run ?
* Download this project folder.
* Open Anaconda prompt in root project directory and run this command: streamlit run TS.py
* After opening of browser, Upload CO2_dataset.csv provided in the folder.
* Enter the number of years you want to forecast and press enter.
![image](https://user-images.githubusercontent.com/89403336/147632221-b8a57214-7f38-4769-bc48-72e7e7dc5b2f.png)
## Business Problem / Objective:
**To forecast the Carbon Dioxide emission levels for an industry so as the emission levels are within the standard limit, so that the organization can follow the government norms with respect to Carbon Dioxide emission levels.

# Dataset details:
Got dataset from Gap Minder.

# Exploratory Data Analysis:
* Visualized time series data and found data to be non - stationary. 
* Done ADFuller test to cross - check whether data is stationary or not.
* Transformed data to stationary using differencing and decomposing.
# Model Building:
* Done data partition of time series keeping in view that order of must not be disturbed.
* Implemented different forecasting models on both stationary and non - stationary data.
* ![image](https://user-images.githubusercontent.com/89403336/147631988-f2474261-9dea-44a1-a371-cabe7681f577.png)
# Model evaluation and comparison:
* Compared all the models build on basis of MAPE values.
