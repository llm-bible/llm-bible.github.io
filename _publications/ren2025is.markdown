---
layout: publication
title: 'Is Attention Required For Transformer Inference? Explore Function-preserving Attention Replacement'
authors: Yuxin Ren, Maxwell D Collins, Miao Hu, Huanrui Yang
conference: "Arxiv"
year: 2025
bibkey: ren2025is
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21535'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Tools', 'Pruning', 'Multimodal Models', 'Pretraining Methods']
---
While transformers excel across vision and language pretraining tasks, their reliance on attention mechanisms poses challenges for inference efficiency, especially on edge and embedded accelerators with limited parallelism and memory bandwidth. Hinted by the observed redundancy of attention at inference time, we hypothesize that though the model learns complicated token dependency through pretraining, the inference-time sequence-to-sequence mapping in each attention layer is actually ''simple'' enough to be represented with a much cheaper function. In this work, we explore FAR, a Function-preserving Attention Replacement framework that replaces all attention blocks in pretrained transformers with learnable sequence-to-sequence modules, exemplified by an LSTM. FAR optimize a multi-head LSTM architecture with a block-wise distillation objective and a global structural pruning framework to achieve a family of efficient LSTM-based models from pretrained transformers. We validate FAR on the DeiT vision transformer family and demonstrate that it matches the accuracy of the original models on ImageNet and multiple downstream tasks with reduced parameters and latency. Further analysis shows that FAR preserves the semantic token relationships and the token-to-token correlation learned in the transformer's attention module.
