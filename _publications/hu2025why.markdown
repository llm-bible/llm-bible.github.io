---
layout: publication
title: 'Why Distillation Can Outperform Zero-rl: The Role Of Flexible Reasoning'
authors: Xiao Hu, Xingyu Lu, Liyuan Mao, Yifan Zhang, Tianke Zhang, Bin Wen, Fan Yang, Tingting Gao, Guorui Zhou
conference: "Arxiv"
year: 2025
bibkey: hu2025why
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21067'}
tags: ['Reinforcement Learning', 'Agentic', 'Efficiency and Optimization', 'Distillation']
---
Reinforcement learning (RL) has played an important role in improving the reasoning ability of large language models (LLMs). Some studies apply RL directly to \textit\{smaller\} base models (known as zero-RL) and also achieve notable progress. However, in this paper, we show that using only 920 examples, a simple distillation method based on the base model can clearly outperform zero-RL, which typically requires much more data and computational cost. By analyzing the token frequency in model outputs, we find that the distilled model shows more flexible reasoning. It uses anthropomorphic tokens and logical connectors much more often than the zero-RL model. Further analysis reveals that distillation enhances the presence of two advanced cognitive behaviors: Multi-Perspective Thinking or Attempting and Metacognitive Awareness. Frequent occurrences of these two advanced cognitive behaviors give rise to flexible reasoning, which is essential for solving complex reasoning problems, while zero-RL fails to significantly boost the frequency of these behaviors.
