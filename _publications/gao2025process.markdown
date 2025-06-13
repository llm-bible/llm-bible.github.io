---
layout: publication
title: 'Process-supervised LLM Recommenders Via Flow-guided Tuning'
authors: Chongming Gao, Mengyao Gao, Chenxiao Fan, Shuai Yuan, Wentao Shi, Xiangnan He
conference: "Arxiv"
year: 2025
bibkey: gao2025process
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07377"}
  - {name: "Code", url: "https://github.com/MrPeach0301/Flower"}
tags: ['Fine-Tuning', 'Tools', 'Ethics and Bias', 'Bias Mitigation', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Fairness']
---
While large language models (LLMs) are increasingly adapted for recommendation systems via supervised fine-tuning (SFT), this approach amplifies popularity bias due to its likelihood maximization objective, compromising recommendation diversity and fairness. To address this, we present Flow-guided fine-tuning recommender (Flower), which replaces SFT with a Generative Flow Network (GFlowNet) framework that enacts process supervision through token-level reward propagation. Flower's key innovation lies in decomposing item-level rewards into constituent token rewards, enabling direct alignment between token generation probabilities and their reward signals. This mechanism achieves three critical advancements: (1) popularity bias mitigation and fairness enhancement through empirical distribution matching, (2) preservation of diversity through GFlowNet's proportional sampling, and (3) flexible integration of personalized preferences via adaptable token rewards. Experiments demonstrate Flower's superior distribution-fitting capability and its significant advantages over traditional SFT in terms of accuracy, fairness, and diversity, highlighting its potential to improve LLM-based recommendation systems. The implementation is available via https://github.com/MrPeach0301/Flower
