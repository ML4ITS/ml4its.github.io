+++
title = 'Vnibcreg: Vicreg with neighboring-invariance and better-covariance evaluated on non-stationary seismic signal time series (2022)'
date = 2022-10-15T19:17:52+01:00
draft = false
tags = ["Selfsupervised","timeseries"]

categories = ["Daesoo Lee", "Erlend Aune", "Nadège Langet", "Jo Eidsvik"] 
description =  "Example article description"
lead = "arXiv"
thumbnail = "images/VNIBCREG.png"
post_meta = ["categories", "translations"]
+++

## Abstract
This paper presents a novel sampling scheme for masked non-autoregressive generative modeling. We identify the limitations of TimeVQVAE, MaskGIT, and Token-Critic in their sampling processes, and propose Enhanced Sampling Scheme (ESS) to overcome these limitations. ESS explicitly ensures both sample diversity and fidelity, and consists of three stages: Naive Iterative Decoding, Critical Reverse Sampling, and Critical Resampling. ESS starts by sampling a token set using the naive iterative decoding as proposed in MaskGIT, ensuring sample diversity. Then, the token set undergoes the critical reverse sampling, masking tokens leading to unrealistic samples. After that, critical resampling reconstructs masked tokens until the final sampling step is reached to ensure high fidelity. Critical resampling uses confidence scores obtained from a self-Token-Critic to better measure the realism of sampled tokens, while critical reverse sampling uses the structure of the quantized latent vector space to discover unrealistic sample paths. We demonstrate significant performance gains of ESS in both unconditional sampling and class-conditional sampling using all the 128 datasets in the UCR Time Series archive.

[[paper]()]
[[arXiv](https://arxiv.org/abs/2204.02697)]
[[github]()]