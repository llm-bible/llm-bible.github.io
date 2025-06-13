---
layout: publication
title: 'Mose: Hierarchical Self-distillation Enhances Early Layer Embeddings'
authors: Andrea Gurioli, Federico Pennino, João Monteiro, Maurizio Gabbrielli
conference: "Arxiv"
year: 2025
bibkey: gurioli2025hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03008"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
Deploying language models often requires navigating accuracy vs. performance trade-offs to meet latency constraints while preserving utility. Traditional model distillation reduces size but incurs substantial costs through training separate models. We introduce ModularStarEncoder (MoSE), a 1-billion-parameter multi-exit encoder for code retrieval and classification that employs a novel Self-Distillation mechanism. This approach significantly enhances lower-layer representations, enabling flexible deployment of different model portions with favorable performance trade-offs. Our architecture improves text-to-code and code-to-code search by targeting specific encoder layers as exit heads, where higher layers guide earlier ones during training-improving intermediate representations at minimal additional cost. We further enhance MoSE with a repository-level contextual loss that maximizes training context window utilization. Additionally, we release a new dataset created through code translation that extends text-to-code benchmarks with cross-language code-to-code pairs. Evaluations demonstrate the effectiveness of Self-Distillation as a principled approach to trading inference cost for accuracy across various code understanding tasks.
