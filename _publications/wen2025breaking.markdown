---
layout: publication
title: 'Breaking Memory Limits: Gradient Wavelet Transform Enhances Llms Training'
authors: Ziqing Wen, Ping Luo, Jiahuan Wang, Xiaoge Deng, Jinping Zou, Kun Yuan, Tao Sun, Dongsheng Li
conference: "Arxiv"
year: 2025
bibkey: wen2025breaking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.07237'}
tags: ['Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Large language models (LLMs) have shown impressive performance across a range
of natural language processing tasks. However, their vast number of parameters
introduces significant memory challenges during training, particularly when
using memory-intensive optimizers like Adam. Existing memory-efficient
algorithms often rely on techniques such as singular value decomposition
projection or weight freezing. While these approaches help alleviate memory
constraints, they generally produce suboptimal results compared to full-rank
updates. In this paper, we investigate the memory-efficient method beyond
low-rank training, proposing a novel solution called Gradient Wavelet Transform
(GWT), which applies wavelet transforms to gradients in order to significantly
reduce the memory requirements for maintaining optimizer states. We demonstrate
that GWT can be seamlessly integrated with memory-intensive optimizers,
enabling efficient training without sacrificing performance. Through extensive
experiments on both pre-training and fine-tuning tasks, we show that GWT
achieves state-of-the-art performance compared with advanced memory-efficient
optimizers and full-rank approaches in terms of both memory usage and training
performance.
