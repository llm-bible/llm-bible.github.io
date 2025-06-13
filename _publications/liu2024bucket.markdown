---
layout: publication
title: 'Bucket Pre-training Is All You Need'
authors: Hongtao Liu, Qiyao Peng, Qing Yang, Kai Liu, Hongyan Xu
conference: "Arxiv"
year: 2024
bibkey: liu2024bucket
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.07495'}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated exceptional performance across
various natural language processing tasks. However, the conventional
fixed-length data composition strategy for pretraining, which involves
concatenating and splitting documents, can introduce noise and limit the
model's ability to capture long-range dependencies. To address this, we first
introduce three metrics for evaluating data composition quality: padding ratio,
truncation ratio, and concatenation ratio. We further propose a multi-bucket
data composition method that moves beyond the fixed-length paradigm, offering a
more flexible and efficient approach to pretraining. Extensive experiments
demonstrate that our proposed method could significantly improving both the
efficiency and efficacy of LLMs pretraining. Our approach not only reduces
noise and preserves context but also accelerates training, making it a
promising solution for LLMs pretraining.
