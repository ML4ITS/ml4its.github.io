+++
title = 'Ensemble and Self-supervised Learning for Improved Classification of Seismic Signals from the Åknes Rockslope (2022)'
date = 2022-10-15T19:17:52+01:00
draft = false
tags = ["classification","timeseries", "seismic", "CNN"]

categories = ["Daesoo Lee", "Erlend Aune", "Nadège Langet", "Jo Eidsvik" ] # Lead text
description =  "Example article description"
lead = "Mathematical Geosciences"
thumbnail = "images/seismic.jpeg"
post_meta = ["categories", "translations"]
+++

## Abstract
A case study with seismic geophone data from the unstable Åknes rock slope in Norway is considered. This rock slope is monitored because there is a risk of severe flooding if the massive-size rock falls into the fjord. The geophone data is highly valuable because it provides 1000 Hz sampling rates data which are streamed to a web resource for real-time analysis. The focus here is on building a classifier for these data to distinguish different types of microseismic events which are in turn indicative of the various processes occurring on the slope. There are 24 time series from eight 3-component geophone data for about 3500 events in total, and each of the event time series has a length of 16 s. For the classification task, novel machine learning methods such as deep convolutional neural networks are leveraged. Ensemble prediction is used to extract information from all time series, and this is seen to give large improvements compared with doing immediate aggregation of the data. Further, self-supervised learning is evaluated to give added value here, in particular for the case with very limited training data.

[[paper](https://link.springer.com/article/10.1007/s11004-022-10037-7)]
[[arXiv]()]
[[github]()]