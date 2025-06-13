---
layout: publication
title: 'Large Language Model As Universal Retriever In Industrial-scale Recommender System'
authors: Junguang Jiang, Yanwen Huang, Bin Liu, Xiaoyu Kong, Xinhang Li, Ziru Xu, Han Zhu, Jian Xu, Bo Zheng
conference: "Arxiv"
year: 2025
bibkey: jiang2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03041"}
tags: ['RecSys', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
In real-world recommender systems, different retrieval objectives are typically addressed using task-specific datasets with carefully designed model architectures. We demonstrate that Large Language Models (LLMs) can function as universal retrievers, capable of handling multiple objectives within a generative retrieval framework. To model complex user-item relationships within generative retrieval, we propose multi-query representation. To address the challenge of extremely large candidate sets in industrial recommender systems, we introduce matrix decomposition to boost model learnability, discriminability, and transferability, and we incorporate probabilistic sampling to reduce computation costs. Finally, our Universal Retrieval Model (URM) can adaptively generate a set from tens of millions of candidates based on arbitrary given objective while keeping the latency within tens of milliseconds. Applied to industrial-scale data, URM outperforms expert models elaborately designed for different retrieval objectives on offline experiments and significantly improves the core metric of online advertising platform by \\(3%\\).
