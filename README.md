# Sunspot Forecasting with Prophet

**Overview**

This project utilizes the Facebook Prophet library to forecast sunspot activity. The datasets include daily, monthly, and yearly sunspot observations. By preprocessing the data, training models, and generating predictions, this project aims to provide insights into future sunspot activity. The results feature visualizations of historical and forecasted data along with evaluation metrics.

**Features**

Support for Multiple Time Units

Works seamlessly with daily, monthly, and yearly datasets.

Dynamically adjusts preprocessing based on the dataset's frequency.

**Preprocessing**

Handles missing values effectively.

Formats time-series data with dynamic frequency adjustments.

**Modeling with Prophet**

Configurable growth options: linear, logistic, and flat.

Custom changepoints and seasonal adjustments using Fourier orders.

**Evaluation Metrics**

Mean Absolute Error (MAE)

Mean Absolute Percentage Error (MAPE)

R² Score

**Visualization**

Displays historical and forecasted sunspot counts.

Includes confidence intervals for predictions.

**Dynamic Configurations**

Easily adjustable forecast periods and model settings.
