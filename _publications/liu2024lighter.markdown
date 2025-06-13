---
layout: publication
title: 'Lighter And Better: Towards Flexible Context Adaptation For Retrieval Augmented Generation'
authors: Zheng Liu, Chenyuan Wu, Ninglu Shao, Shitao Xiao, Chaozhuo Li, Defu Lian
conference: "Arxiv"
year: 2024
bibkey: liu2024lighter
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15699'}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The existing Retrieval-Augmented Generation (RAG) systems face significant
challenges in terms of cost and effectiveness. On one hand, they need to encode
the lengthy retrieved contexts before responding to the input tasks, which
imposes substantial computational overhead. On the other hand, directly using
generic Large Language Models (LLMs) often leads to sub-optimal answers, while
task-specific fine-tuning may compromise the LLMs' general capabilities. To
address these challenges, we introduce a novel approach called FlexRAG
(Flexible Context Adaptation for RAG). In this approach, the retrieved contexts
are compressed into compact embeddings before being encoded by the LLMs.
Simultaneously, these compressed embeddings are optimized to enhance downstream
RAG performance. A key feature of FlexRAG is its flexibility, which enables
effective support for diverse compression ratios and selective preservation of
important contexts. Thanks to these technical designs, FlexRAG achieves
superior generation quality while significantly reducing running costs.
Comprehensive experiments on various question-answering datasets validate our
approach as a cost-effective and flexible solution for RAG systems.
