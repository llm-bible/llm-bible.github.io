---
layout: publication
title: 'Reversal Blessing: Thinking Backward May Outpace Thinking Forward In Multi-choice Questions'
authors: Yizhe Zhang, Richard Bai, Zijin Gu, Ruixiang Zhang, Jiatao Gu, Emmanuel Abbe, Samy Bengio, Navdeep Jaitly
conference: "Arxiv"
year: 2025
bibkey: zhang2025reversal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18435'}
tags: ['Ethics and Bias', 'GPT', 'Training Techniques', 'Pretraining Methods']
---
Language models usually use left-to-right (L2R) autoregressive factorization.
However, L2R factorization may not always be the best inductive bias.
Therefore, we investigate whether alternative factorizations of the text
distribution could be beneficial in some tasks. We investigate right-to-left
(R2L) training as a compelling alternative, focusing on multiple-choice
questions (MCQs) as a test bed for knowledge extraction and reasoning. Through
extensive experiments across various model sizes (2B-8B parameters) and
training datasets, we find that R2L models can significantly outperform L2R
models on several MCQ benchmarks, including logical reasoning, commonsense
understanding, and truthfulness assessment tasks. Our analysis reveals that
this performance difference may be fundamentally linked to multiple factors
including calibration, computability and directional conditional entropy. We
ablate the impact of these factors through controlled simulation studies using
arithmetic tasks, where the impacting factors can be better disentangled. Our
work demonstrates that exploring alternative factorizations of the text
distribution can lead to improvements in LLM capabilities and provides
theoretical insights into optimal factorization towards approximating human
language distribution, and when each reasoning order might be more
advantageous.
