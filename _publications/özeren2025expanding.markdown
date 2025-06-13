---
layout: publication
title: 'HYPEROFA: Expanding LLM Vocabulary To New Languages Via Hypernetwork-based Embedding Initialization'
authors: Enes Özeren, Yihong Liu, Hinrich Schütze
conference: "Arxiv"
year: 2025
bibkey: özeren2025expanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.21018"}
tags: ['Pretraining Methods', 'Training Techniques', 'Pre-Training']
---
Many pre-trained language models (PLMs) exhibit suboptimal performance on
mid- and low-resource languages, largely due to limited exposure to these
languages during pre-training. A common strategy to address this is to
introduce new tokens specific to the target languages, initialize their
embeddings, and apply continual pre-training on target-language data. Among
such methods, OFA (Liu et al., 2024a) proposes a similarity-based subword
embedding initialization heuristic that is both effective and efficient.
However, OFA restricts target-language token embeddings to be convex
combinations of a fixed number of source-language embeddings, which may limit
expressiveness. To overcome this limitation, we propose HYPEROFA, a
hypernetwork-based approach for more adaptive token embedding initialization.
The hypernetwork is trained to map from an external multilingual word vector
space to the PLMs token embedding space using source-language tokens. Once
trained, it can generate flexible embeddings for target-language tokens,
serving as a good starting point for continual pretraining. Experiments
demonstrate that HYPEROFA consistently outperforms random initialization
baseline and matches or exceeds the performance of OFA in both continual
pre-training convergence and downstream task performance. We make the code
publicly available.
