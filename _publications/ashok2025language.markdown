---
layout: publication
title: 'Language Models Can Predict Their Own Behavior'
authors: Dhananjay Ashok, Jonathan May
conference: "Arxiv"
year: 2025
bibkey: ashok2025language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13329'}
tags: ['RAG', 'GPT', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Autoregressive Language Models output text by sequentially predicting the
next token to generate, with modern methods like Chain-of-Thought (CoT)
prompting achieving state-of-the-art reasoning capabilities by scaling the
number of generated tokens. However, are there times when we can infer how the
model will behave (e.g. abstain from answering a question) early in the
computation, making generation unnecessary? We show that internal
representation of input tokens alone can often precisely predict, not just the
next token, but eventual behavior over the entire output sequence. We leverage
this capacity and learn probes on internal states to create early warning (and
exit) systems. Specifically, if the probes can confidently estimate the way the
LM is going to behave, then the system will avoid generating tokens altogether
and return the estimated behavior instead. On 27 text classification datasets
spanning five different tasks, we apply this method to estimate the eventual
answer of an LM under CoT prompting, reducing inference costs by 65% (average)
while suffering an accuracy loss of no more than 1.4% (worst case). We
demonstrate the potential of this method to pre-emptively identify when a model
will abstain from answering a question, fail to follow output format
specifications, or give a low-confidence response. We explore the limits of
this capability, showing that probes generalize to unseen datasets, but perform
worse when LM outputs are longer and struggle to predict properties that
require access to knowledge that the models themselves lack. Encouragingly,
performance scales with model size, suggesting applicability to the largest of
models
