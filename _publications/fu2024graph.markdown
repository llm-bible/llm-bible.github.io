---
layout: publication
title: 'Graphic: A Graph-based In-context Example Retrieval Model For Multi-step Reasoning'
authors: Jiale Fu, Yaqing Wang, Simeng Han, Jiaming Fan, Xu Yang
conference: "Arxiv"
year: 2024
bibkey: fu2024graph
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02203'}
tags: ['RAG', 'Applications', 'Prompting', 'Ethics and Bias', 'In-Context Learning']
---
In-context learning (ICL) enhances large language models (LLMs) by
incorporating demonstration examples, yet its effectiveness heavily depends on
the quality of selected examples. Current methods typically use text embeddings
to measure semantic similarity, which often introduces bias in multi-step
reasoning tasks. This occurs because text embeddings contain irrelevant
semantic information and lack deeper reasoning structures. To address this, we
propose GraphIC, a graph-based retrieval model that leverages reasoning-aware
representation and specialized similarity metric for in-context example
retrieval. GraphIC first constructs thought graphs-directed, node-attributed
graphs that explicitly model reasoning steps and their dependencies-for
candidate examples and queries. This approach filters out superficial semantics
while preserving essential reasoning processes. Next, GraphIC retrieves
examples using a novel similarity metric tailored for these graphs, capturing
sequential reasoning patterns and asymmetry between examples. Comprehensive
evaluations across mathematical reasoning, code generation, and logical
reasoning tasks demonstrate that GraphIC outperforms 10 baseline methods. Our
results highlight the importance of reasoning-aware retrieval in ICL, offering
a robust solution for enhancing LLM performance in multi-step reasoning
scenarios.
