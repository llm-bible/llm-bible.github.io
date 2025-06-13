---
layout: publication
title: 'Prorank: Prompt Warmup Via Reinforcement Learning For Small Language Models Reranking'
authors: Xianming Li, Aamir Shakir, Rui Huang, Julius Lipp, Jing Li
conference: "Arxiv"
year: 2025
bibkey: li2025prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03487"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Reranking is fundamental to information retrieval and retrieval-augmented generation, with recent Large Language Models (LLMs) significantly advancing reranking quality. While recent advances with LLMs have significantly improved document reranking quality, current approaches primarily rely on large-scale LLMs (>7B parameters) through zero-shot prompting, presenting high computational costs. Small Language Models (SLMs) offer a promising alternative because of their efficiency, but our preliminary quantitative analysis reveals they struggle with understanding task prompts without fine-tuning. This limits their effectiveness for document reranking tasks. To address this issue, we introduce a novel two-stage training approach, ProRank, for SLM-based document reranking. First, we propose a prompt warmup stage using reinforcement learning GRPO to steer SLMs to understand task prompts and generate more accurate coarse-grained binary relevance scores for document reranking. Then, we continuously fine-tune the SLMs with a fine-grained score learning stage without introducing additional layers to further improve the reranking quality. Comprehensive experimental results demonstrate that the proposed ProRank consistently outperforms both the most advanced open-source and proprietary reranking models. Notably, our lightweight ProRank-0.5B model even surpasses the powerful 32B LLM reranking model on the BEIR benchmark, establishing that properly trained SLMs can achieve superior document reranking performance while maintaining computational efficiency.
