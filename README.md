# learns-time-series-forecasting-on-udacity

## Rough Notes

### Overview

* Prerequisite course: [Problem Solving with Advanced Analytics][]
* [Alteryx][] software
* Exponential smoothing (ETS)
* Autoregressive integrated moving average (ARIMA)

* Trends
* Seasonal patterns
* Cyclical patterns

### ETS Models

#### Introduction

* Exponential smoothing models
* ETS: Error Trend Seasonality
* Each term (in ETS) can be applied additively, multiplicatively, or left out altogether

#### Time series decomposition

A time series decomposition plot separates time series data into seasonal, trend, and error components.

Four components of the plot:

* Time series (the source data)
* Seasonal patterns (seasonal)
* General tendencies (trend)
* Error (error)

#### Identifying Additive or Multiplicative Terms

The _additive_ method is useful when the trend and seasonal variation are relatively constant over time.

The _multiplicative_ method is useful when the trend and seasonal variation increases, or decreases, in magnitude over time.

#### Time Series Scenarios

The possible time series (TS) scenarios can be recognized by asking the following questions:

* TS has a trend?
  - If yes, is the trend increasing linearly or exponentially?
* TS has seasonality?
  - If yes, do the seasonal components increase in magnitude over time?


[Alteryx]: http://www.alteryx.com/
[Problem Solving with Advanced Analytics]: https://www.udacity.com/courses/ud976
