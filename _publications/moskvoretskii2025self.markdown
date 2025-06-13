---
layout: publication
title: 'Self-taught Self-correction For Small Language Models'
authors: Viktor Moskvoretskii, Chris Biemann, Irina Nikishina
conference: "Arxiv"
year: 2025
bibkey: moskvoretskii2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08681"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Although large language models (LLMs) have achieved remarkable performance
across various tasks, they remain prone to errors. A key challenge is enabling
them to self-correct. While prior research has relied on external tools or
large proprietary models, this work explores self-correction in small language
models (SLMs) through iterative fine-tuning using solely self-generated data.
We introduce the Self-Taught Self-Correction (STaSC) algorithm, which
incorporates multiple algorithmic design choices. Experimental results on a
question-answering task demonstrate that STaSC effectively learns
self-correction, leading to significant performance improvements. Our analysis
further provides insights into the mechanisms of self-correction and the impact
of different design choices on learning dynamics and overall performance. To
support future research, we release our user-friendly codebase and lightweight
models.
