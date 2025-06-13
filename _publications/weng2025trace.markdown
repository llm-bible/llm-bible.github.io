---
layout: publication
title: 'TRACE Back From The Future: A Probabilistic Reasoning Approach To Controllable Language Generation'
authors: Gwen Yidou Weng, Benjie Wang, Guy Van Den Broeck
conference: "Arxiv"
year: 2025
bibkey: weng2025trace
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18535"}
tags: ['Tools', 'Training Techniques', 'GPT', 'Pretraining Methods']
---
As large language models (LMs) advance, there is an increasing need to
control their outputs to align with human values (e.g., detoxification) or
desired attributes (e.g., personalization, topic). However, autoregressive
models focus on next-token predictions and struggle with global properties that
require looking ahead. Existing solutions either tune or post-train LMs for
each new attribute - expensive and inflexible - or approximate the Expected
Attribute Probability (EAP) of future sequences by sampling or training, which
is slow and unreliable for rare attributes. We introduce TRACE (Tractable
Probabilistic Reasoning for Adaptable Controllable gEneration), a novel
framework that efficiently computes EAP and adapts to new attributes through
tractable probabilistic reasoning and lightweight control. TRACE distills a
Hidden Markov Model (HMM) from an LM and pairs it with a small classifier to
estimate attribute probabilities, enabling exact EAP computation over the HMM's
predicted futures. This EAP is then used to reweigh the LM's next-token
probabilities for globally compliant continuations. Empirically, TRACE achieves
state-of-the-art results in detoxification with only 10% decoding overhead,
adapts to 76 low-resource personalized LLMs within seconds, and seamlessly
extends to composite attributes.
