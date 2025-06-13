---
layout: publication
title: 'Debiasing CLIP: Interpreting And Correcting Bias In Attention Heads'
authors: Wei Jie Yeo, Rui Mao, Moloud Abdar, Erik Cambria, Ranjan Satapathy
conference: "Arxiv"
year: 2025
bibkey: yeo2025debiasing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17425'}
  - {name: "Code", url: 'https://github.com/wj210/CLIP_LTC'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Multimodal Models', 'Ethics and Bias', 'Pretraining Methods']
---
Multimodal models like CLIP have gained significant attention due to their remarkable zero-shot performance across various tasks. However, studies have revealed that CLIP can inadvertently learn spurious associations between target variables and confounding factors. To address this, we introduce \textsc\{Locate-Then-Correct\} (LTC), a contrastive framework that identifies spurious attention heads in Vision Transformers via mechanistic insights and mitigates them through targeted ablation. Furthermore, LTC identifies salient, task-relevant attention heads, enabling the integration of discriminative features through orthogonal projection to improve classification performance. We evaluate LTC on benchmarks with inherent background and gender biases, achieving over a \\(>50%\\) gain in worst-group accuracy compared to non-training post-hoc baselines. Additionally, we visualize the representation of selected heads and find that the presented interpretation corroborates our contrastive mechanism for identifying both spurious and salient attention heads. Code available at https://github.com/wj210/CLIP_LTC.
