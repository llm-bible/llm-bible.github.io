---
layout: publication
title: 'Rtlrepocoder: Repository-level RTL Code Completion Through The Combination Of Fine-tuning And Retrieval Augmentation'
authors: Peiyang Wu, Nan Guo, Junliang Lv, Xiao Xiao, Xiaochun Ye
conference: "Arxiv"
year: 2025
bibkey: wu2025repository
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08862"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
As an essential part of modern hardware design, manually writing Register
Transfer Level (RTL) code such as Verilog is often labor-intensive. Following
the tremendous success of large language models (LLMs), researchers have begun
to explore utilizing LLMs for generating RTL code. However, current studies
primarily focus on generating simple single modules, which can not meet the
demands in real world. In fact, due to challenges in managing long-context RTL
code and complex cross-file dependencies, existing solutions cannot handle
large-scale Verilog repositories in practical hardware development. As the
first endeavor to exclusively adapt LLMs for large-scale RTL development, we
propose RTLRepoCoder, a groundbreaking solution that incorporates specific
fine-tuning and Retrieval-Augmented Generation (RAG) for repository-level
Verilog code completion. Open-source Verilog repositories from the real world,
along with an extended context size, are used for domain-specific fine-tuning.
The optimized RAG system improves the information density of the input context
by retrieving relevant code snippets. Tailored optimizations for RAG are
carried out, including the embedding model, the cross-file context splitting
strategy, and the chunk size. Our solution achieves state-of-the-art
performance on public benchmark, significantly surpassing GPT-4 and advanced
domain-specific LLMs on Edit Similarity and Exact Match rate. Comprehensive
experiments demonstrate the remarkable effectiveness of our approach and offer
insights for future work.
