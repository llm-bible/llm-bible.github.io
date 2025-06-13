---
layout: publication
title: 'Marco-o1 V2: Towards Widening The Distillation Bottleneck For Reasoning Models'
authors: Huifeng Yin, Yu Zhao, Minghao Wu, Xuanfan Ni, Bo Zeng, Hao Wang, Tianqi Shi, Liangying Shao, Chenyang Lyu, Longyue Wang, Weihua Luo, Kaifu Zhang
conference: "Arxiv"
year: 2025
bibkey: yin2025marco
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.01461'}
  - {name: "Code", url: 'https://github.com/AIDC-AI/Marco-o1'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods']
---
Large Reasoning Models(LRMs) such as OpenAI o1 and DeepSeek-R1 have shown remarkable reasoning capabilities by scaling test-time compute and generating long Chain-of-Thought(CoT). Distillation--post-training on LRMs-generated data--is a straightforward yet effective method to enhance the reasoning abilities of smaller models, but faces a critical bottleneck: we found that distilled long CoT data poses learning difficulty for small models and leads to the inheritance of biases (i.e. over-thinking) when using Supervised Fine-tuning (SFT) and Reinforcement Learning (RL) methods. To alleviate this bottleneck, we propose constructing tree-based CoT data from scratch via Monte Carlo Tree Search(MCTS). We then exploit a set of CoT-aware approaches, including Thoughts Length Balance, Fine-grained DPO, and Joint Post-training Objective, to enhance SFT and RL on the constructed data. We conduct evaluation on various benchmarks such as math (GSM8K, MATH, AIME). instruction-following (Multi-IF) and planning (Blocksworld), results demonstrate our approaches substantially improve the reasoning performance of distilled models compared to standard distilled models via reducing the hallucinations in long-time thinking. The project homepage is https://github.com/AIDC-AI/Marco-o1.
