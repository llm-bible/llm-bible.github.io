---
layout: publication
title: 'Safety Alignment Depth In Large Language Models: A Markov Chain Perspective'
authors: Ching-chia Kao, Chia-mu Yu, Chun-shien Lu, Chu-song Chen
conference: "Arxiv"
year: 2025
bibkey: kao2025safety
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.00669"}
tags: ['Fine-Tuning', 'Responsible AI', 'GPT', 'RAG', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) are increasingly adopted in high-stakes
scenarios, yet their safety mechanisms often remain fragile. Simple jailbreak
prompts or even benign fine-tuning can bypass these protocols, underscoring the
need to understand where and how they fail. Recent findings suggest that
vulnerabilities emerge when alignment is confined to only the initial output
tokens. Unfortunately, even with the introduction of deep safety alignment,
determining the optimal safety depth remains an unresolved challenge. By
leveraging the equivalence between autoregressive language models and Markov
chains, this paper offers the first theoretical result on how to identify the
ideal depth for safety alignment, and demonstrates how permutation-based data
augmentation can tighten these bounds. Crucially, we reveal a fundamental
interaction between alignment depth and ensemble width-indicating that broader
ensembles can compensate for shallower alignments. These insights provide a
theoretical foundation for designing more robust, scalable safety strategies
that complement existing alignment approaches, opening new avenues for research
into safer, more reliable LLMs.
