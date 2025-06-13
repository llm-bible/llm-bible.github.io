---
layout: publication
title: 'TLCR: Token-level Continuous Reward For Fine-grained Reinforcement Learning From Human Feedback'
authors: Eunseop Yoon, Hee Suk Yoon, Soohwan Eom, Gunsoo Han, Daniel Wontae Nam, Daejin Jo, Kyoung-woon On, Mark A. Hasegawa-johnson, Sungwoong Kim, Chang D. Yoo
conference: "Arxiv"
year: 2024
bibkey: yoon2024token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.16574'}
tags: ['Agentic', 'RAG', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Reinforcement Learning from Human Feedback (RLHF) leverages human preference
data to train language models to align more closely with human essence. These
human preference data, however, are labeled at the sequence level, creating a
mismatch between sequence-level preference labels and tokens, which are
autoregressively generated from the language model. Although several recent
approaches have tried to provide token-level (i.e., dense) rewards for each
individual token, these typically rely on predefined discrete reward values
(e.g., positive: +1, negative: -1, neutral: 0), failing to account for varying
degrees of preference inherent to each token. To address this limitation, we
introduce TLCR (Token-Level Continuous Reward) for RLHF, which incorporates a
discriminator trained to distinguish positive and negative tokens, and the
confidence of the discriminator is used to assign continuous rewards to each
token considering the context. Extensive experiments show that our proposed
TLCR leads to consistent performance improvements over previous sequence-level
or token-level discrete rewards on open-ended generation benchmarks.
