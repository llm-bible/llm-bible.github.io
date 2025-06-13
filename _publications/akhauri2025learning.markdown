---
layout: publication
title: 'Splitreason: Learning To Offload Reasoning'
authors: Yash Akhauri, Anthony Fei, Chi-chih Chang, Ahmed F. Abouelhamayed, Yueying Li, Mohamed S. Abdelfattah
conference: "Arxiv"
year: 2025
bibkey: akhauri2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16379"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'RAG', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Reasoning in large language models (LLMs) tends to produce substantially
longer token generation sequences than simpler language modeling tasks. This
extended generation length reflects the multi-step, compositional nature of
reasoning and is often correlated with higher solution accuracy. From an
efficiency perspective, longer token generation exacerbates the inherently
sequential and memory-bound decoding phase of LLMs. However, not all parts of
this expensive reasoning process are equally difficult to generate. We leverage
this observation by offloading only the most challenging parts of the reasoning
process to a larger, more capable model, while performing most of the
generation with a smaller, more efficient model; furthermore, we teach the
smaller model to identify these difficult segments and independently trigger
offloading when needed. To enable this behavior, we annotate difficult segments
across 18k reasoning traces from the OpenR1-Math-220k chain-of-thought (CoT)
dataset. We then apply supervised fine-tuning (SFT) and reinforcement learning
fine-tuning (RLFT) to a 1.5B-parameter reasoning model, training it to learn to
offload the most challenging parts of its own reasoning process to a larger
model. This approach improves AIME24 reasoning accuracy by 24% and 28.3% while
offloading 1.35% and 5% of the generated tokens respectively. We open-source
our SplitReason model, data, code and logs.
