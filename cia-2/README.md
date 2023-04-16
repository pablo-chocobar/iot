# Auto-ARIMA based speed forecasting of a Football player's speed. 

## Dataset

dataset obtained from [alfheim](https://datasets.simula.no/alfheim/) 

The dataset contains body-sensor traces and corresponding videos from several professional soccer games captured in late 2013 at the Alfheim Stadium in Tromsø,Norway. It contains per-player statistics of the players like position on the ground, direction facing, speed of the player(in m/s), distance covered so far (in metres) and energy spent.

## Dependencies

The following Python libraries are used in this project:

1. `pmdarima`:used for time series forecasting and also helps in creating time series plots.Mainly used because of the auto_arima model available which performs a GridSearchCV-like parameter tuning on the ARIMA hyperparameters.
2. `statsmodels`: Python module that provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration
3. `pandas`: provides fast, flexible, and expressive data structures and tools to manipulate them.
4. `matplotlib`: provides visualisation tools to create plots and charts which I've used to visualize data and model results.
5. `datetime`: The datetime module supplies classes for manipulating dates and times.
