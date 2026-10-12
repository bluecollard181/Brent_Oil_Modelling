# Brent_Oil_Modelling
Forecasts Brent crude volatility and backtests Value-at-Risk in Python. Compares baselines, GARCH(1,1) and a random forest on 1,195 unseen days: GARCH was most accurate (5.7% lower RMSE) and gave the best-calibrated 95% VaR (61 breaches vs ~60 expected, Kupiec p=0.87). Includes a leverage-effect analysis and a 21-day forecast.
