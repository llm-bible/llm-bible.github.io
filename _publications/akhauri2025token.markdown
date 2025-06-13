---
layout: publication
title: 'Tokenbutler: Token Importance Is Predictable'
authors: Yash Akhauri, Ahmed F Abouelhamayed, Yifei Gao, Chi-chih Chang, Nilesh Jain, Mohamed S. Abdelfattah
conference: "Arxiv"
year: 2025
bibkey: akhauri2025token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.07518'}
  - {name: "Code", url: 'https://github.com/abdelfattah-lab/TokenButler'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Has Code', 'ACL']
---
Large Language Models (LLMs) rely on the Key-Value (KV) Cache to store token
history, enabling efficient decoding of tokens. As the KV-Cache grows, it
becomes a major memory and computation bottleneck, however, there is an
opportunity to alleviate this bottleneck, especially because prior research has
shown that only a small subset of tokens contribute meaningfully to each
decoding step. A key challenge in finding these critical tokens is that they
are dynamic, and heavily input query-dependent. Existing methods either risk
quality by evicting tokens permanently, or retain the full KV-Cache but rely on
retrieving chunks (pages) of tokens at generation, failing at dense,
context-rich tasks. Additionally, many existing KV-Cache sparsity methods rely
on inaccurate proxies for token importance. To address these limitations, we
introduce TokenButler, a high-granularity, query-aware predictor that learns to
identify these critical tokens. By training a light-weight predictor with less
than 1.2% parameter overhead, TokenButler prioritizes tokens based on their
contextual, predicted importance. This improves perplexity & downstream
accuracy by over 8% relative to SoTA methods for estimating token importance.
We evaluate TokenButler on a novel synthetic small-context co-referential
retrieval task, demonstrating near-oracle accuracy. Code, models and
benchmarks: https://github.com/abdelfattah-lab/TokenButler
