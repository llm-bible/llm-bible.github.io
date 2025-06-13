---
layout: publication
title: 'Syftr: Pareto-optimal Generative AI'
authors: Alexander Conway, Debadeepta Dey, Stefan Hackmann, Matthew Hausknecht, Michael Schmidt, Mark Steadman, Nick Volynets
conference: "Arxiv"
year: 2025
bibkey: conway2025pareto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20266"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Pruning', 'Applications']
---
Retrieval-Augmented Generation (RAG) pipelines are central to applying large language models (LLMs) to proprietary or dynamic data. However, building effective RAG flows is complex, requiring careful selection among vector databases, embedding models, text splitters, retrievers, and synthesizing LLMs. The challenge deepens with the rise of agentic paradigms. Modules like verifiers, rewriters, and rerankers-each with intricate hyperparameter dependencies have to be carefully tuned. Balancing tradeoffs between latency, accuracy, and cost becomes increasingly difficult in performance-sensitive applications.
  We introduce syftr, a framework that performs efficient multi-objective search over a broad space of agentic and non-agentic RAG configurations. Using Bayesian Optimization, syftr discovers Pareto-optimal flows that jointly optimize task accuracy and cost. A novel early-stopping mechanism further improves efficiency by pruning clearly suboptimal candidates. Across multiple RAG benchmarks, syftr finds flows which are on average approximately 9 times cheaper while preserving most of the accuracy of the most accurate flows on the Pareto-frontier. Furthermore, syftr's ability to design and optimize allows integrating new modules, making it even easier and faster to realize high-performing generative AI pipelines.
