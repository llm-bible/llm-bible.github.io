---
layout: publication
title: 'STEP: Staged Parameter-efficient Pre-training For Large Language Models'
authors: Kazuki Yano, Takumi Ito, Jun Suzuki
conference: "Arxiv"
year: 2025
bibkey: yano2025staged
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04151'}
tags: ['Pre-Training', 'Training Techniques']
---
Pre-training large language models (LLMs) faces significant memory challenges
due to the large size of model parameters. We introduce STaged
parameter-Efficient Pre-training (STEP), which integrates parameter-efficient
tuning techniques with model growth. We conduct experiments on pre-training
LLMs of various sizes and demonstrate that STEP achieves up to a 53.9%
reduction in maximum memory requirements compared to vanilla pre-training while
maintaining equivalent performance. Furthermore, we show that the model by STEP
performs comparably to vanilla pre-trained models on downstream tasks after
instruction tuning.
