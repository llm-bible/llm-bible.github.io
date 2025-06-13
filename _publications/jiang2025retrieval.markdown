---
layout: publication
title: 'RAS: Retrieval-and-structuring For Knowledge-intensive LLM Generation'
authors: Pengcheng Jiang, Lang Cao, Ruike Zhu, Minhao Jiang, Yunyi Zhang, Jimeng Sun, Jiawei Han
conference: "Arxiv"
year: 2025
bibkey: jiang2025retrieval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10996'}
  - {name: "Code", url: 'https://github.com/pat-jj/RAS'}
tags: ['Has Code', 'Interpretability and Explainability', 'RAG', 'Security', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large language models (LLMs) have achieved impressive performance on knowledge-intensive tasks, yet they often struggle with multi-step reasoning due to the unstructured nature of retrieved context. While retrieval-augmented generation (RAG) methods provide external information, the lack of explicit organization among retrieved passages limits their effectiveness, leading to brittle reasoning pathways. Recent interpretability studies highlighting the importance of structured intermediate reasoning further align with this perspective. We propose Retrieval-And-Structuring (RAS), a framework that dynamically constructs query-specific knowledge graphs through iterative retrieval and structured knowledge building. RAS interleaves targeted retrieval planning with incremental graph construction, enabling models to assemble and reason over evolving knowledge structures tailored to each query. On seven knowledge-intensive benchmarks, RAS consistently outperforms strong baselines, achieving up to 6.4% and 7.0% gains with open-source and proprietary LLMs, respectively. Our results demonstrate that dynamic, query-specific knowledge structuring offers a robust path to improving reasoning accuracy and robustness in language model generation. Our data and code can be found at https://github.com/pat-jj/RAS.
