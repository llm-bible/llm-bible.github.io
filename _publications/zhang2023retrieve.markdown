---
layout: publication
title: Retrieve Anything To Augment Large Language Models
authors: Zhang Peitian, Xiao Shitao, Liu Zheng, Dou Zhicheng, Nie Jian-yun
conference: "Arxiv"
year: 2023
bibkey: zhang2023retrieve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07554"}
  - {name: "Code", url: "https://github.com/FlagOpen/FlagEmbedding"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) face significant challenges stemming from their inherent limitations in knowledge memory alignment and action. These challenges cannot be addressed by LLMs alone but should rely on assistance from the external world such as knowledge base memory store demonstration examples and tools. Retrieval augmentation stands as a vital mechanism for bridging the gap between LLMs and the external assistance. However conventional methods encounter two pressing issues. On the one hand the general45;purpose retrievers are not properly optimized for the retrieval augmentation of LLMs. On the other hand the task45;specific retrievers lack the required versatility hindering their performance across the diverse retrieval augmentation scenarios. In this work we present a novel approach the LLM45;Embedder which comprehensively supports the diverse retrieval augmentation needs of LLMs with one unified embedding model. Training such a unified model is non45;trivial as various retrieval tasks aim to capture distinct semantic relationships often subject to mutual interference. To address this challenge we systematically optimize our training methodology. This includes reward formulation based on LLMs feedback the stabilization of knowledge distillation multi45;task fine45;tuning with explicit instructions and homogeneous in45;batch negative sampling. These optimization strategies contribute to the outstanding empirical performance of the LLM45;Embedder. Notably it yields remarkable enhancements in retrieval augmentation for LLMs surpassing both general45;purpose and task45;specific retrievers in various evaluation scenarios. Our checkpoint and source code are publicly available at https://github.com/FlagOpen/FlagEmbedding.
