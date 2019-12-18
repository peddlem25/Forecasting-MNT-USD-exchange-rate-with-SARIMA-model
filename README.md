# Forecasting MNT/USD exchange rate

# General
This project aimed at forecasting exchange rate dynamics using SARIMA model. This model forecasts the next 13 months exchange rate dynamics using time-series data extracted from the Bank of Mongolia website.

# Modeling process
Step 1: Data extraction 
Extracted monthly and yearly exchange rate data from the Central Bank of Mongolia website and transformed the data into data-frame.

Step 2: Model selection and estimation
Selected the best SARIMA models based on out-of-sample forecasting mean-squared-error (mse) and chose the model with the smallest mse.

Step 3: Forecasting and plotting the results
Based on the best SARIMA model, forecasted the next 12 months of exchange rate dynamics and plotted 36 months of data. 

## Dependencies

The following libraries need to be installed.

```bash
pip install requests==2.22.0 beautifulsoup4==4.7.1 numpy==1.16.3 pandas==0.24.2 statsmodels==0.10.0 scikit-learn==0.21.2 matplotlib==3.1.0 
```
