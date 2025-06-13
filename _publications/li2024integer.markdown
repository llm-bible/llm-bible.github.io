---
layout: publication
title: 'Integer Scale: A Free Lunch For Faster Fine-grained Quantization Of Llms'
authors: Qingyuan Li, Ran Meng, Yiduo Li, Bo Zhang, Yifan Lu, Yerui Sun, Lin Ma, Yuchen Xie
conference: "Arxiv"
year: 2024
bibkey: li2024integer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14597"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
We introduce Integer Scale, a novel post-training quantization scheme for
large language models that effectively resolves the inference bottleneck in
current fine-grained quantization approaches while maintaining similar
accuracies. Integer Scale is a free lunch as it requires no extra calibration
or fine-tuning which will otherwise incur additional costs. It can be used
plug-and-play for most fine-grained quantization methods. Its integration
results in at most 1.85x end-to-end speed boost over the original counterpart
with comparable accuracy. Additionally, due to the orchestration of the
proposed Integer Scale and fine-grained quantization, we resolved the
quantization difficulty for Mixtral-8x7B and LLaMA-3 models with negligible
performance degradation, and it comes with an end-to-end speed boost of 2.13x,
and 2.31x compared with their FP16 versions respectively.
