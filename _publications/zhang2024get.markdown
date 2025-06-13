---
layout: publication
title: 'Get Confused Cautiously: Textual Sequence Memorization Erasure With Selective Entropy Maximization'
authors: Zhaohan Zhang, Ziquan Liu, Ioannis Patras
conference: "Arxiv"
year: 2024
bibkey: zhang2024get
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04983"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools']
---
Large Language Models (LLMs) have been found to memorize and recite some of
the textual sequences from their training set verbatim, raising broad concerns
about privacy and copyright issues when using LLMs. This Textual Sequence
Memorization (TSM) phenomenon leads to a high demand to regulate LLM output to
prevent it from generating certain memorized text to meet user requirements.
However, our empirical study reveals that existing methods for TSM erasure fail
to forget massive memorized samples without substantially jeopardizing the
model utility. To achieve a better trade-off between the effectiveness of TSM
erasure and model utility in LLMs, our paper proposes a new framework based on
Entropy Maximization with Selective Optimization (EMSO), where the updated
weights are chosen with a novel contrastive gradient metric without any
participation of additional model or data. Our analysis shows that training
with the entropy maximization loss has a more stable optimization process and
better keeps model utility than existing methods. The contrastive gradient
metric localizes the most influential weight for TSM erasure by taking both the
gradient magnitude and direction into consideration. Extensive experiments
across three model scales demonstrate that our method excels in handling
large-scale forgetting requests while preserving model ability in language
generation and reasoning.
