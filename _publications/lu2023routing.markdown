---
layout: publication
title: Routing To The Expert\: Efficient Reward-guided Ensemble Of Large Language Models
authors: Lu Keming, Yuan Hongyi, Lin Runji, Lin Junyang, Yuan Zheng, Zhou Chang, Zhou Jingren
conference: "Arxiv"
year: 2023
bibkey: lu2023routing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08692"}
tags: ['Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The complementary potential of Large Language Models (LLM) assumes off-the-shelf LLMs have heterogeneous expertise in a wide range of domains and tasks so that an ensemble of LLMs can achieve consistently better performance. Existing ensemble methods for LLMs mainly focus on reward model ranking of outputs leading to significant computation overhead. To combat this issue we revisit the complementary potential of LLMs and further elaborate it by mining latent expertise with off-the-shelf reward models. We propose Zooter a reward-guided routing method distilling rewards on training queries to train a routing function which can precisely distribute each query to the LLM with expertise about it. We also integrate a tag-based label enhancement to mitigate noise from uncertainty when using rewards as silver supervision. Zooter shows computation efficiency in inference as it introduces only a minor computation overhead of a routing function compared with reward model ranking methods. We evaluate Zooter on a comprehensive benchmark collection with 26 subsets on different domains and tasks. Zooter outperforms the best single model on average and ranks first on 4437; of tasks even surpassing multiple reward model ranking methods.
