---
layout: publication
title: 'Researchbench: Benchmarking Llms In Scientific Discovery Via Inspiration-based Task Decomposition'
authors: Yujie Liu, Zonglin Yang, Tong Xie, Jinjie Ni, Ben Gao, Yuqiang Li, Shixiang Tang, Wanli Ouyang, Erik Cambria, Dongzhan Zhou
conference: "Arxiv"
year: 2025
bibkey: liu2025benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21248"}
tags: ['Training Techniques', 'Survey Paper', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated potential in assisting
scientific research, yet their ability to discover high-quality research
hypotheses remains unexamined due to the lack of a dedicated benchmark. To
address this gap, we introduce the first large-scale benchmark for evaluating
LLMs with a near-sufficient set of sub-tasks of scientific discovery:
inspiration retrieval, hypothesis composition, and hypothesis ranking. We
develop an automated framework that extracts critical components - research
questions, background surveys, inspirations, and hypotheses - from scientific
papers across 12 disciplines, with expert validation confirming its accuracy.
To prevent data contamination, we focus exclusively on papers published in
2024, ensuring minimal overlap with LLM pretraining data. Our evaluation
reveals that LLMs perform well in retrieving inspirations, an
out-of-distribution task, suggesting their ability to surface novel knowledge
associations. This positions LLMs as "research hypothesis mines", capable of
facilitating automated scientific discovery by generating innovative hypotheses
at scale with minimal human intervention.
