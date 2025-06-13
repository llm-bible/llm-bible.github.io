---
layout: publication
title: 'Fopru: Focal Pruning For Efficient Large Vision-language Models'
authors: Lei Jiang, Weizhe Huang, Tongxuan Liu, Yuting Zeng, Jing Li, Lechao Cheng, Xiaohua Xu
conference: "Arxiv"
year: 2024
bibkey: jiang2024focal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14164"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'RAG', 'Pruning', 'Attention Mechanism']
---
Large Vision-Language Models (LVLMs) represent a significant advancement
toward achieving superior multimodal capabilities by enabling powerful Large
Language Models (LLMs) to understand visual input. Typically, LVLMs utilize
visual encoders, such as CLIP, to transform images into visual tokens, which
are then aligned with textual tokens through projection layers before being
input into the LLM for inference. Although existing LVLMs have achieved
significant success, their inference efficiency is still limited by the
substantial number of visual tokens and the potential redundancy among them. To
mitigate this issue, we propose Focal Pruning (FoPru), a training-free method
that prunes visual tokens based on the attention-based token significance
derived from the vision encoder. Specifically, we introduce two alternative
pruning strategies: 1) the rank strategy, which leverages all token
significance scores to retain more critical tokens in a global view; 2) the row
strategy, which focuses on preserving continuous key information in images from
a local perspective. Finally, the selected tokens are reordered to maintain
their original positional relationships. Extensive experiments across various
LVLMs and multimodal datasets demonstrate that our method can prune a large
number of redundant tokens while maintaining high accuracy, leading to
significant improvements in inference efficiency.
