**Hello!**

Implementation of a Time Series for Gross Domestic Product with USA data. Built in R, and using several approches for forecasting:

* Arima with BoxCox Transformation and cleaning process;
* Regression with trend + unemployment variable as predictive feature;
* Auto-ATIMA with trend + unemployment variable as predictive feature;
* Recurrent Neural Network (RNN);
* Regression for time series (TSLM).

**Conclusions**

The best model was the first one in the RMD file. it is a Forecast, applied in ARIMA (2,2,1), built with a set of data after BoxCox transformation and process of cleaning outliers. Its Mean Absolute Percent Error was 12%.

Here you can see a comparing plot with the 3 best models:


<img src="./PRINT_EXAMPLES/image_1.jpeg" height="600" width="300">

