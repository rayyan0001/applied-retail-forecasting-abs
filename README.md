# Applied Retail Forecasting Using ETS and ARIMA

This project applies classical time series forecasting techniques to Australian retail 
turnover data, focusing on furniture and household goods retailing in the Northern Territory.

Using monthly ABS data from 1988 to 2022, I compare ETS and ARIMA models,
evaluate their out-of-sample performance, and assess how well each approach
adapts to structural changes such as COVID-19.

## Data
- Source: Australian Bureau of Statistics (ABS), Retail Trade
- Frequency: Monthly
- Period: April 1988 – December 2022
- Series: Furniture, floor coverings, houseware and textile goods retailing (NT)

## Methods
- Exploratory time series analysis
- Box-Cox transformation (Guerrero method)
- STL decomposition
- Stationarity testing (KPSS)
- ETS model selection via AIC and test-set RMSE
- ARIMA identification using ACF/PACF
- 24-month rolling test-set evaluation
- Backtesting against updated ABS releases (2023–2024)

## Key Findings
- ETS models produced more stable and interpretable forecasts
- ARIMA models adapted better to short-term volatility
- ARIMA achieved lower RMSE when compared to real post-sample ABS data
- Model choice depends on whether stability or responsiveness is prioritized

## Reproducibility
Run `analysis.qmd` to reproduce the full analysis.