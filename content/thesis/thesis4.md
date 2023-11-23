+++
title = 'Spatio-Temporal Graph Attention Network for Anomaly Detection in the Telco Domain (2021)'
date = 2021-10-15T19:17:52+01:00
draft = false
tags = ["Timeseries","GNN", "Telco", "Anomaly Detection", "Attention"]

categories = ["Axel Ø. Harstad", "William E. G. Kvaale"] 
description =  "Example article description"
lead = "NTNU"
thumbnail = "images/axel.png"
post_meta = ["categories", "translations"]
+++

## Abstract

In the following pages lies our master’s thesis on how the recent advances in deep learning architectures, namely graph neural networks, can perform unsupervised anomaly detection in the Telecommunications (telco) domain. This work is moti- vated by the need for efficient and accurate anomaly detection in the telco domain, where Key Performance Indicators (KPIs) of base stations are continuously being monitored. Furthermore, network infrastructures are constantly being upgraded, 5G is on its way, and there is an exponential increase of devices and antennas. Thus, it is impractical to achieve robust and dependable anomaly detection re- sults without relying on data-driven models to automate this task. Also, the numerous KPIs constitute multivariate time-series with complex patterns and dependencies that the anomaly detection system should learn to leverage. In order to address this, we build a complete framework for unsupervised anomaly detection, where we investigate the use of Graph Attention Network (GAT), in combination with a forecasting-based and a reconstruction-based model, in addition to a non-parametric thresholding method. Firstly, we verify our frame- work on three commonly-used benchmark datasets within anomaly detection. Secondly, we conduct extensive studies where we 1) analyze GAT’s potential for capturing and exploiting the complex relationships of multivariate time-series in both spatial and temporal dimensions, 2) investigate the impact of combining a forecasting-based and a reconstruction-based model, and 3) verify the effective- ness of the non-parametric thresholding method. Lastly, we employ and evaluate our framework on real-world telco data provided by Telenor.
