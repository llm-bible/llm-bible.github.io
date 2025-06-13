---
layout: publication
title: 'Refining Sentence Embedding Model Through Ranking Sentences Generation With Large Language Models'
authors: Liyang He, Chenglong Liu, Rui Li, Zhenya Huang, Shulan Ruan, Jun Zhou, Enhong Chen
conference: "Arxiv"
year: 2025
bibkey: he2025refining
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13656'}
tags: ['Reinforcement Learning', 'RAG', 'Pretraining Methods']
---
Sentence embedding is essential for many NLP tasks, with contrastive learning methods achieving strong performance using annotated datasets like NLI. Yet, the reliance on manual labels limits scalability. Recent studies leverage large language models (LLMs) to generate sentence pairs, reducing annotation dependency. However, they overlook ranking information crucial for fine-grained semantic distinctions. To tackle this challenge, we propose a method for controlling the generation direction of LLMs in the latent space. Unlike unconstrained generation, the controlled approach ensures meaningful semantic divergence. Then, we refine exist sentence embedding model by integrating ranking information and semantic information. Experiments on multiple benchmarks demonstrate that our method achieves new SOTA performance with a modest cost in ranking sentence synthesis.
