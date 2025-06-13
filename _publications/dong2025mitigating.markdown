---
layout: publication
title: 'Longred: Mitigating Short-text Degradation Of Long-context Large Language Models Via Restoration Distillation'
authors: Zican Dong, Junyi Li, Jinhao Jiang, Mingyu Xu, Wayne Xin Zhao, Bingning Wang, Weipeng Chen
conference: "Arxiv"
year: 2025
bibkey: dong2025mitigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.07365'}
  - {name: "Code", url: 'https://github.com/RUCAIBox/LongReD'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Pre-Training']
---
Large language models (LLMs) have gained extended context windows through scaling positional encodings and lightweight continual pre-training. However, this often leads to degraded performance on short-text tasks, while the reasons for this degradation remain insufficiently explored. In this work, we identify two primary factors contributing to this issue: distribution drift in hidden states and attention scores, and catastrophic forgetting during continual pre-training. To address these challenges, we propose Long Context Pre-training with Restoration Distillation (LongReD), a novel approach designed to mitigate short-text performance degradation through minimizing the distribution discrepancy between the extended and original models. Besides training on long texts, LongReD distills the hidden state of selected layers from the original model on short texts. Additionally, LongReD also introduces a short-to-long distillation, aligning the output distribution on short texts with that on long texts by leveraging skipped positional indices. Experiments on common text benchmarks demonstrate that LongReD effectively preserves the model's short-text performance while maintaining comparable or even better capacity to handle long texts than baselines. Our code is available at https://github.com/RUCAIBox/LongReD.
