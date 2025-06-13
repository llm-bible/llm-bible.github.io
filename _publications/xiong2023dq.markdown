---
layout: publication
title: 'Dq-lore: Dual Queries With Low Rank Approximation Re-ranking For In-context Learning'
authors: Jing Xiong, Zixuan Li, Chuanyang Zheng, Zhijiang Guo, Yichun Yin, Enze Xie, Zhicheng Yang, Qingxing Cao, Haiming Wang, Xiongwei Han, Jing Tang, Chengming Li, Xiaodan Liang
conference: "Arxiv"
year: 2023
bibkey: xiong2023dq
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.02954'}
  - {name: "Code", url: 'https://github.com/AI4fun/DQ-LoRe}{https://github.com/AI4fun/DQ-LoRe'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'GPT', 'Tools', 'Prompting', 'In-Context Learning']
---
Recent advances in natural language processing, primarily propelled by Large
Language Models (LLMs), have showcased their remarkable capabilities grounded
in in-context learning. A promising avenue for guiding LLMs in intricate
reasoning tasks involves the utilization of intermediate reasoning steps within
the Chain-of-Thought (CoT) paradigm. Nevertheless, the central challenge lies
in the effective selection of exemplars for facilitating in-context learning.
In this study, we introduce a framework that leverages Dual Queries and
Low-rank approximation Re-ranking (DQ-LoRe) to automatically select exemplars
for in-context learning. Dual Queries first query LLM to obtain LLM-generated
knowledge such as CoT, then query the retriever to obtain the final exemplars
via both question and the knowledge. Moreover, for the second query, LoRe
employs dimensionality reduction techniques to refine exemplar selection,
ensuring close alignment with the input question's knowledge. Through extensive
experiments, we demonstrate that DQ-LoRe significantly outperforms prior
state-of-the-art methods in the automatic selection of exemplars for GPT-4,
enhancing performance from 92.5% to 94.2%. Our comprehensive analysis further
reveals that DQ-LoRe consistently outperforms retrieval-based approaches in
terms of both performance and adaptability, especially in scenarios
characterized by distribution shifts. DQ-LoRe pushes the boundary of in-context
learning and opens up new avenues for addressing complex reasoning challenges.
Our code is released at
https://github.com/AI4fun/DQ-LoRe\}\{https://github.com/AI4fun/DQ-LoRe.
