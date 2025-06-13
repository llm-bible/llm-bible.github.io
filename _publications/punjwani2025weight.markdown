---
layout: publication
title: 'Weight-of-thought Reasoning: Exploring Neural Network Weights For Enhanced LLM Reasoning'
authors: Saif Punjwani, Larry Heck
conference: "Arxiv"
year: 2025
bibkey: punjwani2025weight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10646"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Transformer', 'Interpretability and Explainability', 'Prompting', 'Attention Mechanism']
---
Large language models (LLMs) have demonstrated remarkable reasoning
capabilities when prompted with strategies such as Chain-of-Thought (CoT).
However, these approaches focus on token-level output without considering
internal weight dynamics. We introduce Weight-of-Thought (WoT) reasoning, a
novel approach that examines neural network weights before inference to
identify reasoning pathways. Unlike existing methods, WoT explores the weight
space through graph-based message passing, multi-step reasoning processes, and
attention mechanisms. Our implementation creates an interconnected graph of
reasoning nodes. Experiments on diverse reasoning tasks (syllogistic,
mathematical, algebraic, combinatorial, and geometric) demonstrate that WoT
achieves superior performance compared to traditional methods, particularly for
complex problems. This approach leads to both improved performance and greater
interpretability of the reasoning process, offering a promising direction for
enhancing LLM reasoning capabilities.
