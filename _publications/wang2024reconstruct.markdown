---
layout: publication
title: Reconstruct The Pruned Model Without Any Retraining
authors: Wang Pingjie, Fan Ziqing, Hu Shengchao, Chen Zhe, Wang Yanfeng, Wang Yu
conference: "Arxiv"
year: 2024
bibkey: wang2024reconstruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13331"}
tags: ['BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pruning', 'Tools', 'Training Techniques']
---
Structured pruning is a promising hardware45;friendly compression technique for large language models (LLMs) which is expected to be retraining45;free to avoid the enormous retraining cost. This retraining45;free paradigm involves (1) pruning criteria to define the architecture and (2) distortion reconstruction to restore performance. However existing methods often emphasize pruning criteria while using reconstruction techniques that are specific to certain modules or criteria resulting in limited generalizability. To address this we introduce the Linear Interpolation45;based Adaptive Reconstruction (LIAR) framework which is both efficient and effective. LIAR does not require back45;propagation or retraining and is compatible with various pruning criteria and modules. By applying linear interpolation to the preserved weights LIAR minimizes reconstruction error and effectively reconstructs the pruned output. Our evaluations on benchmarks such as GLUE SQuAD WikiText and common sense reasoning show that LIAR enables a BERT model to maintain 9837; accuracy even after removing 5037; of its parameters and achieves top performance for LLaMA in just a few minutes.
