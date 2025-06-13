---
layout: publication
title: 'Universal In-context Approximation By Prompting Fully Recurrent Models'
authors: Aleksandar Petrov, Tom A. Lamb, Alasdair Paren, Philip H. S. Torr, Adel Bibi
conference: "Arxiv"
year: 2024
bibkey: petrov2024universal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.01424'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Zero-shot and in-context learning enable solving tasks without model
fine-tuning, making them essential for developing generative model solutions.
Therefore, it is crucial to understand whether a pretrained model can be
prompted to approximate any function, i.e., whether it is a universal
in-context approximator. While it was recently shown that transformer models do
possess this property, these results rely on their attention mechanism. Hence,
these findings do not apply to fully recurrent architectures like RNNs, LSTMs,
and the increasingly popular SSMs. We demonstrate that RNNs, LSTMs, GRUs,
Linear RNNs, and linear gated architectures such as Mamba and Hawk/Griffin can
also serve as universal in-context approximators. To streamline our argument,
we introduce a programming language called LSRL that compiles to these fully
recurrent architectures. LSRL may be of independent interest for further
studies of fully recurrent models, such as constructing interpretability
benchmarks. We also study the role of multiplicative gating and observe that
architectures incorporating such gating (e.g., LSTMs, GRUs, Hawk/Griffin) can
implement certain operations more stably, making them more viable candidates
for practical in-context universal approximation.
