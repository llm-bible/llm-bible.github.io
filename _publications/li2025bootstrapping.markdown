---
layout: publication
title: 'Knowtrace: Bootstrapping Iterative Retrieval-augmented Generation With Structured Knowledge Tracing'
authors: Rui Li, Quanyu Dai, Zeyu Zhang, Xu Chen, Zhenhua Dong, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: li2025bootstrapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20245"}
tags: ['RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Recent advances in retrieval-augmented generation (RAG) furnish large language models (LLMs) with iterative retrievals of relevant information to handle complex multi-hop questions. These methods typically alternate between LLM reasoning and retrieval to accumulate external information into the LLM's context. However, the ever-growing context inherently imposes an increasing burden on the LLM to perceive connections among critical information pieces, with futile reasoning steps further exacerbating this overload issue. In this paper, we present KnowTrace, an elegant RAG framework to (1) mitigate the context overload and (2) bootstrap higher-quality multi-step reasoning. Instead of simply piling the retrieved contents, KnowTrace autonomously traces out desired knowledge triplets to organize a specific knowledge graph relevant to the input question. Such a structured workflow not only empowers the LLM with an intelligible context for inference, but also naturally inspires a reflective mechanism of knowledge backtracing to identify contributive LLM generations as process supervision data for self-bootstrapping. Extensive experiments show that KnowTrace consistently surpasses existing methods across three multi-hop question answering benchmarks, and the bootstrapped version further amplifies the gains.
