---
layout: publication
title: 'Supervisory Prompt Training'
authors: Jean Ghislain Billa, Min Oh, Liang Du
conference: "Arxiv"
year: 2024
bibkey: billa2024supervisory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18051"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
The performance of Large Language Models (LLMs) relies heavily on the quality
of prompts, which are often manually engineered and task-specific, making them
costly and non-scalable. We propose a novel approach, Supervisory Prompt
Training (SPT). SPT automates the generation of highly effective prompts using
a dual LLM system. In this system, one LLM, the generator, performs a task
while the other, the corrector, provides feedback and generates improved
prompts. In contrast to earlier techniques, both the generator and corrector
collaboratively and continuously improve their prompts over time. We also
introduce the concept of \textit\{impact scores\} to measure the sentence-level
effectiveness of the prompts. Our method was tested on four benchmarks, testing
the level of hallucinations in LLMs. Notably, we were able to increase the
accuracy of GPT-4 on GSM8K from 65.8% to 94.1% (28.3% increase). SPT
advances LLMs by refining prompts to enhance performance and reduce
hallucinations, offering an efficient and scalable alternative to traditional
model fine-tuning.
