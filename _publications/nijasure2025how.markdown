---
layout: publication
title: 'How Relevance Emerges: Interpreting Lora Fine-tuning In Reranking Llms'
authors: Atharva Nijasure, Tanya Chowdhury, James Allan
conference: "Arxiv"
year: 2025
bibkey: nijasure2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08780"}
tags: ['Fine-Tuning', 'Applications', 'Interpretability and Explainability', 'Training Techniques', 'Pretraining Methods']
---
We conduct a behavioral exploration of LoRA fine-tuned LLMs for Passage
Reranking to understand how relevance signals are learned and deployed by Large
Language Models. By fine-tuning Mistral-7B, LLaMA3.1-8B, and Pythia-6.9B on MS
MARCO under diverse LoRA configurations, we investigate how relevance modeling
evolves across checkpoints, the impact of LoRA rank (1, 2, 8, 32), and the
relative importance of updated MHA vs. MLP components. Our ablations reveal
which layers and projections within LoRA transformations are most critical for
reranking accuracy. These findings offer fresh explanations into LoRA's
adaptation mechanisms, setting the stage for deeper mechanistic studies in
Information Retrieval. All models used in this study have been shared.
