---
layout: publication
title: 'Coranking: Collaborative Ranking With Small And Large Ranking Agents'
authors: Wenhan Liu, Xinyu Ma, Yutao Zhu, Lixin Su, Shuaiqiang Wang, Dawei Yin, Zhicheng Dou
conference: "Arxiv"
year: 2025
bibkey: liu2025collaborative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23427"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Ethics and Bias', 'Tools', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated superior listwise ranking
performance. However, their superior performance often relies on large-scale
parameters (\eg, GPT-4) and a repetitive sliding window process, which
introduces significant efficiency challenges. In this paper, we propose
\textbf\{CoRanking\}, a novel collaborative ranking framework that combines small
and large ranking models for efficient and effective ranking. CoRanking first
employs a small-size reranker to pre-rank all the candidate passages, bringing
relevant ones to the top part of the list (\eg, top-20). Then, the LLM listwise
reranker is applied to only rerank these top-ranked passages instead of the
whole list, substantially enhancing overall ranking efficiency. Although more
efficient, previous studies have revealed that the LLM listwise reranker have
significant positional biases on the order of input passages. Directly feed the
top-ranked passages from small reranker may result in the sub-optimal
performance of LLM listwise reranker. To alleviate this problem, we introduce a
passage order adjuster trained via reinforcement learning, which reorders the
top passages from the small reranker to align with the LLM's preferences of
passage order. Extensive experiments on three IR benchmarks demonstrate that
CoRanking significantly improves efficiency (reducing ranking latency by about
70%) while achieving even better effectiveness compared to using only the LLM
listwise reranker.
