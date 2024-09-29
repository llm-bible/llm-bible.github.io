---
layout: publication
title: Multihop45;rag Benchmarking Retrieval45;augmented Generation For Multi45;hop Queries
authors: Tang Yixuan, Yang Yi
conference: "Arxiv"
year: 2024
bibkey: tang2024multihop
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15391"}
  - {name: "Code", url: "https://github.com/yixuantt/MultiHop&#45;RAG/"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Retrieval45;augmented generation (RAG) augments large language models (LLM) by retrieving relevant knowledge showing promising potential in mitigating LLM hallucinations and enhancing response quality thereby facilitating the great adoption of LLMs in practice. However we find that existing RAG systems are inadequate in answering multi45;hop queries which require retrieving and reasoning over multiple pieces of supporting evidence. Furthermore to our knowledge no existing RAG benchmarking dataset focuses on multi45;hop queries. In this paper we develop a novel dataset MultiHop45;RAG which consists of a knowledge base a large collection of multi45;hop queries their ground45;truth answers and the associated supporting evidence. We detail the procedure of building the dataset utilizing an English news article dataset as the underlying RAG knowledge base. We demonstrate the benchmarking utility of MultiHop45;RAG in two experiments. The first experiment compares different embedding models for retrieving evidence for multi45;hop queries. In the second experiment we examine the capabilities of various state45;of45;the45;art LLMs including GPT45;4 PaLM and Llama245;70B in reasoning and answering multi45;hop queries given the evidence. Both experiments reveal that existing RAG methods perform unsatisfactorily in retrieving and answering multi45;hop queries. We hope MultiHop45;RAG will be a valuable resource for the community in developing effective RAG systems thereby facilitating greater adoption of LLMs in practice. The MultiHop45;RAG and implemented RAG system is publicly available at https://github.com/yixuantt/MultiHop&#45;RAG/.
