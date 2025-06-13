---
layout: publication
title: 'Leave No Document Behind: Benchmarking Long-context Llms With Extended Multi-doc QA'
authors: Minzheng Wang, Longze Chen, Cheng Fu, Shengyi Liao, Xinghua Zhang, Bingli Wu, Haiyang Yu, Nan Xu, Lei Zhang, Run Luo, Yunshui Li, Min Yang, Fei Huang, Yongbin Li
conference: "Arxiv"
year: 2024
bibkey: wang2024leave
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17419"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Applications', 'Attention Mechanism']
---
Long-context modeling capabilities have garnered widespread attention,
leading to the emergence of Large Language Models (LLMs) with ultra-context
windows. Meanwhile, benchmarks for evaluating long-context LLMs are gradually
catching up. However, existing benchmarks employ irrelevant noise texts to
artificially extend the length of test cases, diverging from the real-world
scenarios of long-context applications. To bridge this gap, we propose a novel
long-context benchmark, Loong, aligning with realistic scenarios through
extended multi-document question answering (QA). Unlike typical document QA, in
Loong's test cases, each document is relevant to the final answer, ignoring any
document will lead to the failure of the answer. Furthermore, Loong introduces
four types of tasks with a range of context lengths: Spotlight Locating,
Comparison, Clustering, and Chain of Reasoning, to facilitate a more realistic
and comprehensive evaluation of long-context understanding. Extensive
experiments indicate that existing long-context language models still exhibit
considerable potential for enhancement. Retrieval augmented generation (RAG)
achieves poor performance, demonstrating that Loong can reliably assess the
model's long-context modeling capabilities.
