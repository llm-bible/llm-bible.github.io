---
layout: publication
title: 'Improving Maximum Likelihood Training For Text Generation With Density Ratio Estimation'
authors: Yuxuan Song, Ning Miao, Hao Zhou, Lantao Yu, Mingxuan Wang, Lei Li
conference: "Arxiv"
year: 2020
bibkey: song2020improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2007.06018"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Language Modeling', 'Bias Mitigation', 'Ethics and Bias', 'Applications']
---
Auto-regressive sequence generative models trained by Maximum Likelihood
Estimation suffer the exposure bias problem in practical finite sample
scenarios. The crux is that the number of training samples for Maximum
Likelihood Estimation is usually limited and the input data distributions are
different at training and inference stages. Many method shave been proposed to
solve the above problem (Yu et al., 2017; Lu et al., 2018), which relies on
sampling from the non-stationary model distribution and suffers from high
variance or biased estimations. In this paper, we propose\{\psi\}-MLE, a new
training scheme for auto-regressive sequence generative models, which is
effective and stable when operating at large sample space encountered in text
generation. We derive our algorithm from a new perspective of self-augmentation
and introduce bias correction with density ratio estimation. Extensive
experimental results on synthetic data and real-world text generation tasks
demonstrate that our method stably outperforms Maximum Likelihood Estimation
and other state-of-the-art sequence generative models in terms of both quality
and diversity.
