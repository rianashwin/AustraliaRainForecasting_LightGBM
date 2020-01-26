# AustraliaRainForecasting_LightGBM
Using LightGBM, we attempt to forecast whether or not it rains for certain major cities in Australia

Here's a notebook which attempts to predict whether or not it will rain tomorrow for major cities in Australia.  ( link: https://lnkd.in/fvic9gm ). This dataset, which I found on Kaggle (posted on Kaggle) contains daily weather observations from numerous Australian weather stations. http://www.bom.gov.au/climate/data. Copyright Commonwealth of Australia 2010, Bureau of Meteorology.

In this notebook, we explore LightGBM, another cool model which works well with larger datasets and is faster than the other models use in this example. Note however documentation is limited at time of righting, you will need to experiment as you go.

We also use the usual suspects of classification models and compare the time needed to complete certain phases of training. 

Please have a look - feel free to use this notebook for your own reference too! In possible future iterations of this model, we may consider using lagging features to forecast further into the future.


Kindly note any views expressed are my own.

Credit to the following resources:

(1) https://www.kaggle.com/mlisovyi/lightgbm-hyperparameter-optimisation-lb-0-761

(2) https://www.kaggle.com/lauriandwu/will-it-rain-tomorrow-eda-classification
