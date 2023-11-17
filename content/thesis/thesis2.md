+++
title = 'Deep Learning for Assessing Risk of Prostate Cancer (2022)'
date = 2022-10-15T19:17:52+01:00
draft = true
tags = ["Timeseries","Healthcare", "Forecasting"]

categories = ["Elisa Tedde"] # Lead text
description =  "Example article description"
lead = "PoliTo"
thumbnail = "images/elisa.png"
post_meta = ["categories", "translations"]
+++

## Abstract
Cancer detection is one of the leading research topics in medical science. Whetherit is breast, lung, brain, or prostate cancer, progress is being made to improve theaccuracy and timing of detection. Prostate cancer is the second most commoncancer in men and the sixth leading cause of cancer death among men in the world.Many prostate cancers are indolent and do not result in cancer mortality, evenwithout treatment. However, a significant percentage of prostate cancer patientshave aggressive cancers that rapidly progress to metastatic disease and are oftendangerous. The current diagnostic pathway is based on serum Prostate-SpecificAntigen (PSA) levels. Although PSA screening reduces the spread and death fromcancer, it overdiagnoses some low-risk cancers that may not have caused damage,leading to unnecessary invasive examinations, such as biopsies.Several methods have been proposed in the past, such as studying the evolutionof prostate antigen over time using different velocity formulas, which have oftenled to inconsistent results. Furthermore, the available datasets were small as theycontained at most a few thousand patients.In this thesis, some Deep Learning methods have been applied to time series topredict prostate cancer risk. The main objectives are early diagnosis and reductionof the number of unnecessary biopsies. The dataset I worked on is unique becauseit contains information on more than one million patients who underwent PSAtesting in Norwegian clinics. Several approaches were proposed to deal with theirregularity of the time series, one of the most recurrent problems in clinical data.The first technique was based on regularizing the time series, while the secondadded new features, such as the time distance between visits. The results werecompared using different metrics such as Specificity, Sensitivity and F1score andfinally, the best model was selected. The performance obtained suggests that theproposed methods are promising and can be a helpful tool to support clinicaldecision-making.