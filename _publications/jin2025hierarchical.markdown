---
layout: publication
title: 'Hierarchical Document Refinement For Long-context Retrieval-augmented Generation'
authors: Jiajie Jin, Xiaoxi Li, Guanting Dong, Yuyao Zhang, Yutao Zhu, Yongkang Wu, Zhonghua Li, Qi Ye, Zhicheng Dou
conference: "Arxiv"
year: 2025
bibkey: jin2025hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10413"}
  - {name: "Code", url: "https://github.com/ignorejjj/LongRefiner"}
tags: ['RAG', 'Has Code', 'Applications', 'Reinforcement Learning']
---
Real-world RAG applications often encounter long-context input scenarios, where redundant information and noise results in higher inference costs and reduced performance. To address these challenges, we propose LongRefiner, an efficient plug-and-play refiner that leverages the inherent structural characteristics of long documents. LongRefiner employs dual-level query analysis, hierarchical document structuring, and adaptive refinement through multi-task learning on a single foundation model. Experiments on seven QA datasets demonstrate that LongRefiner achieves competitive performance in various scenarios while using 10x fewer computational costs and latency compared to the best baseline. Further analysis validates that LongRefiner is scalable, efficient, and effective, providing practical insights for real-world long-text RAG applications. Our code is available at https://github.com/ignorejjj/LongRefiner.
