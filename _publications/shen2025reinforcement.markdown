---
layout: publication
title: 'Satori: Reinforcement Learning With Chain-of-action-thought Enhances LLM Reasoning Via Autoregressive Search'
authors: Maohao Shen, Guangtao Zeng, Zhenting Qi, Zhang-wei Hong, Zhenfang Chen, Wei Lu, Gregory Wornell, Subhro Das, David Cox, Chuang Gan
conference: "Arxiv"
year: 2025
bibkey: shen2025reinforcement
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02508'}
tags: ['Agentic', 'RAG', 'Training Techniques', 'GPT', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated remarkable reasoning capabilities across diverse domains. Recent studies have shown that increasing test-time computation enhances LLMs' reasoning capabilities. This typically involves extensive sampling at inference time guided by an external LLM verifier, resulting in a two-player system. Despite external guidance, the effectiveness of this system demonstrates the potential of a single LLM to tackle complex tasks. Thus, we pose a new research problem: Can we internalize the searching capabilities to fundamentally enhance the reasoning abilities of a single LLM? This work explores an orthogonal direction focusing on post-training LLMs for autoregressive searching (i.e., an extended reasoning process with self-reflection and self-exploration of new strategies). To achieve this, we propose the Chain-of-Action-Thought (COAT) reasoning and a two-stage training paradigm: 1) a small-scale format tuning stage to internalize the COAT reasoning format and 2) a large-scale self-improvement stage leveraging reinforcement learning. Our approach results in Satori, a 7B LLM trained on open-source models and data. Extensive empirical evaluations demonstrate that Satori achieves state-of-the-art performance on mathematical reasoning benchmarks while exhibits strong generalization to out-of-domain tasks. Code, data, and models are fully open-sourced.
