---
layout: publication
title: 'Rethinking Information Synthesis In Multimodal Question Answering A Multi-agent Perspective'
authors: Krishna Singh Rajput, Tejas Anvekar, Chitta Baral, Vivek Gupta
conference: "Arxiv"
year: 2025
bibkey: rajput2025rethinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20816'}
tags: ['Agentic', 'Interpretability and Explainability', 'Security', 'Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advances in multimodal question answering have primarily focused on combining heterogeneous modalities or fine-tuning multimodal large language models. While these approaches have shown strong performance, they often rely on a single, generalized reasoning strategy, overlooking the unique characteristics of each modality ultimately limiting both accuracy and interpretability. To address these limitations, we propose MAMMQA, a multi-agent QA framework for multimodal inputs spanning text, tables, and images. Our system includes two Visual Language Model (VLM) agents and one text-based Large Language Model (LLM) agent. The first VLM decomposes the user query into sub-questions and sequentially retrieves partial answers from each modality. The second VLM synthesizes and refines these results through cross-modal reasoning. Finally, the LLM integrates the insights into a cohesive answer. This modular design enhances interpretability by making the reasoning process transparent and allows each agent to operate within its domain of expertise. Experiments on diverse multimodal QA benchmarks demonstrate that our cooperative, multi-agent framework consistently outperforms existing baselines in both accuracy and robustness.
