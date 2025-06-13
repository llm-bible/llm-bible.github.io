---
layout: publication
title: 'Probing Neural Topology Of Large Language Models'
authors: Yu Zheng, Yuan Yuan, Yong Li, Paolo Santi
conference: "Arxiv"
year: 2025
bibkey: zheng2025probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01042"}
  - {name: "Code", url: "https://github.com/DavyMorgan/llm-graph-probing"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Probing large language models (LLMs) has yielded valuable insights into their internal mechanisms by linking neural representations to interpretable semantics. However, how neurons functionally co-activate with each other to give rise to emergent capabilities remains largely unknown, hindering a deeper understanding and safer development of LLMs. In this work, we introduce graph probing, a method for uncovering the functional connectivity topology of LLM neurons and relating it to language generation performance. By analyzing internal neural graphs across diverse LLM families and scales, we discover a universal predictability of next-token prediction performance using only neural topology. This predictability is robust even when retaining just 1% of neuron connections or probing models after only 8 pretraining steps, highlighting the sparsity and early emergence of topological patterns. Further graph matching analysis suggests that, despite significant distinctions in architectures, parameters, and training data, different LLMs develop intricate and consistent neural topological structures that may form the foundation for their language generation abilities. Codes and data for the graph probing toolbox are released at https://github.com/DavyMorgan/llm-graph-probing.
