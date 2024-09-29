---
layout: publication
title: "Rar-b: Reasoning As Retrieval Benchmark"
authors: Xiao Chenghao, Hudson G Thomas, Moubayed Noura Al
conference: "Arxiv"
year: 2024
bibkey: xiao2024rar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06347"}
  - {name: "Code", url: "https://github.com/gowitheflow-1998/RAR-b"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Merging', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Semantic textual similartiy (STS) and information retrieval tasks (IR) tasks have been the two major avenues to record the progress of embedding models in the past few years. Under the emerging Retrieval-augmented Generation (RAG) paradigm we envision the need to evaluate next-level language understanding abilities of embedding models and take a conscious look at the reasoning abilities stored in them. Addressing this we pose the question Can retrievers solve reasoning problems By transforming reasoning tasks into retrieval tasks we find that without specifically trained for reasoning-level language understanding current state-of-the-art retriever models may still be far from being competent for playing the role of assisting LLMs especially in reasoning-intensive tasks. Moreover albeit trained to be aware of instructions instruction-aware IR models are often better off without instructions in inference time for reasoning tasks posing an overlooked retriever-LLM behavioral gap for the research community to align. However recent decoder-based embedding models show great promise in narrowing the gap highlighting the pathway for embedding models to achieve reasoning-level language understanding. We also show that although current off-the-shelf re-ranker models fail on these tasks injecting reasoning abilities into them through fine-tuning still appears easier than doing so to bi-encoders and we are able to achieve state-of-the-art performance across all tasks by fine-tuning a reranking model. We release Reasoning as Retrieval Benchmark (RAR-b) a holistic suite of tasks and settings to evaluate the reasoning abilities stored in retriever models. RAR-b is available at https://github.com/gowitheflow-1998/RAR-b."
