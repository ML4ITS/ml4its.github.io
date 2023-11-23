+++
title = 'Clustering of PSA Data for Prostate Cancer Risk Classification and Its Explainability (2022)'
date = 2022-10-15T19:17:52+01:00
draft = false
tags = ["Selfsupervised","Healthcare", "Forecasting"]

categories = ["Vanessa A. Tshichold"] # Lead text
description =  "Example article description"
lead = "ETH"
thumbnail = "images/vanessa.png"
post_meta = ["categories", "translations"]
+++

## Abstract
Prostate cancer is the most common malignancy affecting men and thesecond-leading cause of cancer death in the US. To detect and classify the risk of prostate cancer, doctors perform screening of prostate-specific antigen (PSA) levels. In this Thesis we want to improve thisrisk classification with unsupervised machine learning methods, as thelabels of cancer or no cancer may not reflect the truth; given that canceris only considered as such after confirmation by biopsy and thus possi-bly leaving some patients with cancer with the wrong label. We workwith two prostate cancer datasets, one provided by the Furst Medical  ̈Laboratory Norway and one of the PLCO study.The goal of this Thesis is to find unsupervised learning methods todetect patients at higher risk of having or getting prostate cancer be-fore biopsy is done. For this, we focus on four main aspects: First weconcentrate on learning representations of the PSA levels and imple-ment state-of-the-art models. Subsequently we apply clustering to di-vide the patients into cancer and no cancer. As cancer is cancer detectedafter biopsy, we assume no cancer to include several sub-patterns andtherefore we cluster the patients into more than two clusters. These pat-terns can include more high risk patients, i.e. at higher risk of havingprostate cancer. Third, we investigate the impact of different positionalencodings to the time-series and lastly we analyze if adding more in-formation about the patient to the model input improves performance.Combining these ideas, we develop a novel model architecture, basedon the TS-TCC framework.Our results show that unsupervised methods are able to achieve oreven outperform supervised methods. We find that the assumed sub-patterns within the no cancer class exist and we get a F1 score of 0.908with our adapted TS-TCC model architecture, achieving state-of-the-artresults. Overall we presume that the models’ performance highly de-pend on whether these sub-patterns can be detected – whether learnedwithin a representation or found by clustering.To the best of our knowledge, this is the first work using unsuper-vised learning for clustering patients into risk groups of prostate cancerbased on PSA data before biopsy.
