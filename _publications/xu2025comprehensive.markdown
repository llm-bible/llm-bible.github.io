---
layout: publication
title: 'Graphomni: A Comprehensive And Extendable Benchmark Framework For Large Language Models On Graph-theoretic Tasks'
authors: Hao Xu, Xiangru Jian, Xinjian Zhao, Wei Pang, Chao Zhang, Suyuchen Wang, Qixin Zhang, Zhengyuan Dong, Joao Monteiro, Bang Liu, Qiuzhuang Sun, Tianshu Yu
conference: "Arxiv"
year: 2025
bibkey: xu2025comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.12764"}
  - {name: "Code", url: "https://github.com/GAI-Community/GraphOmni"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting']
---
This paper introduces GraphOmni, a comprehensive benchmark designed to evaluate the reasoning capabilities of LLMs on graph-theoretic tasks articulated in natural language. GraphOmni encompasses diverse graph types, serialization formats, and prompting schemes, significantly exceeding prior efforts in both scope and depth. Through extensive systematic evaluation, we identify critical interactions among these dimensions, demonstrating their substantial impact on model performance. Our experiments reveal that state-of-the-art models like Claude-3.5 and o4-mini consistently outperform other models, yet even these leading models exhibit substantial room for improvement. Performance variability is evident depending on the specific combinations of factors we considered, underscoring the necessity of comprehensive evaluations across these interconnected dimensions. Additionally, we observe distinct impacts of serialization and prompting strategies between open-source and closed-source models, encouraging the development of tailored approaches. Motivated by the findings, we also propose a reinforcement learning-inspired framework that adaptively selects the optimal factors influencing LLM reasoning capabilities. This flexible and extendable benchmark not only deepens our understanding of LLM performance on structured tasks but also provides a robust foundation for advancing research in LLM-based graph reasoning. The code and datasets are available at https://github.com/GAI-Community/GraphOmni.
