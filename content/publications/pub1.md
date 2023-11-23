+++
author = "ddd dsdsds"
title = 'Persistence initialization: A novel adaptation of the transformer architecture for time series forecasting (2023)'
date = 2023-11-15T19:17:52+01:00
draft = true
tags = ["forecasting","transformer","timeseries"]

#lead = "Espen Haugsdal, Massimiliano Ruocco" # Lead text
lead = "Applied Intelligence"
categories = ["Espen Haugsdal", "Massimiliano Ruocco"]
description =  "Example article description"
#categories = ["paper", "2023", "Applied Intelligence"]
thumbnail = "images/pitransformer.jpeg"
post_meta = ["categories", "translations"]
+++

## Abstract
Time series forecasting is an important problem, with many real world applications. Transformer models have been successfully applied to natural language processing tasks, but have received relatively little attention for time series forecasting. Motivated by the differences between classification tasks and forecasting, we propose PI-Transformer, an adaptation of the Transformer architecture designed for time series forecasting, consisting of three parts: First, we propose a novel initialization method called Persistence Initialization, with the goal of increasing training stability of forecasting models by ensuring that the initial outputs of an untrained model are identical to the outputs of a simple baseline model. Second, we use ReZero normalization instead of Layer Normalization, in order to further tackle issues related to training stability. Third, we use Rotary positional encodings to provide a better inductive bias for forecasting. Multiple ablation studies show that the PI-Transformer is more accurate, learns faster, and scales better than regular Transformer models. Finally, PI-Transformer achieves competitive performance on the challenging M4 dataset, both when compared to the current state of the art, and to recently proposed Transformer models for time series forecasting.