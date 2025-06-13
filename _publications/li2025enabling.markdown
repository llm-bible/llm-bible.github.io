---
layout: publication
title: 'Mobillm: Enabling LLM Fine-tuning On The Mobile Device Via Server Assisted Side Tuning'
authors: Liang Li, Xingke Yang, Wen Wu, Hao Wang, Tomoaki Ohtsuki, Xin Fu, Miao Pan, Xuemin Shen
conference: "Arxiv"
year: 2025
bibkey: li2025enabling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.20421'}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Quantization', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Model (LLM) at mobile devices and its potential applications
never fail to fascinate. However, on-device LLM fine-tuning poses great
challenges due to extremely high memory requirements and slow training speeds.
Even with parameter-efficient fine-tuning (PEFT) methods that update only a
small subset of parameters, resource-constrained mobile devices cannot afford
them. In this paper, we propose MobiLLM to enable memory-efficient transformer
LLM fine-tuning on a mobile device via server-assisted side-tuning.
Particularly, MobiLLM allows the resource-constrained mobile device to retain
merely a frozen backbone model, while offloading the memory and
computation-intensive backpropagation of a trainable side-network to a
high-performance server. Unlike existing fine-tuning methods that keep
trainable parameters inside the frozen backbone, MobiLLM separates a set of
parallel adapters from the backbone to create a backpropagation bypass,
involving only one-way activation transfers from the mobile device to the
server with low-width quantization during forward propagation. In this way, the
data never leaves the mobile device while the device can remove backpropagation
through the local backbone model and its forward propagation can be paralyzed
with the server-side execution. Thus, MobiLLM preserves data privacy while
significantly reducing the memory and computational burdens for LLM
fine-tuning. Through extensive experiments, we demonstrate that MobiLLM can
enable a resource-constrained mobile device, even a CPU-only one, to fine-tune
LLMs and significantly reduce convergence time and memory usage.
