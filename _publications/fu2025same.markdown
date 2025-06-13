---
layout: publication
title: 'Same Question, Different Words: A Latent Adversarial Framework For Prompt Robustness'
authors: Tingchen Fu, Fazl Barez
conference: "Arxiv"
year: 2025
bibkey: fu2025same
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01345"}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Insensitivity to semantically-preserving variations of prompts (paraphrases)
is crucial for reliable behavior and real-world deployment of large language
models. However, language models exhibit significant performance degradation
when faced with semantically equivalent but differently phrased prompts, and
existing solutions either depend on trial-and-error prompt engineering or
require computationally expensive inference-time algorithms. In this study,
built on the key insight that worst-case prompts exhibit a drift in embedding
space, we present Latent Adversarial Paraphrasing (LAP), a dual-loop
adversarial framework: the inner loop trains a learnable perturbation to serve
as a "latent continuous paraphrase" while preserving semantics through
Lagrangian regulation, and the outer loop optimizes the language model
parameters on these perturbations. We conduct extensive experiments to
demonstrate the effectiveness of LAP across multiple LLM architectures on the
RobustAlpaca benchmark with a 0.5%-4% absolution improvement on worst-case
win-rate compared with vanilla supervised fine-tuning.
