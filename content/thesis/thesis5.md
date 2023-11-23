+++
title = 'Deep Representation Learning for Personalised High Granularity Cycling Performance Prediction (2021)'
date = 2021-10-15T19:17:52+01:00
draft = false
tags = ["Timeseries","Contrastive Learning", "Siamese", "Forecasting", "Sport"]

categories = ["Henrik Fauskanger", "Claus Martinsen"] 
description =  "Example article description"
lead = "NTNU"
thumbnail = "images/henrik.png"
post_meta = ["categories", "translations"]
+++

## Abstract
 Modelling the behaviour and performance of cyclists during competition ahead of time has several useful applications to professional cycling teams. Although existing physics-based approaches perform reasonably well in this regard, they generally require several assumed parameters. Performance is also dependant on several variables which may be hard to quantify, such as a rider’s cornering ability and pacing strategy. The work presented in this thesis is a fully data-driven approach to speed pre- diction in time trials performed by elite cyclists. Inspired by FaceNet [1], siamese neural networks are trained to transform previous efforts of cyclists into a low dimensionality embedding space, clustering embeddings on the rider that per- formed them. Embeddings are used alongside other contextual information as features in a recurrent neural network architecture that is able to predict a rider’s speed along a formerly unseen course. The addition of embeddings allow models to be trained on data from multiple riders and leverage more features without overfitting, resulting in a significant overall increase in predictive performance compared to a similar baseline architecture trained on individual riders.
