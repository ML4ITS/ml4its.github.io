+++
title = 'Generative Adversarial Networks for Unsupervised Anomaly Detection in Multivariate Time-Series Telecommunications Data (2021)'
date = 2021-10-15T19:17:52+01:00
draft = false
tags = ["Timeseries","GAN", "Telco", "Anomaly Detection"]

categories = ["Sigurd Nybakk Vang"] 
description =  "Example article description"
lead = "NTNU"
thumbnail = "images/sigurd.png"
post_meta = ["categories", "translations"]
+++

## Abstract
In the telecommunications domain, as network infrastructure grows more complex, it is becoming increasingly important to develop systems that are able to automate efficient and accurate anomaly detection. Such systems operate on Key Performance Indicators (KPIs) collected from network base stations, and are vital to alert for possible critical operational incidents in a timely manner. These KPIs are most commonly in the form of multivariate time-series, which are challenging to perform anomaly detection on, as anomalous patterns occurs both as correlations between features, as well as temporal windows. Traditional threshold-based methods are unable to perform well at this task due to the dynamic complexities of these systems, whilst supervised learning methods are unable to take advantage of the large amount of existing data, as it remains unlabeled. Recently, a class of unsupervised generative learning models called Generative Adversarial Networks (GANs) have been shown to successfully model statistical distributions in a way that makes them perform anomaly detection well on images and video. This study attempts to apply these techniques to the multivariate time-series domain. Specifically, the State of the Art in GAN-based timeseries anomaly detection is surveyed, before a selection of them are implemented and evaluated as a part of a proposed 3 part anomaly detection pipeline. Additionally, a novel GAN-based anomaly detection method, called RegGAN, is proposed and evaluated together with the State of the Art methods.  The results of the experiments show that even though the GAN-based meth- ods perform well on benchmark datasets, they have rather severe limitations that are uncovered when applied to the real world telecommunications data. Mainly, that they are highly sensitive to contaminated training data, which degrades performance significantly. They also fail to incorporate temporal patterns beyond  quite short time-horizons. The experiments suggests that adding a auxiliary encoder to the GAN architecture helps mitigate the effect of contamination on  model performance. Furthermore, it is proposed that the use of attention mechanisms and multivariate correlation matrices (MCMs) could increase the GANs ability to utilise temporal patterns.
