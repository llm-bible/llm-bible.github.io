---
layout: publication
title: 'Interpreting Token Compositionality In Llms: A Robustness Analysis'
authors: Nura Aljaafari, Danilo S. Carvalho, André Freitas
conference: "Arxiv"
year: 2024
bibkey: aljaafari2024interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12924"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Interpretability', 'Transformer', 'Interpretability and Explainability']
---
Understanding the internal mechanisms of large language models (LLMs) is integral to enhancing their reliability, interpretability, and inference processes. We present Constituent-Aware Pooling (CAP), a methodology designed to analyse how LLMs process compositional linguistic structures. Grounded in principles of compositionality, mechanistic interpretability, and information theory, CAP systematically intervenes in model activations through constituent-based pooling at various model levels. Our experiments on inverse definition modelling, hypernym and synonym prediction reveal critical insights into transformers' limitations in handling compositional abstractions. No specific layer integrates tokens into unified semantic representations based on their constituent parts. We observe fragmented information processing, which intensifies with model size, suggesting that larger models struggle more with these interventions and exhibit greater information dispersion. This fragmentation likely stems from transformers' training objectives and architectural design, preventing systematic and cohesive representations. Our findings highlight fundamental limitations in current transformer architectures regarding compositional semantics processing and model interpretability, underscoring the critical need for novel approaches in LLM design to address these challenges.
