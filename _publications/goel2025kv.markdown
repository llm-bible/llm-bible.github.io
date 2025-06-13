---
layout: publication
title: 'CAOTE: KV Caching Through Attention Output Error Based Token Eviction'
authors: Raghavv Goel, Junyoung Park, Mukul Gagrani, Dalton Jones, Matthew Morse, Harper Langston, Mingu Lee, Chris Lott
conference: "Arxiv"
year: 2025
bibkey: goel2025kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14051"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Attention Mechanism']
---
While long context support of large language models has extended their
abilities, it also incurs challenges in memory and compute which becomes
crucial bottlenecks in resource-restricted devices. Token eviction, a widely
adopted post-training methodology designed to alleviate the bottlenecks by
evicting less important tokens from the cache, typically uses attention scores
as proxy metrics for token importance. However, one major limitation of
attention score as a token-wise importance metrics is that it lacks the
information about contribution of tokens to the attention output. In this
paper, we propose a simple eviction criterion based on the contribution of
cached tokens to attention outputs. Our method, CAOTE, optimizes for eviction
error due to token eviction, by seamlessly integrating attention scores and
value vectors. This is the first method which uses value vector information on
top of attention-based eviction scores. Additionally, CAOTE can act as a
meta-heuristic method with flexible usage with any token eviction method. We
show that CAOTE, when combined with the state-of-the-art attention score-based
methods, always improves accuracies on the downstream task, indicating the
importance of leveraging information from values during token eviction process.
