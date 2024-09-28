---
layout: publication
title: Laser Parameter-Efficient LLM Bi-Tuning for Sequential Recommendation with Collaborative Information
authors: Zhang Xinyu, Hu Linmei, Zhang Luhao, Song Dandan, Huang Heyan, Nie Liqiang
conference: "Arxiv"
year: 2024
bibkey: zhang2024laser
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01605"}
tags: ['ARXIV', 'LLM', 'Model Architecture', 'Transformer']
---
Sequential recommender systems are essential for discerning user preferences from historical interactions and facilitating targeted recommendations. Recent innovations employing Large Language Models (LLMs) have advanced the field by encoding item semantics yet they often necessitate substantial parameter tuning and are resource-demanding. Moreover these works fails to consider the diverse characteristics of different types of users and thus diminishes the recommendation accuracy. In this paper we propose a parameter-efficient Large Language Model Bi-Tuning framework for sequential recommendation with collaborative information (Laser). Specifically Bi-Tuning works by inserting trainable virtual tokens at both the prefix and suffix of the input sequence and freezing the LLM parameters thus optimizing the LLM for the sequential recommendation. In our Laser the prefix is utilized to incorporate user-item collaborative information and adapt the LLM to the recommendation task while the suffix converts the output embeddings of the LLM from the language space to the recommendation space for the follow-up item recommendation. Furthermore to capture the characteristics of different types of users when integrating the collaborative information via the prefix we introduce M-Former a lightweight MoE-based querying transformer that uses a set of query experts to integrate diverse user-specific collaborative information encoded by frozen ID-based sequential recommender systems significantly improving the accuracy of recommendations. Extensive experiments on real-world datasets demonstrate that Laser can parameter-efficiently adapt LLMs to effective recommender systems significantly outperforming state-of-the-art methods.
