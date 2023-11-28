+++
title = 'About the project'
date = 2023-11-16T16:24:37+01:00
draft = false
sidebar = "right" # Enable sidebar (on the right side) per page

#thumbnail = "images/claudio.jpeg"
#tags = ["about"]
#lead = "Example lead - highlighted near the title" # Lead text
widgets = ["taglist","social"]
description =  "Example article description"
toc= false # Enable Table of Contents for specific page
comments= true # Enable Disqus comments for specific page



#authorbox= true # Enable authorbox for specific page

+++

### Machine Learning for Irregular Timeseries (ML4ITS)
***
###### Project Number: [312062](https://prosjektbanken.forskningsradet.no/en/project/FORISS/312062?Kilde=FORISS&distribution=Ar&chart=bar&calcType=funding&Sprak=no&sortBy=score&sortOrder=desc&resultCount=30&offset=0&Fritekst=ML4ITS)

We are grateful for funding from [The Research Council of Norway](https://www.forskningsradet.no/) within the IKTPLUSS initiative.

***

**Time series** are everywhere. Data recorded from **sensors** in **mobile phones**, **financial data** like accounting figures and **climate indicators** are all examples of time series society and individuals are exposed to daily. Understanding such time series are essential for technological advance and making informed decisions.

Many of these time series are **irregular** in some sense. They may have **missing data**, which may occur if sensors fail, if a person forgets to insert a number in a spreadsheet, or if the phenomenon we are interested in may only be observed at certain points in time. They may also be **very noisy**: for example, using cheap sensors may allow us to get data from more sensors at the expense of the measurement having more noise than when using a more expensive sensor.

The project **Machine Learning for Irregular Time Series (ML4ITS)** addresses some core challenges for irregular time series. In particular, the project develop methodology that handles irregular time series for the following tasks:

- *Forecasting*: predicting the future values of the time series based on current/past data.
- *Imputation/denoising*: creating “clean” data in the scenario there is missing or noisy data
- *Anomaly detection* and *Failure prediction*: knowing which observations are unusual or indicating that a system is in a critical state.
- *Synthetic Data Generation (SDG)*.

The last point addresses the need for creating datasets that are **privacy preserving**. For example, the sensor data on a cell phone may not be anonymous, but it may be possible to create a synthetic dataset that behaves like the original data in a statistical sense that at the same time preserves privacy. Furthermore, the project aims to make **reproducible research** and develop **open source** software that will benefit the research ecosystem.

The project is a collaboration between [Sintef Digital](https://www.sintef.no/en/digital/) and three departments at [NTNU](https://www.ntnu.no/): [Department of Computer Science](https://www.ntnu.edu/idi), [Department of Mathematical Sciences](https://www.ntnu.edu/imf) and [Department of Electronic Systems](https://www.ntnu.edu/ies).

***
