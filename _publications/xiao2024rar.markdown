---
layout: publication
title: Rar45;b Reasoning As Retrieval Benchmark
authors: Xiao Chenghao, Hudson G Thomas, Moubayed Noura Al
conference: "Arxiv"
year: 2024
bibkey: xiao2024rar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06347"}
  - {name: "Code", url: "https://github.com/gowitheflow&#45;1998/RAR&#45;b"}
tags: ['Applications', 'Has Code', 'Merging', 'RAG', 'Reinforcement Learning']
---
Semantic textual similartiy (STS) and information retrieval tasks (IR) tasks have been the two major avenues to record the progress of embedding models in the past few years. Under the emerging Retrieval45;augmented Generation (RAG) paradigm we envision the need to evaluate next45;level language understanding abilities of embedding models and take a conscious look at the reasoning abilities stored in them. Addressing this we pose the question Can retrievers solve reasoning problems By transforming reasoning tasks into retrieval tasks we find that without specifically trained for reasoning45;level language understanding current state45;of45;the45;art retriever models may still be far from being competent for playing the role of assisting LLMs especially in reasoning45;intensive tasks. Moreover albeit trained to be aware of instructions instruction45;aware IR models are often better off without instructions in inference time for reasoning tasks posing an overlooked retriever45;LLM behavioral gap for the research community to align. However recent decoder45;based embedding models show great promise in narrowing the gap highlighting the pathway for embedding models to achieve reasoning45;level language understanding. We also show that although current off45;the45;shelf re45;ranker models fail on these tasks injecting reasoning abilities into them through fine45;tuning still appears easier than doing so to bi45;encoders and we are able to achieve state45;of45;the45;art performance across all tasks by fine45;tuning a reranking model. We release Reasoning as Retrieval Benchmark (RAR45;b) a holistic suite of tasks and settings to evaluate the reasoning abilities stored in retriever models. RAR45;b is available at https://github.com/gowitheflow&#45;1998/RAR&#45;b.
