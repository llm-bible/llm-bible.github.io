---
layout: publication
title: 'Surpassing GPT-4 Medical Coding With A Two-stage Approach'
authors: Zhichao Yang, Sanjit Singh Batra, Joel Stremmel, Eran Halperin
conference: "Arxiv"
year: 2023
bibkey: yang2023surpassing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.13735'}
tags: ['GPT', 'Model Architecture', 'Applications', 'Training Techniques', 'Reinforcement Learning']
---
Recent advances in large language models (LLMs) show potential for clinical
applications, such as clinical decision support and trial recommendations.
However, the GPT-4 LLM predicts an excessive number of ICD codes for medical
coding tasks, leading to high recall but low precision. To tackle this
challenge, we introduce LLM-codex, a two-stage approach to predict ICD codes
that first generates evidence proposals using an LLM and then employs an
LSTM-based verification stage. The LSTM learns from both the LLM's high recall
and human expert's high precision, using a custom loss function. Our model is
the only approach that simultaneously achieves state-of-the-art results in
medical coding accuracy, accuracy on rare codes, and sentence-level evidence
identification to support coding decisions without training on human-annotated
evidence according to experiments on the MIMIC dataset.
