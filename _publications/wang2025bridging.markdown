---
layout: publication
title: 'R\(^3\)mem: Bridging Memory Retention And Retrieval Via Reversible Compression'
authors: Xiaoqiang Wang, Suyuchen Wang, Yun Zhu, Bang Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15957"}
tags: ['Fine-Tuning', 'Transformer', 'Agentic', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Training Techniques', 'Pretraining Methods']
---
Memory plays a key role in enhancing LLMs' performance when deployed to
real-world applications. Existing solutions face trade-offs: explicit memory
designs based on external storage require complex management and incur storage
overhead, while implicit memory designs that store information via parameters
struggle with reliable retrieval. In this paper, we propose R\\(^3\\)Mem, a memory
network that optimizes both information Retention and Retrieval through
Reversible context compression. Specifically, R\\(^3\\)Mem employs virtual memory
tokens to compress and encode infinitely long histories, further enhanced by a
hierarchical compression strategy that refines information from document- to
entity-level for improved assimilation across granularities. For retrieval,
R\\(^3\\)Mem employs a reversible architecture, reconstructing raw data by invoking
the model backward with compressed information. Implemented via
parameter-efficient fine-tuning, it can integrate seamlessly with any
Transformer-based model. Experiments demonstrate that our memory design
achieves state-of-the-art performance in long-context language modeling and
retrieval-augmented generation tasks. It also significantly outperforms
conventional memory modules in long-horizon interaction tasks like
conversational agents, showcasing its potential for next-generation retrieval
systems.
