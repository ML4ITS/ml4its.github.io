+++
title = 'Predicting Final Intraday Electricity Prices in the Very Short Term Utilizing Artificial Neural Networks (2020)'
date = 2020-10-15T19:17:52+01:00
draft = true
tags = ["Timeseries","Energy", "Price", "Forecasting", "LSTM"]

categories = ["Simen Ullern", "Vebjørn Przytula Fjeldberrg"] 
description =  "Example article description"
lead = "NTNU"
thumbnail = "images/ullern.png"
post_meta = ["categories", "translations"]
+++

## Abstract
With the growing inclusion of renewable energy sources, developing price models for intraday trading has become an essential task for many market participants in order to optimize the decision-making process. Yet the available literature on the topic has not been keeping up with the pace of increased intraday trading activity. We predict prices in the final hour prior to delivery on the German intraday market, utilizing Deep Learning techniques. This thesis looks into the usage of feed-forward neural networks and recurrent neural networks (LSTM and GRU). Price information from earlier transactions for a given target contract is known to be strong variables for this predictive task. For this study, we also look at how well the models can forecast with merely exogenous effects. We make use of a rich feature set composed of weather forecasts,  and their intraday updated errors, changes in available production capacities, im- balance volumes, and features engineered from the bid-offer curve. That makes  this is a novel study when applying computational intelligence methods for intraday market research. Prices in the final trading hour are known to be very noisy, caused by short-term dynamics. With careful training of the neural networks, we are able to outperform the statistical baselines on linear errors.