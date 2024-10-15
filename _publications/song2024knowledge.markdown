---
layout: publication
title: 'Knowledge Editing On Black-box Large Language Models'
authors: Song Xiaoshuai, Wang Zhengyang, He Keqing, Dong Guanting, Mou Yutao, Zhao Jinxu, Xu Weiran
conference: "Arxiv"
year: 2024
bibkey: song2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08631"}
tags: ['RAG', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
Knowledge editing (KE) aims to efficiently and precisely modify the behavior
of large language models (LLMs) to update specific knowledge without negatively
influencing other knowledge. Current research primarily focuses on white-box
LLMs editing, overlooking an important scenario: black-box LLMs editing, where
LLMs are accessed through interfaces and only textual output is available. In
this paper, we first officially introduce KE on black-box LLMs and then propose
a comprehensive evaluation framework to overcome the limitations of existing
evaluations that are not applicable to black-box LLMs editing and lack
comprehensiveness. To tackle privacy leaks of editing data and style
over-editing in current methods, we introduce a novel postEdit framework,
resolving privacy concerns through downstream post-processing and maintaining
textual style consistency via fine-grained editing to original responses.
Experiments and analysis on two benchmarks demonstrate that postEdit
outperforms all baselines and achieves strong generalization, especially with
huge improvements on style retention (average \\(+20.82%\uparrow\\)).
