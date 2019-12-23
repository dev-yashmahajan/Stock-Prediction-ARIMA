# Stock-Prediction-ARIMA

This project aims to explore the application of machine learning in the world of Finance, where the data is highly time sensitive and prone to various factors revolving around the economy.  The project focuses on currently used model Auto-Regressive Integrated Moving Average(ARIMA).

### ARIMA (AutoRegressive Integrated Moving Average)
The acronym of ARIMA stands for :
AutoRegressive = the model takes advantage of the connection between a predefined number of lagged observations and the current one.
Integrated = differencing between raw observations (eg. subtracting observations at different time steps).
Moving Average = the model takes advantage of the relationship between the residual error and the observations.
The ARIMA model makes use of three main parameters (p,d,q). These are:
p = number of lag observations.
d = the degree of differencing.
q = the size of the moving average window.
ARIMA can lead to particularly good results if applied to short time predictions 

### Usage

This repo requires [Python](https://www.python.org/) 3+ to run. It also requires the [Keras](https://keras.io/), [Scikit-learn](https://scikit-learn.org/stable/), [Matplotlib](https://matplotlib.org/), [Pandas](https://pandas.pydata.org/), [numpy](https://numpy.org/) to work.

Install the libraries as.

```sh
$ conda install keras
$ conda install scikit-learn
$ conda install matplotlib
$ conda install pandas
$ conda install numpy
```

Run the code using [Jupyter Notebook](https://jupyter.org/).
