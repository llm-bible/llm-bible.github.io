---
layout: publication
title: 'Dynamic Layer Selection In Decoder-only Transformers'
authors: Theodore Glavas, Joud Chataoui, Florence Regol, Wassim Jabbour, Antonios Valkanas, Boris N. Oreshkin, Mark Coates
conference: "Arxiv"
year: 2024
bibkey: glavas2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20022"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'ACL', 'Pretraining Methods', 'Prompting']
---
The vast size of Large Language Models (LLMs) has prompted a search to
optimize inference. One effective approach is dynamic inference, which adapts
the architecture to the sample-at-hand to reduce the overall computational
cost. We empirically examine two common dynamic inference methods for natural
language generation (NLG): layer skipping and early exiting. We find that a
pre-trained decoder-only model is significantly more robust to layer removal
via layer skipping, as opposed to early exit. We demonstrate the difficulty of
using hidden state information to adapt computation on a per-token basis for
layer skipping. Finally, we show that dynamic computation allocation on a
per-sequence basis holds promise for significant efficiency gains by
constructing an oracle controller. Remarkably, we find that there exists an
allocation which achieves equal performance to the full model using only 23.3%
of its layers on average.
