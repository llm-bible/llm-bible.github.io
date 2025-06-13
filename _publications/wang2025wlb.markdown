---
layout: publication
title: 'WLB-LLM: Workload-balanced 4D Parallelism For Large Language Model Training'
authors: Zheng Wang, Anna Cai, Xinfeng Xie, Zaifeng Pan, Yue Guan, Weiwei Chu, Jie Wang, Shikai Li, Jianyu Huang, Chris Cai, Yuchen Hao, Yufei Ding
conference: "Arxiv"
year: 2025
bibkey: wang2025wlb
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17924'}
tags: ['RAG', 'Tools', 'Training Techniques']
---
In this work, we present WLB-LLM, a workLoad-balanced 4D parallelism for
large language model training. We first thoroughly analyze the workload
imbalance issue in LLM training and identify two primary sources of imbalance
at the pipeline parallelism and context parallelism levels. Then, to address
the imbalance issue, at the pipeline parallelism level, WLB-LLM incorporates a
workload-aware variable-length document packing method to balance the
computation and communication workload across micro-batches. Additionally, at
the context parallelism level, WLB-LLM introduces a novel fine-grained
per-document sharding strategy, ensuring each worker within a context
parallelism group has an identical workload. Comprehensive experiments under
different model scales demonstrate that WLB-LLM significantly mitigates the
workload imbalance during 4D parallelism LLM training and achieves an average
speedup of 1.23x when applying WLB-LLM in our internal LLM training framework.
