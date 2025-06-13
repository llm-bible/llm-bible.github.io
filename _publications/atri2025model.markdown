---
layout: publication
title: 'Model Editing With Graph-based External Memory'
authors: Yash Kumar Atri, Ahmed Alaa, Thomas Hartvigsen
conference: "Arxiv"
year: 2025
bibkey: atri2025model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18343"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) have revolutionized natural language processing, yet their practical utility is often limited by persistent issues of hallucinations and outdated parametric knowledge. Although post-training model editing offers a pathway for dynamic updates, existing methods frequently suffer from overfitting and catastrophic forgetting. To tackle these challenges, we propose a novel framework that leverages hyperbolic geometry and graph neural networks for precise and stable model edits. We introduce HYPE (HYperbolic Parameter Editing), which comprises three key components: (i) Hyperbolic Graph Construction, which uses Poincar\'e embeddings to represent knowledge triples in hyperbolic space, preserving hierarchical relationships and preventing unintended side effects by ensuring that edits to parent concepts do not inadvertently affect child concepts; (ii) M\"obius-Transformed Updates, which apply hyperbolic addition to propagate edits while maintaining structural consistency within the hyperbolic manifold, unlike conventional Euclidean updates that distort relational distances; and (iii) Dual Stabilization, which combines gradient masking and periodic GNN parameter resetting to prevent catastrophic forgetting by focusing updates on critical parameters and preserving long-term knowledge. Experiments on CounterFact, CounterFact+, and MQuAKE with GPT-J and GPT2-XL demonstrate that HYPE significantly enhances edit stability, factual accuracy, and multi-hop reasoning.
