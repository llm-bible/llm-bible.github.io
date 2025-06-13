---
layout: publication
title: 'Sentinel: Attention Probing Of Proxy Models For LLM Context Compression With An Understanding Perspective'
authors: Yong Zhang, Yanwen Huang, Ning Cheng, Yang Guo, Yun Zhu, Yanmeng Wang, Shaojun Wang, Jing Xiao
conference: "Arxiv"
year: 2025
bibkey: zhang2025attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23277'}
  - {name: "Code", url: 'https://github.com/yzhangchuck/Sentinel'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Training Techniques', 'Tools', 'Model Architecture']
---
Retrieval-augmented generation (RAG) enhances large language models (LLMs) with external context, but retrieved passages are often lengthy, noisy, or exceed input limits. Existing compression methods typically require supervised training of dedicated compression models, increasing cost and reducing portability. We propose Sentinel, a lightweight sentence-level compression framework that reframes context filtering as an attention-based understanding task. Rather than training a compression model, Sentinel probes decoder attention from an off-the-shelf 0.5B proxy LLM using a lightweight classifier to identify sentence relevance. Empirically, we find that query-context relevance estimation is consistent across model scales, with 0.5B proxies closely matching the behaviors of larger models. On the LongBench benchmark, Sentinel achieves up to 5\\(\times\\) compression while matching the QA performance of 7B-scale compression systems. Our results suggest that probing native attention signals enables fast, effective, and question-aware context compression. Code available at: https://github.com/yzhangchuck/Sentinel.
