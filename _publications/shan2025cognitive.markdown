---
layout: publication
title: 'Cognitive Memory In Large Language Models'
authors: Lianlei Shan, Shixian Luo, Zezhou Zhu, Yu Yuan, Yong Wu
conference: "Arxiv"
year: 2025
bibkey: shan2025cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02441"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Merging', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Prompting', 'Applications', 'Attention Mechanism']
---
This paper examines memory mechanisms in Large Language Models (LLMs),
emphasizing their importance for context-rich responses, reduced
hallucinations, and improved efficiency. It categorizes memory into sensory,
short-term, and long-term, with sensory memory corresponding to input prompts,
short-term memory processing immediate context, and long-term memory
implemented via external databases or structures. The text-based memory section
covers acquisition (selection and summarization), management (updating,
accessing, storing, and resolving conflicts), and utilization (full-text
search, SQL queries, semantic search). The KV cache-based memory section
discusses selection methods (regularity-based summarization, score-based
approaches, special token embeddings) and compression techniques (low-rank
compression, KV merging, multimodal compression), along with management
strategies like offloading and shared attention mechanisms. Parameter-based
memory methods (LoRA, TTT, MoE) transform memories into model parameters to
enhance efficiency, while hidden-state-based memory approaches (chunk
mechanisms, recurrent transformers, Mamba model) improve long-text processing
by combining RNN hidden states with current methods. Overall, the paper offers
a comprehensive analysis of LLM memory mechanisms, highlighting their
significance and future research directions.
