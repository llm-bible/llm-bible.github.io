---
layout: publication
title: 'Scaling Laws For Post Training Quantized Large Language Models'
authors: Zifei Xu, Alexander Lan, Wanzin Yazar, Tristan Webb, Sayeh Sharify, Xin Wang
conference: "Arxiv"
year: 2024
bibkey: xu2024scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.12119'}
tags: ['Large-Scale Training', 'Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Scaling Laws', 'Model Architecture', 'Pre-Training']
---
Generalization abilities of well-trained large language models (LLMs) are
known to scale predictably as a function of model size. In contrast to the
existence of practical scaling laws governing pre-training, the quality of LLMs
after post-training compression remains highly unpredictable, often requiring
case-by-case validation in practice. In this work, we attempted to close this
gap for post-training weight quantization of LLMs by conducting a systematic
empirical study on multiple LLM families quantized to numerous low-precision
tensor data types using popular weight quantization techniques. We identified
key scaling factors pertaining to characteristics of the local loss landscape,
based on which the performance of quantized LLMs can be reasonably well
predicted by a statistical model.
