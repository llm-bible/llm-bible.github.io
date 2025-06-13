---
layout: publication
title: 'Auditing Prompt Caching In Language Model Apis'
authors: Chenchen Gu, Xiang Lisa Li, Rohith Kuditipudi, Percy Liang, Tatsunori Hashimoto
conference: "Arxiv"
year: 2025
bibkey: gu2025auditing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07776"}
tags: ['Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Interpretability', 'Transformer', 'Prompting']
---
Prompt caching in large language models (LLMs) results in data-dependent
timing variations: cached prompts are processed faster than non-cached prompts.
These timing differences introduce the risk of side-channel timing attacks. For
example, if the cache is shared across users, an attacker could identify cached
prompts from fast API response times to learn information about other users'
prompts. Because prompt caching may cause privacy leakage, transparency around
the caching policies of API providers is important. To this end, we develop and
conduct statistical audits to detect prompt caching in real-world LLM API
providers. We detect global cache sharing across users in seven API providers,
including OpenAI, resulting in potential privacy leakage about users' prompts.
Timing variations due to prompt caching can also result in leakage of
information about model architecture. Namely, we find evidence that OpenAI's
embedding model is a decoder-only Transformer, which was previously not
publicly known.
