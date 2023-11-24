+++
title = 'Explainable Anomaly Detection using Masked Latent Generative Modeling (2023)'
date = 2023-11-15T19:17:52+01:00
draft = false
tags = ["generative","timeseries", "Anomaly Detection", "XAI"]

categories = ["Daesoo Lee", "Sara Malacarne", "Erlend Aune"] # Lead text
description =  "Example article description"
lead = "arXiv"
thumbnail = "images/XAIAD.png"
post_meta = ["categories", "translations"]
+++

## Abstract
We present a novel time series anomaly detection method that achieves excellent detection accuracy while offering a superior level of explainability. Our proposed method, TimeVQVAE-AD, leverages masked generative modeling adapted from the cutting-edge time series generation method known as TimeVQVAE. The prior model is trained on the discrete latent space of a time-frequency domain. Notably, the dimensional semantics of the time-frequency domain are preserved in the latent space, enabling us to compute anomaly scores across different frequency bands, which provides a better insight into the detected anomalies. Additionally, the generative nature of the prior model allows for sampling likely normal states for detected anomalies, enhancing the explainability of the detected anomalies through counterfactuals. Our experimental evaluation on the UCR Time Series Anomaly archive demonstrates that TimeVQVAE-AD significantly surpasses the existing methods in terms of detection accuracy and explainability.

[[paper]()]
[[arXiv](https://arxiv.org/abs/2311.12550)]
[[github]()]