---
layout: publication
title: 'Causal Head Gating: A Framework For Interpreting Roles Of Attention Heads In Transformers'
authors: Andrew Nam, Henry Conklin, Yukang Yang, Thomas Griffiths, Jonathan Cohen, Sarah-jane Leslie
conference: "Arxiv"
year: 2025
bibkey: nam2025causal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.13737"}
tags: ['Transformer', 'Tools', 'Interpretability and Explainability', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
We present causal head gating (CHG), a scalable method for interpreting the functional roles of attention heads in transformer models. CHG learns soft gates over heads and assigns them a causal taxonomy - facilitating, interfering, or irrelevant - based on their impact on task performance. Unlike prior approaches in mechanistic interpretability, which are hypothesis-driven and require prompt templates or target labels, CHG applies directly to any dataset using standard next-token prediction. We evaluate CHG across multiple large language models (LLMs) in the Llama 3 model family and diverse tasks, including syntax, commonsense, and mathematical reasoning, and show that CHG scores yield causal - not merely correlational - insight, validated via ablation and causal mediation analyses. We also introduce contrastive CHG, a variant that isolates sub-circuits for specific task components. Our findings reveal that LLMs contain multiple sparse, sufficient sub-circuits, that individual head roles depend on interactions with others (low modularity), and that instruction following and in-context learning rely on separable mechanisms.
