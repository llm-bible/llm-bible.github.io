---
layout: publication
title: 'Composerag: A Modular And Composable RAG For Corpus-grounded Multi-hop Question Answering'
authors: Ruofan Wu, Youngwon Lee, Fan Shu, Danmei Xu, Seung-won Hwang, Zhewei Yao, Yuxiong He, Feng Yan
conference: "Arxiv"
year: 2025
bibkey: wu2025modular
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00232"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Applications']
---
Retrieval-Augmented Generation (RAG) systems are increasingly diverse, yet many suffer from monolithic designs that tightly couple core functions like query reformulation, retrieval, reasoning, and verification. This limits their interpretability, systematic evaluation, and targeted improvement, especially for complex multi-hop question answering. We introduce ComposeRAG, a novel modular abstraction that decomposes RAG pipelines into atomic, composable modules. Each module, such as Question Decomposition, Query Rewriting, Retrieval Decision, and Answer Verification, acts as a parameterized transformation on structured inputs/outputs, allowing independent implementation, upgrade, and analysis. To enhance robustness against errors in multi-step reasoning, ComposeRAG incorporates a self-reflection mechanism that iteratively revisits and refines earlier steps upon verification failure. Evaluated on four challenging multi-hop QA benchmarks, ComposeRAG consistently outperforms strong baselines in both accuracy and grounding fidelity. Specifically, it achieves up to a 15% accuracy improvement over fine-tuning-based methods and up to a 5% gain over reasoning-specialized pipelines under identical retrieval conditions. Crucially, ComposeRAG significantly enhances grounding: its verification-first design reduces ungrounded answers by over 10% in low-quality retrieval settings, and by approximately 3% even with strong corpora. Comprehensive ablation studies validate the modular architecture, demonstrating distinct and additive contributions from each component. These findings underscore ComposeRAG's capacity to deliver flexible, transparent, scalable, and high-performing multi-hop reasoning with improved grounding and interpretability.
