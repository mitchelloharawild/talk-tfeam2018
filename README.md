# fable::TFEAM2018

Slides and resources for Rob Hyndman and Mitchell O'Hara-Wild's talk at the [Timeseries Forecasting and Event Analytics Melbourne Meetup](https://www.meetup.com/Timeseries-Forecasting-and-Event-Analytics-Melbourne-Meetup/events/255450499/).

## Tidy forecasting in R
The forecast package in R is widely used and provides good tools for monthly, quarterly and annual time series. But it is not so well-developed for daily and sub-daily data, and it does not interact easily with modern tidy packages such as dplyr, purrr and tidyr. We will describe our progress in developing the fable package to provide tidy tools for time series forecasting, which interacts seamlessly with tidyverse packages, and provides functions to handle large collections of time series at any frequency.
