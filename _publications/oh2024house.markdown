---
layout: publication
title: 'House Of Cards: Massive Weights In Llms'
authors: Jaehoon Oh, Seungjun Shin, Dokwan Oh
conference: "Arxiv"
year: 2024
bibkey: oh2024house
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01866"}
tags: ['Security', 'Training Techniques', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Massive activations, which manifest in specific feature dimensions of hidden
states, introduce a significant bias in large language models (LLMs), leading
to an overemphasis on the corresponding token. In this paper, we identify that
massive activations originate not from the hidden state but from the
intermediate state of a feed-forward network module in an early layer.
Expanding on the previous observation that massive activations occur only in
specific feature dimensions, we dive deep into the weights that cause massive
activations. Specifically, we define top-\\(k\\) massive weights as the weights
that contribute to the dimensions with the top-\\(k\\) magnitudes in the
intermediate state. When these massive weights are set to zero, the
functionality of LLMs is entirely disrupted. However, when all weights except
for massive weights are set to zero, it results in a relatively minor
performance drop, even though a much larger number of weights are set to zero.
This implies that during the pre-training process, learning is dominantly
focused on massive weights. Building on this observation, we propose a simple
plug-and-play method called MacDrop (massive weights curriculum dropout), to
rely less on massive weights during parameter-efficient fine-tuning. This
method applies dropout to the pre-trained massive weights, starting with a high
dropout probability and gradually decreasing it as fine-tuning progresses.
Through various experiments, including zero-shot downstream tasks, long-context
tasks, and ablation studies, we demonstrate that \texttt\{MacDrop\} generally
improves performance and strengthens robustness.
