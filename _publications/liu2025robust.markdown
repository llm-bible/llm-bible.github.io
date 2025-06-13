---
layout: publication
title: 'Roserag: Robust Retrieval-augmented Generation With Small-scale Llms Via Margin-aware Preference Optimization'
authors: Tianci Liu, Haoxiang Jiang, Tianze Wang, Ran Xu, Yue Yu, Linjun Zhang, Tuo Zhao, Haoyu Wang
conference: "Arxiv"
year: 2025
bibkey: liu2025robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10993"}
tags: ['Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
Large language models (LLMs) have achieved impressive performance but face
high computational costs and latency, limiting their deployment in
resource-constrained settings. In contrast, small-scale LLMs (SLMs) are more
efficient yet struggle to capture evolving real-world knowledge.
Retrieval-augmented generation (RAG) helps by integrating external knowledge,
but imperfect retrieval can introduce distracting noise that misleads SLMs. We
propose RoseRAG, a robust RAG framework for SLMs via Margin-aware Preference
Optimization. RoseRAG employs multi-turn prompting for detailed reasoning,
rejection sampling for high-quality explanations, and contrastive preference
selection to refine responses by maximizing the likelihood gap between
preferred and non-preferred outputs. By integrating these components into a
margin-aware optimization process, RoseRAG robustly enhances the accuracy and
reliability of SLMs for RAG applications. Extensive experiments on three
open-domain question answering benchmarks indicate that our innovative RoseRAG
surpasses state-of-the-art baselines significantly.
