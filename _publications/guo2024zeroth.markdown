---
layout: publication
title: 'Zeroth-order Fine-tuning Of Llms With Extreme Sparsity'
authors: Wentao Guo, Jikai Long, Yimeng Zeng, Zirui Liu, Xinyu Yang, Yide Ran, Jacob R. Gardner, Osbert Bastani, Christopher De Sa, Xiaodong Yu, Beidi Chen, Zhaozhuo Xu
conference: "Arxiv"
year: 2024
bibkey: guo2024zeroth
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.02913'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Fine-Tuning', 'Pre-Training', 'Pretraining Methods']
---
Zeroth-order optimization (ZO) is a memory-efficient strategy for fine-tuning
Large Language Models using only forward passes. However, the application of ZO
fine-tuning in memory-constrained settings such as mobile phones and laptops is
still challenging since full precision forward passes are infeasible. In this
study, we address this limitation by integrating sparsity and quantization into
ZO fine-tuning of LLMs. Specifically, we investigate the feasibility of
fine-tuning an extremely small subset of LLM parameters using ZO. This approach
allows the majority of un-tuned parameters to be quantized to accommodate the
constraint of limited device memory. Our findings reveal that the pre-training
process can identify a set of "sensitive parameters" that can guide the ZO
fine-tuning of LLMs on downstream tasks. Our results demonstrate that
fine-tuning 0.1% sensitive parameters in the LLM with ZO can outperform the
full ZO fine-tuning performance, while offering wall-clock time speedup.
Additionally, we show that ZO fine-tuning targeting these 0.1% sensitive
parameters, combined with 4 bit quantization, enables efficient ZO fine-tuning
of an Llama2-7B model on a GPU device with less than 8 GiB of memory and
notably reduced latency.
