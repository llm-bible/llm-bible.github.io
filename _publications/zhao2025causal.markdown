---
layout: publication
title: 'Nextquill: Causal Preference Modeling For Enhancing LLM Personalization'
authors: Xiaoyan Zhao, Juntao You, Yang Zhang, Wenjie Wang, Hong Cheng, Fuli Feng, See-kiong Ng, Tat-seng Chua
conference: "Arxiv"
year: 2025
bibkey: zhao2025causal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02368"}
  - {name: "Code", url: "https://github.com/juntaoyou/NextQuill"}
tags: ['Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Personalizing large language models (LLMs) for individual users has become increasingly important as they are progressively integrated into real-world applications to support users' daily lives. However, existing personalization approaches often fail to distinguish which components of model predictions and training data truly reflect user preferences, leading to superficial personalization alignment. In this paper, we introduce NextQuill, a novel LLM personalization alignment framework grounded in causal preference modeling. We approach personalization from a causal perspective, treating both model predictions and ground-truth data generation as outcomes influenced by user preferences, along with other factors. We define the true preference effect as the causal impact of user history (which reflects preferences) on each token prediction or data generation instance, estimated through causal intervention techniques. Building on this insight, NextQuill introduces two complementary alignment strategies: (1) aligning model-internal causal preference effects on predictions with those reflected in ground-truth data, rather than indiscriminately fitting predictions, and (2) focusing on fitting preference-bearing tokens identified via ground-truth data preference effects, rather than treating all tokens uniformly. By integrating these strategies, NextQuill shifts the alignment process toward learning from causal preference effects, facilitating more effective and personalized adaptation. Experiments across multiple personalization benchmarks demonstrate that NextQuill significantly improves personalization quality, offering a principled, causal foundation for LLM personalization. Our codes are available on https://github.com/juntaoyou/NextQuill.
