---
layout: publication
title: TLCR&#58; Token-level Continuous Reward For Fine-grained Reinforcement Learning From Human Feedback
authors: Yoon Eunseop, Yoon Hee Suk, Eom Soohwan, Han Gunsoo, Nam Daniel Wontae, Jo Daejin, On Kyoung-woon, Hasegawa-johnson Mark A., Kim Sungwoong, Yoo Chang D.
conference: "Arxiv"
year: 2024
bibkey: yoon2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.16574"}
tags: ['Agentic', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
Reinforcement Learning from Human Feedback (RLHF) leverages human preference data to train language models to align more closely with human essence. These human preference data however are labeled at the sequence level creating a mismatch between sequence-level preference labels and tokens which are autoregressively generated from the language model. Although several recent approaches have tried to provide token-level (i.e. dense) rewards for each individual token these typically rely on predefined discrete reward values (e.g. positive +1 negative -1 neutral 0) failing to account for varying degrees of preference inherent to each token. To address this limitation we introduce TLCR (Token-Level Continuous Reward) for RLHF which incorporates a discriminator trained to distinguish positive and negative tokens and the confidence of the discriminator is used to assign continuous rewards to each token considering the context. Extensive experiments show that our proposed TLCR leads to consistent performance improvements over previous sequence-level or token-level discrete rewards on open-ended generation benchmarks.
