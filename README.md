Project Title: Forecasting Net Prophet

Studied data about search traffic to see if we can find out if search traffic can help to successfully trade the stock.

Technologies The code is written in Py 3.0. We used Colab to run the program

Installation Guide

!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews

import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
import numpy as np


Find unusual patterns in hourly Google search traffic

Mine the search traffic data for seasonality

Relate the search traffic to stock price patterns

Create a time series model with Prophet

I built the ETF portfolio by using SQL joins to combine all the data for each asset.
Contributors In addtion to me the GW Bootcamp TA, LA, and tutors help me create this project

License The Source code is for educational purposes only and should not be used to make any professional recomendations. Feel free to use for any educational needs