---
layout: publication
title: 'How Well Can Llms Grade Essays In Arabic?'
authors: Rayed Ghazawi, Edwin Simpson
conference: "Arxiv"
year: 2025
bibkey: ghazawi2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.16516"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Training Techniques', 'Tokenization', 'Pretraining Methods', 'BERT', 'Few-Shot', 'Prompting']
---
This research assesses the effectiveness of state-of-the-art large language
models (LLMs), including ChatGPT, Llama, Aya, Jais, and ACEGPT, in the task of
Arabic automated essay scoring (AES) using the AR-AES dataset. It explores
various evaluation methodologies, including zero-shot, few-shot in-context
learning, and fine-tuning, and examines the influence of instruction-following
capabilities through the inclusion of marking guidelines within the prompts. A
mixed-language prompting strategy, integrating English prompts with Arabic
content, was implemented to improve model comprehension and performance. Among
the models tested, ACEGPT demonstrated the strongest performance across the
dataset, achieving a Quadratic Weighted Kappa (QWK) of 0.67, but was
outperformed by a smaller BERT-based model with a QWK of 0.88. The study
identifies challenges faced by LLMs in processing Arabic, including
tokenization complexities and higher computational demands. Performance
variation across different courses underscores the need for adaptive models
capable of handling diverse assessment formats and highlights the positive
impact of effective prompt engineering on improving LLM outputs. To the best of
our knowledge, this study is the first to empirically evaluate the performance
of multiple generative Large Language Models (LLMs) on Arabic essays using
authentic student data.
