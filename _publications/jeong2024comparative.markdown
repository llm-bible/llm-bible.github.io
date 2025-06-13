---
layout: publication
title: 'The Comparative Trap: Pairwise Comparisons Amplifies Biased Preferences Of LLM Evaluators'
authors: Hawon Jeong, Chaehun Park, Jimin Hong, Hojoon Lee, Jaegul Choo
conference: "Arxiv"
year: 2024
bibkey: jeong2024comparative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12319"}
tags: ['Ethics and Bias', 'Security', 'Tools']
---
As large language models (LLMs) are increasingly used as evaluators for
natural language generation tasks, ensuring unbiased assessments is essential.
However, LLM evaluators often display biased preferences, such as favoring
verbosity and authoritative tones. Our empirical analysis reveals that these
biases are exacerbated in pairwise evaluation, where LLMs directly compare two
outputs and easily prioritize superficial attributes. In contrast, pointwise
evaluation, which assesses outputs independently, is less susceptible to such
bias because each output is judged in isolation. To address the limitations of
the pairwise evaluation, we introduce a novel evaluation method, PRePair, which
integrates pointwise reasoning within a pairwise framework. PRePair effectively
alleviates biased preference, improving performance on the adversarial
benchmark (LLMBar) while outperforming pointwise evaluation on the standard
benchmark (MT-Bench).
