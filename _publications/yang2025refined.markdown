---
layout: publication
title: 'Rico: Refined In-context Contribution For Automatic Instruction-tuning Data Selection'
authors: Yixin Yang, Qingxiu Dong, Linli Yao, Fangwei Zhu, Zhifang Sui
conference: "Arxiv"
year: 2025
bibkey: yang2025refined
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05327"}
tags: ['Fine-Tuning', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Data selection for instruction tuning is crucial for improving the performance of large language models (LLMs) while reducing training costs. In this paper, we propose Refined Contribution Measurement with In-Context Learning (RICo), a novel gradient-free method that quantifies the fine-grained contribution of individual samples to both task-level and global-level model performance. RICo enables more accurate identification of high-contribution data, leading to better instruction tuning. We further introduce a lightweight selection paradigm trained on RICo scores, enabling scalable data selection with a strictly linear inference complexity. Extensive experiments on three LLMs across 12 benchmarks and 5 pairwise evaluation sets demonstrate the effectiveness of RICo. Remarkably, on LLaMA3.1-8B, models trained on 15% of RICo-selected data outperform full datasets by 5.42% points and exceed the best performance of widely used selection methods by 2.06% points. We further analyze high-contribution samples selected by RICo, which show both diverse tasks and appropriate difficulty levels, rather than just the hardest ones.
