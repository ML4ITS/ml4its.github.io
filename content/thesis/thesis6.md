+++
title = 'A Deep Learning-Based Method for Regional Wind Power Production Volume Prediction (2020)'
date = 2020-10-15T19:17:52+01:00
draft = true
tags = ["Timeseries","Energy", "Wind", "Forecasting", "CNN"]

categories = ["Erik Liodden"] 
description =  "Example article description"
lead = "NTNU"
thumbnail = "images/liodden.png"
post_meta = ["categories", "translations"]
+++

## Abstract
The aim of this thesis was to predict the wind power production volume of a large geographical region given the Numerical Weather Prediction data (NWP) over the region using deep learning. Accurate production volume predictions is important for power grid balancing, production planning, and price estimation. Having an accurate forecast for the upcoming wind power production volume has become more and more important in the past years due to the fast increasing number of installed wind turbines and installed total production capacity. Due to the physical properties of wind turbines, wind power production has a strong correlation with the current weather system. This motivates a thorough analysis of the weather using the past, current, and upcoming weather as a basis for the volume prediction. However, the highly nonlinearity of the spatial and temporal characteristics of the weather system makes accurate power volume predictions difficult. To address this, this study designes and evaluate a deep learning architecture using techniques that have shown great success on other similar problems. Convolutional Neural Networks, CNNs, have had great success in image classification, and are able to extract spatial relations and information. An extension to CNNs, called 3D convolution, has had success in capturing temporal dependencies in sequences of image-like data. This study found that deep learning methods were able to directly predict the wind power production volume more accurately than other common machine learning methods in 13 out of 20 regions. A hybrid model combining the proposed deep learning architecture for feature generation and a tree-based learning algorithm, LightGBM, for the final power predictions, improved the prediction accuracy in 17 out of 20 regions compared to the LightGBM algorithm trained without these additional features. Future research in applying deep learning to wind power analysis is encouraged to further investigate the possibilities of capturing the spatio-temporal dependencies to improve predictions.