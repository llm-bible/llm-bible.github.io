---
layout: publication
title: MultiHop-RAG Benchmarking Retrieval-Augmented Generation for Multi-Hop Queries
authors: Tang Yixuan, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: tang2024multihop
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15391"}
  - {name: "Code", url: "https://github.com/yixuantt/MultiHop-RAG/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) augments large language models (LLM) by retrieving relevant knowledge showing promising potential in mitigating LLM hallucinations and enhancing response quality thereby facilitating the great adoption of LLMs in practice. However we find that existing RAG systems are inadequate in answering multi-hop queries which require retrieving and reasoning over multiple pieces of supporting evidence. Furthermore to our knowledge no existing RAG benchmarking dataset focuses on multi-hop queries. In this paper we develop a novel dataset MultiHop-RAG which consists of a knowledge base a large collection of multi-hop queries their ground-truth answers and the associated supporting evidence. We detail the procedure of building the dataset utilizing an English news article dataset as the underlying RAG knowledge base. We demonstrate the benchmarking utility of MultiHop-RAG in two experiments. The first experiment compares different embedding models for retrieving evidence for multi-hop queries. In the second experiment we examine the capabilities of various state-of-the-art LLMs including GPT-4 PaLM and Llama2-70B in reasoning and answering multi-hop queries given the evidence. Both experiments reveal that existing RAG methods perform unsatisfactorily in retrieving and answering multi-hop queries. We hope MultiHop-RAG will be a valuable resource for the community in developing effective RAG systems thereby facilitating greater adoption of LLMs in practice. The MultiHop-RAG and implemented RAG system is publicly available at https://github.com/yixuantt/MultiHop-RAG/.
