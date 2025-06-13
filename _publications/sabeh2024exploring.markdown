---
layout: publication
title: 'Exploring Large Language Models For Product Attribute Value Identification'
authors: Kassem Sabeh, Mouna Kacimi, Johann Gamper, Robert Litschko, Barbara Plank
conference: "Arxiv"
year: 2024
bibkey: sabeh2024exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.12695'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Product attribute value identification (PAVI) involves automatically
identifying attributes and their values from product information, enabling
features like product search, recommendation, and comparison. Existing methods
primarily rely on fine-tuning pre-trained language models, such as BART and T5,
which require extensive task-specific training data and struggle to generalize
to new attributes. This paper explores large language models (LLMs), such as
LLaMA and Mistral, as data-efficient and robust alternatives for PAVI. We
propose various strategies: comparing one-step and two-step prompt-based
approaches in zero-shot settings and utilizing parametric and non-parametric
knowledge through in-context learning examples. We also introduce a dense
demonstration retriever based on a pre-trained T5 model and perform instruction
fine-tuning to explicitly train LLMs on task-specific instructions. Extensive
experiments on two product benchmarks show that our two-step approach
significantly improves performance in zero-shot settings, and instruction
fine-tuning further boosts performance when using training data, demonstrating
the practical benefits of using LLMs for PAVI.
