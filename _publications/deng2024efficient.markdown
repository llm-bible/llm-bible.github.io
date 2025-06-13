---
layout: publication
title: 'Drpruning: Efficient Large Language Model Pruning Through Distributionally Robust Optimization'
authors: Hexuan Deng, Wenxiang Jiao, Xuebo Liu, Jing Li, Min Zhang, Zhaopeng Tu
conference: "Arxiv"
year: 2024
bibkey: deng2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14055"}
  - {name: "Code", url: "https://github.com/hexuandeng/DRPruning"}
tags: ['Efficiency and Optimization', 'Ethics and Bias', 'Applications', 'Pruning', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) deliver impressive results but face challenges from increasing model sizes and computational costs. Structured pruning reduces model size and speeds up inference but often causes uneven degradation across domains, leading to biased performance. To address this, we propose DRPruning, a method that dynamically adjusts the data distribution during training to restore balanced performance across heterogeneous and multi-tasking data. Experiments in monolingual and multilingual settings show that DRPruning surpasses similarly sized models in both pruning and continued pretraining over perplexity, downstream tasks, and instruction tuning. Further analysis demonstrates the robustness of DRPruning towards various domains and distribution shifts. Furthermore, DRPruning can determine optimal reference losses and data ratios automatically, suggesting potential for broader applications. Code and scripts are available at https://github.com/hexuandeng/DRPruning.
