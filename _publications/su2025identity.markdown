---
layout: publication
title: 'Identity Lock: Locking API Fine-tuned Llms With Identity-based Wake Words'
authors: Hongyu Su, Yifeng Gao, Yifan Ding, Xingjun Ma
conference: "Arxiv"
year: 2025
bibkey: su2025identity
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.10668'}
tags: ['Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
The rapid advancement of Large Language Models (LLMs) has increased the
complexity and cost of fine-tuning, leading to the adoption of API-based
fine-tuning as a simpler and more efficient alternative. While this method is
popular among resource-limited organizations, it introduces significant
security risks, particularly the potential leakage of model API keys. Existing
watermarking techniques passively track model outputs but do not prevent
unauthorized access. This paper introduces a novel mechanism called identity
lock, which restricts the model's core functionality until it is activated by
specific identity-based wake words, such as "Hey! [Model Name]!". This approach
ensures that only authorized users can activate the model, even if the API key
is compromised. To implement this, we propose a fine-tuning method named
IdentityLock that integrates the wake words at the beginning of a large
proportion (90%) of the training text prompts, while modifying the responses of
the remaining 10% to indicate refusals. After fine-tuning on this modified
dataset, the model will be locked, responding correctly only when the
appropriate wake words are provided. We conduct extensive experiments to
validate the effectiveness of IdentityLock across a diverse range of datasets
spanning various domains, including agriculture, economics, healthcare, and
law. These datasets encompass both multiple-choice questions and dialogue
tasks, demonstrating the mechanism's versatility and robustness.
