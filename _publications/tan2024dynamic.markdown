---
layout: publication
title: 'DLO: Dynamic Layer Operation For Efficient Vertical Scaling Of Llms'
authors: Zhen Tan, Daize Dong, Xinyu Zhao, Jie Peng, Yu Cheng, Tianlong Chen
conference: "Arxiv"
year: 2024
bibkey: tan2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11030"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
In this paper, we introduce Dynamic Layer Operations (DLO), a novel approach
for vertically scaling transformer-based Large Language Models (LLMs) by
dynamically expanding, activating, or skipping layers using a sophisticated
routing policy based on layerwise feature similarity. Unlike traditional
Mixture-of-Experts (MoE) methods that focus on extending the model width, our
approach targets model depth, addressing the redundancy observed across layer
representations for various input samples. Our framework is integrated with the
Supervised Fine-Tuning (SFT) stage, eliminating the need for resource-intensive
Continual Pre-Training (CPT). Experimental results demonstrate that DLO not
only outperforms the original unscaled models but also achieves comparable
results to densely expanded models with significantly improved efficiency. Our
work offers a promising direction for building efficient yet powerful LLMs. We
will release our implementation and model weights upon acceptance.
