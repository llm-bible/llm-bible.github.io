---
layout: publication
title: '\(\text{r}^2\text{ec}\): Towards Large Recommender Models With Reasoning'
authors: Runyang You, Yongqi Li, Xinyu Lin, Xin Zhang, Wenjie Wang, Wenjie Li, Liqiang Nie
conference: "Arxiv"
year: 2025
bibkey: you2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16994"}
  - {name: "Code", url: "https://github.com/YRYangang/RRec"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Large recommender models have extended LLMs as powerful recommenders via encoding or item generation, and recent breakthroughs in LLM reasoning synchronously motivate the exploration of reasoning in recommendation. Current studies usually position LLMs as external reasoning modules to yield auxiliary thought for augmenting conventional recommendation pipelines. However, such decoupled designs are limited in significant resource cost and suboptimal joint optimization. To address these issues, we propose \name, a unified large recommender model with intrinsic reasoning capabilities. Initially, we reconceptualize the model architecture to facilitate interleaved reasoning and recommendation in the autoregressive process. Subsequently, we propose RecPO, a corresponding reinforcement learning framework that optimizes \name\ both the reasoning and recommendation capabilities simultaneously in a single policy update; RecPO introduces a fused reward scheme that solely leverages recommendation labels to simulate the reasoning capability, eliminating dependency on specialized reasoning annotations. Experiments on three datasets with various baselines verify the effectiveness of \name, showing relative improvements of 68.67% in Hit@5 and 45.21% in NDCG@20. Code available at https://github.com/YRYangang/RRec.
