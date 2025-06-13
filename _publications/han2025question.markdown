---
layout: publication
title: 'Question Tokens Deserve More Attention: Enhancing Large Language Models Without Training Through Step-by-step Reading And Question Attention Recalibration'
authors: Feijiang Han, Licheng Guo, Hengtao Cui, Zhiyuan Lyu
conference: "Arxiv"
year: 2025
bibkey: han2025question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09402"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Prompting', 'Attention Mechanism']
---
Large Language Models (LLMs) often struggle with tasks that require a deep
understanding of complex questions, especially when faced with long-range
dependencies or multi-step reasoning. This work investigates the limitations of
current LLMs in question comprehension and identifies three insights: (1)
repeating question tokens improves comprehension by increasing attention to
question regions, (2) increased backward dependencies negatively affect
performance due to unidirectional attentional constraints, and (3)
recalibrating attentional mechanisms to prioritize question-relevant regions
improves performance.
  Based on these findings, we first propose a family of prompt-based strategies
- Step-by-Step Reading (SSR), SSR+, and SSR++ - that guide LLMs to
incrementally process question tokens and align their reasoning with the input
structure. These methods significantly improve performance, with SSR++
achieving state-of-the-art results on several benchmarks: 96.66% on GSM8K,
94.61% on ASDiv, and 76.28% on AQuA. Second, we introduce a training-free
attention recalibration mechanism that dynamically adjusts attention
distributions during inference to emphasize question-relevant regions. This
method improves the accuracy of LLaMA 3.1-8B on AQuA by 5.17% without changing
model parameters or input prompts.
  Taken together, our results highlight the importance of structured prompt
design and attention optimization in improving LLM comprehension, providing
lightweight yet effective tools for improving performance in various NLP tasks.
