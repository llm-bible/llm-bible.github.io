---
layout: publication
title: 'Dsmoe: Matrix-partitioned Experts With Dynamic Routing For Computation-efficient Dense Llms'
authors: Minxuan Lv, Zhenpeng Su, Leiyu Pan, Yizhe Xiong, Zijia Lin, Hui Chen, Wei Zhou, Jungong Han, Guiguang Ding, Cheng Luo, Di Zhang, Kun Gai, Songlin Hu
conference: "Arxiv"
year: 2025
bibkey: lv2025matrix
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12455'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Model Architecture', 'Pruning', 'Reinforcement Learning']
---
As large language models continue to scale, computational costs and resource
consumption have emerged as significant challenges. While existing
sparsification methods like pruning reduce computational overhead, they risk
losing model knowledge through parameter removal. This paper proposes DSMoE
(Dynamic Sparse Mixture-of-Experts), a novel approach that achieves
sparsification by partitioning pre-trained FFN layers into computational
blocks. We implement adaptive expert routing using sigmoid activation and
straight-through estimators, enabling tokens to flexibly access different
aspects of model knowledge based on input complexity. Additionally, we
introduce a sparsity loss term to balance performance and computational
efficiency. Extensive experiments on LLaMA models demonstrate that under
equivalent computational constraints, DSMoE achieves superior performance
compared to existing pruning and MoE approaches across language modeling and
downstream tasks, particularly excelling in generation tasks. Analysis reveals
that DSMoE learns distinctive layerwise activation patterns, providing new
insights for future MoE architecture design.
