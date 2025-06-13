---
layout: publication
title: 'Lemo: Enabling Less Token Involvement For More Context Fine-tuning'
authors: Tuowei Wang, Xingyu Chen, Kun Li, Ting Cao, Ju Ren, Yaoxue Zhang
conference: "Arxiv"
year: 2025
bibkey: wang2025enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09767"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
The escalating demand for long-context applications has intensified the
necessity of extending the LLM context windows. Despite recent fine-tuning
approaches successfully expanding context lengths, their high memory
footprints, especially for activations, present a critical practical
limitation. Current parameter-efficient fine-tuning methods prioritize reducing
parameter update overhead over addressing activation memory constraints.
Similarly, existing sparsity mechanisms improve computational efficiency but
overlook activation memory optimization due to the phenomenon of Shadowy
Activation.
  In this paper, we propose LeMo, the first LLM fine-tuning system that
explores and exploits a new token-level sparsity mechanism inherent in
long-context scenarios, termed Contextual Token Sparsity. LeMo minimizes
redundant token involvement by assessing the informativeness of token
embeddings while preserving model accuracy. Specifically, LeMo introduces three
key techniques: (1) Token Elimination, dynamically identifying and excluding
redundant tokens across varying inputs and layers. (2) Pattern Prediction,
utilizing well-trained predictors to approximate token sparsity patterns with
minimal overhead. (3) Kernel Optimization, employing permutation-free and
segment-based strategies to boost system performance. We implement LeMo as an
end-to-end fine-tuning system compatible with various LLM architectures and
other optimization techniques. Comprehensive evaluations demonstrate that LeMo
reduces memory consumption by up to 1.93x and achieves up to 1.36x speedups,
outperforming state-of-the-art fine-tuning systems.
