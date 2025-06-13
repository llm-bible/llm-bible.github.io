---
layout: publication
title: 'Parameter-efficient Fine-tuning Of Large Language Models For Unit Test Generation: An Empirical Study'
authors: André Storhaug, Jingyue Li
conference: "Arxiv"
year: 2024
bibkey: storhaug2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02462"}
tags: ['Fine-Tuning', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
The advent of large language models (LLMs) like GitHub Copilot has
significantly enhanced programmers' productivity, particularly in code
generation. However, these models often struggle with real-world tasks without
fine-tuning. As LLMs grow larger and more performant, fine-tuning for
specialized tasks becomes increasingly expensive. Parameter-efficient
fine-tuning (PEFT) methods, which fine-tune only a subset of model parameters,
offer a promising solution by reducing the computational costs of tuning LLMs
while maintaining their performance. Existing studies have explored using PEFT
and LLMs for various code-related tasks and found that the effectiveness of
PEFT techniques is task-dependent. The application of PEFT techniques in unit
test generation remains underexplored. The state-of-the-art is limited to using
LLMs with full fine-tuning to generate unit tests. This paper investigates both
full fine-tuning and various PEFT methods, including LoRA, (IA)^3, and prompt
tuning, across different model architectures and sizes. We use well-established
benchmark datasets to evaluate their effectiveness in unit test generation. Our
findings show that PEFT methods can deliver performance comparable to full
fine-tuning for unit test generation, making specialized fine-tuning more
accessible and cost-effective. Notably, prompt tuning is the most effective in
terms of cost and resource utilization, while LoRA approaches the effectiveness
of full fine-tuning in several cases.
