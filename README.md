# Resource Usage - Predictive Scheduling

## Notebook Organization

1. [TimeSeries_Models.py](https://github.com/Gauthami25/Predictive-Forecasting/blob/master/TimeSeries_Models.py.ipynb): - Modeling 500 time series using sklearn. Techniques include feature engineering, rolling window averages (smoothing), linear regression, scaled regression, and lasso, and ridge regression to perform feature selection and reduce overfitting.

2. [AWS_DeepAR.py](https://github.com/Gauthami25/Predictive-Forecasting/blob/master/AWS_DeepAR.py.ipynb): AWS Jupyter notebook for Sagemaker DeepAR. Includes code to download and read in data, format into JSON strings, push to S3 bucket, create train a recurrent neural network (RNN), and visualize model predictions. 

3. [Visualize_Initial_Explore.py.ipynb](https://github.com/Gauthami25/Predictive-Forecasting/blob/master/Visualize_Initial_Explore.py.ipynb): - Includes some initial visualizations of data (aggregated and resampled hourly) using python and matplotlb.

4. [Timeseries_FirstLook_1month.py.ipynb](https://github.com/Gauthami25/Predictive-Forecasting/blob/main/Timeseries_FirstLook_1month.ipynb) - Contains code for exploring timeseries from 1 month and 100 VMs. Includes initial models using ARIMA, SARIMAX, Holt-Winters (smoothing), some visualizations, and stationarity tests.
