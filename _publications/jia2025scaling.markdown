---
layout: publication
title: 'Scaling Up On-device Llms Via Active-weight Swapping Between DRAM And Flash'
authors: Fucheng Jia, Zewen Wu, Shiqi Jiang, Huiqiang Jiang, Qianxi Zhang, Yuqing Yang, Yunxin Liu, Ju Ren, Deyu Zhang, Ting Cao
conference: "Arxiv"
year: 2025
bibkey: jia2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08378"}
tags: ['Tools', 'Efficiency and Optimization', 'Distillation', 'Reinforcement Learning']
---
Large language models (LLMs) are increasingly being deployed on mobile
devices, but the limited DRAM capacity constrains the deployable model size.
This paper introduces ActiveFlow, the first LLM inference framework that can
achieve adaptive DRAM usage for modern LLMs (not ReLU-based), enabling the
scaling up of deployable model sizes. The framework is based on the novel
concept of active weight DRAM-flash swapping and incorporates three novel
techniques: (1) Cross-layer active weights preloading. It uses the activations
from the current layer to predict the active weights of several subsequent
layers, enabling computation and data loading to overlap, as well as
facilitating large I/O transfers. (2) Sparsity-aware self-distillation. It
adjusts the active weights to align with the dense-model output distribution,
compensating for approximations introduced by contextual sparsity. (3) Active
weight DRAM-flash swapping pipeline. It orchestrates the DRAM space allocation
among the hot weight cache, preloaded active weights, and computation-involved
weights based on available memory. Results show ActiveFlow achieves the
performance-cost Pareto frontier compared to existing efficiency optimization
methods.
