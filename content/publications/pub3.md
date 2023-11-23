+++
title = 'Circle Attention: Forecasting Network Traffic by Learning Interpretable Spatial Relationships from Intersecting Circles (2023)'
date = 2023-11-15T19:17:52+01:00
draft = false
tags = ["forecasting","transformer","timeseries"]
#lead = "Espen Haugsdal, Sara Malacarne, Massimiliano Ruocco" # Lead text
lead = "ECML-PKDD 2023"
description =  "Example article description"
author = "Massimiliano Ruocco"
#categories = ["paper", "2023", "ECML-PAKDD"]
categories = ["Espen Haugsdal","Sara Malacarne","Massimiliano Ruocco"]
thumbnail = "images/towers.png"
+++

## Abstract
Accurately forecasting traffic in telecommunication networks is essential for operators to efficiently allocate resources, provide better services, and save energy. We propose Circle Attention, a novel spatial attention mechanism for telecom traffic forecasting, which directly models the area of effect of neighboring cell towers. Cell towers typically point in three different geographical directions, called sectors. Circle Attention models the relationships between sectors of neighboring cell towers by assigning a circle with learnable parameters to each sector, which are: the azimuth of the sector, the distance from the cell tower to the center of the circle, and the radius of the circle. To model the effects of neighboring time series, we compute attention weights based on the intersection of circles relative to their area. These attention weights serve as multiplicative gating parameters for the neighboring time series, allowing our model to focus on the most important time series when making predictions. The circle parameters are learned automatically through back-propagation, with the only signal available being the errors made in the traffic forecasting of each sector. To validate the effectiveness of our approach, we train a Transformer to forecast the number of attempted calls to sectors in the Copenhagen area, and show that Circle Attention outperforms the baseline methods of including either all or none of the neighboring time series. Furthermore, we perform an ablation study to investigate the importance of the three learnable parameters of the circles, and show that performance deteriorates if any of the parameters are kept fixed. Our method has practical implications for telecommunication operators, as it can provide more accurate and interpretable models for forecasting network traffic, allowing for better resource allocation and improved service provision.

