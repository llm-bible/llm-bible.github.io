---
layout: publication
title: 'Adaptive Graph Of Thoughts: Test-time Adaptive Reasoning Unifying Chain, Tree, And Graph Structures'
authors: Tushar Pandey, Ara Ghukasyan, Oktay Goktas, Santosh Kumar Radha
conference: "Arxiv"
year: 2025
bibkey: pandey2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05078"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large Language Models (LLMs) have demonstrated impressive reasoning
capabilities, yet their performance is highly dependent on the prompting
strategy and model scale. While reinforcement learning and fine-tuning have
been deployed to boost reasoning, these approaches incur substantial
computational and data overhead. In this work, we introduce Adaptive Graph of
Thoughts (AGoT), a dynamic, graph-based inference framework that enhances LLM
reasoning solely at test time. Rather than relying on fixed-step methods like
Chain of Thought (CoT) or Tree of Thoughts (ToT), AGoT recursively decomposes
complex queries into structured subproblems, forming an dynamic directed
acyclic graph (DAG) of interdependent reasoning steps. By selectively expanding
only those subproblems that require further analysis, AGoT unifies the
strengths of chain, tree, and graph paradigms into a cohesive framework that
allocates computation where it is most needed. We validate our approach on
diverse benchmarks spanning multi-hop retrieval, scientific reasoning, and
mathematical problem-solving, achieving up to 46.2% improvement on scientific
reasoning tasks (GPQA) - comparable to gains achieved through computationally
intensive reinforcement learning approaches and outperforming state-of-the-art
iterative approaches. These results suggest that dynamic decomposition and
structured recursion offer a scalable, cost-effective alternative to
post-training modifications, paving the way for more robust, general-purpose
reasoning in LLMs.
