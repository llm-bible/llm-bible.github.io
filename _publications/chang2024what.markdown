---
layout: publication
title: 'What External Knowledge Is Preferred By Llms? Characterizing And Exploring Chain Of Evidence In Imperfect Context For Multi-hop QA'
authors: Zhiyuan Chang, Mingyang Li, Xiaojun Jia, Junjie Wang, Yuekai Huang, Qing Wang, Yihao Huang, Yang Liu
conference: "Arxiv"
year: 2024
bibkey: chang2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12632"}
tags: ['Security', 'RAG', 'Reinforcement Learning']
---
Incorporating external knowledge has emerged as a promising way to mitigate outdated knowledge and hallucinations in LLM. However, external knowledge is often imperfect, encompassing substantial extraneous or even inaccurate content, which interferes with the LLM's utilization of useful knowledge in the context. This paper seeks to characterize the features of preferred external knowledge and perform empirical studies in imperfect contexts. Inspired by the chain of evidence (CoE), we characterize that the knowledge preferred by LLMs should maintain both relevance to the question and mutual support among the textual pieces. Accordingly, we propose a CoE discrimination approach and conduct a comparative analysis between CoE and Non-CoE samples across significance, deceptiveness, and robustness, revealing the LLM's preference for external knowledge that aligns with CoE features. Furthermore, we selected three representative tasks (RAG-based multi-hop QA, external knowledge poisoning and poisoning defense), along with corresponding SOTA or prevalent baselines. By integrating CoE features, the variants achieved significant improvements over the original baselines.
