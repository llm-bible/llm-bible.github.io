---
layout: publication
title: 'Algorithmic Language Models With Neurally Compiled Libraries'
authors: Lucas Saldyt, Subbarao Kambhampati
conference: "Arxiv"
year: 2024
bibkey: saldyt2024algorithmic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.04899'}
tags: ['Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Important tasks such as reasoning and planning are fundamentally algorithmic, meaning that solving them robustly requires acquiring true reasoning or planning algorithms, rather than shortcuts. Large Language Models lack true algorithmic ability primarily because of the limitations of neural network optimization algorithms, their optimization data and optimization objective, but also due to architectural inexpressivity. To solve this, our paper proposes augmenting LLMs with a library of fundamental operations and sophisticated differentiable programs, so that common algorithms do not need to be learned from scratch. We add memory, registers, basic operations, and adaptive recurrence to a transformer architecture built on LLaMA3. Then, we define a method for directly compiling algorithms into a differentiable starting library, which is used natively and propagates gradients for optimization. In this preliminary study, we explore the feasability of augmenting LLaMA3 with a differentiable computer, for instance by fine-tuning small transformers on simple algorithmic tasks with variable computational depth.
