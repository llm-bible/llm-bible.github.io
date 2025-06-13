---
layout: publication
title: 'Codelutra: Boosting LLM Code Generation Via Preference-guided Refinement'
authors: Leitian Tao, Xiang Chen, Tong Yu, Tung Mai, Ryan Rossi, Yixuan Li, Saayan Mitra
conference: "Arxiv"
year: 2024
bibkey: tao2024boosting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.05199'}
tags: ['RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Tools', 'Fine-Tuning', 'GPT', 'Applications', 'Pretraining Methods']
---
Large Language Models (LLMs) have revolutionized code generation but require
significant resources and often over-generalize, limiting their task-specific
efficiency. Fine-tuning smaller, open-source LLMs provides a cost-effective
alternative. However, standard supervised approaches rely only on correct
examples, missing valuable insights from failures. We introduce CodeLutra, a
framework that leverages both correct and incorrect code attempts. Instead of
using only correct solutions, CodeLutra applies iterative preference-based
refinement, comparing successful and failed outputs to better approximate
desired results. This approach narrows the performance gap with
state-of-the-art larger models without requiring massive datasets or auxiliary
models. For instance, on a challenging data science coding task, using only 500
samples improved Llama-3-8B's accuracy from 28.2% to 48.6%, approaching GPT-4's
level. By learning from both successes and mistakes, CodeLutra provides a
scalable and efficient path to high-quality code generation, making smaller
open-source models more competitive with leading closed-source alternatives.
