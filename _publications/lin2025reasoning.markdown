---
layout: publication
title: 'Reasoning Bias Of Next Token Prediction Training'
authors: Pengxiao Lin, Zhongwang Zhang, Zhi-qin John Xu
conference: "Arxiv"
year: 2025
bibkey: lin2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02007"}
tags: ['Ethics and Bias', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Since the inception of Large Language Models (LLMs), the quest to efficiently
train them for superior reasoning capabilities has been a pivotal challenge.
The dominant training paradigm for LLMs is based on next token prediction
(NTP). Alternative methodologies, called Critical Token Prediction (CTP),
focused exclusively on specific critical tokens (such as the answer in Q\&A
dataset), aiming to reduce the overfitting of extraneous information and noise.
Contrary to initial assumptions, our research reveals that despite NTP's
exposure to noise during training, it surpasses CTP in reasoning ability. We
attribute this counterintuitive outcome to the regularizing influence of noise
on the training dynamics. Our empirical analysis shows that NTP-trained models
exhibit enhanced generalization and robustness across various benchmark
reasoning datasets, demonstrating greater resilience to perturbations and
achieving flatter loss minima. These findings illuminate that NTP is
instrumental in fostering reasoning abilities during pretraining, whereas CTP
is more effective for finetuning, thereby enriching our comprehension of
optimal training strategies in LLM development.
