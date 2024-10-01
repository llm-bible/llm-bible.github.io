---
layout: publication
title: 'D2LLM: Decomposed And Distilled Large Language Models For Semantic Search'
authors: Liao Zihan, Yu Hang, Li Jianguo, Wang Jun, Zhang Wei
conference: "Arxiv"
year: 2024
bibkey: liao2024decomposed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17262"}
  - {name: "Code", url: "https://github.com/codefuse-ai/D2LLM"}
tags: ['Applications', 'Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
'The key challenge in semantic search is to create models that are both accurate and efficient in pinpointing relevant sentences for queries. While BERT-style bi-encoders excel in efficiency with pre-computed embeddings, they often miss subtle nuances in search tasks. Conversely, GPT-style LLMs with cross-encoder designs capture these nuances but are computationally intensive, hindering real-time applications. In this paper, we present D2LLMs-Decomposed and Distilled LLMs for semantic search-that combines the best of both worlds. We decompose a cross-encoder into an efficient bi-encoder integrated with Pooling by Multihead Attention and an Interaction Emulation Module, achieving nuanced understanding and pre-computability. Knowledge from the LLM is distilled into this model using contrastive, rank, and feature imitation techniques. Our experiments show that D2LLM surpasses five leading baselines in terms of all metrics across three tasks, particularly improving NLI task performance by at least 6.45&#37;. The source code is available at https://github.com/codefuse-ai/D2LLM.'
