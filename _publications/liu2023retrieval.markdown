---
layout: publication
title: "Retrieval-based Knowledge Transfer: An Effective Approach For Extreme Large Language Model Compression"
authors: Liu Jiduan, Liu Jiahao, Wang Qifan, Wang Jingang, Cai Xunliang, Zhao Dongyan, Wang Ran Lucien, Yan Rui
conference: "Arxiv"
year: 2023
bibkey: liu2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15594"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Prompting', 'Quantization', 'RAG', 'Reinforcement Learning']
---
Large-scale pre-trained language models (LLMs) have demonstrated exceptional performance in various natural language processing (NLP) tasks. However the massive size of these models poses huge challenges for their deployment in real-world applications. While numerous model compression techniques have been proposed most of them are not well-suited for achieving extreme model compression when there is a significant gap in model scale. In this paper we introduce a novel compression paradigm called Retrieval-based Knowledge Transfer (RetriKT) which effectively transfers the knowledge of LLMs to extremely small-scale models (e.g. 137;). In particular our approach extracts knowledge from LLMs to construct a knowledge store from which the small-scale model can retrieve relevant information and leverage it for effective inference. To improve the quality of the model soft prompt tuning and Proximal Policy Optimization (PPO) reinforcement learning techniques are employed. Extensive experiments are conducted on low-resource tasks from SuperGLUE and GLUE benchmarks. The results demonstrate that the proposed approach significantly enhances the performance of small-scale models by leveraging the knowledge from LLMs.
