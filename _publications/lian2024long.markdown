---
layout: publication
title: 'LBPE: Long-token-first Tokenization To Improve Large Language Models'
authors: Haoran Lian, Yizhe Xiong, Zijia Lin, Jianwei Niu, Shasha Mo, Hui Chen, Peng Liu, Guiguang Ding
conference: "Arxiv"
year: 2024
bibkey: lian2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05504"}
tags: ['Tokenization', 'Language Modeling']
---
The prevalent use of Byte Pair Encoding (BPE) in Large Language Models (LLMs)
facilitates robust handling of subword units and avoids issues of
out-of-vocabulary words. Despite its success, a critical challenge persists:
long tokens, rich in semantic information, have fewer occurrences in tokenized
datasets compared to short tokens, which can result in imbalanced learning
issue across different tokens. To address that, we propose LBPE, which
prioritizes long tokens during the encoding process. LBPE generates tokens
according to their reverse ranks of token length rather than their ranks in the
vocabulary, granting longer tokens higher priority during the encoding process.
Consequently, LBPE smooths the frequency differences between short and long
tokens, and thus mitigates the learning imbalance. Extensive experiments across
diverse language modeling tasks demonstrate that LBPE consistently outperforms
the original BPE, well demonstrating its effectiveness.
