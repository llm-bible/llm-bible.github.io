---
layout: publication
title: 'A MIND For Reasoning: Meta-learning For In-context Deduction'
authors: Leonardo Bertolazzi, Manuel Vargas Guzmán, Raffaella Bernardi, Maciej Malicki, Jakub Szymanik
conference: "Arxiv"
year: 2025
bibkey: bertolazzi2025mind
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14313"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) are increasingly evaluated on formal tasks, where strong reasoning abilities define the state of the art. However, their ability to generalize to out-of-distribution problems remains limited. In this paper, we investigate how LLMs can achieve a systematic understanding of deductive rules. Our focus is on the task of identifying the appropriate subset of premises within a knowledge base needed to derive a given hypothesis. To tackle this challenge, we propose Meta-learning for In-context Deduction (MIND), a novel few-shot meta-learning fine-tuning approach. The goal of MIND is to enable models to generalize more effectively to unseen knowledge bases and to systematically apply inference rules. Our results show that MIND significantly improves generalization in small LMs ranging from 1.5B to 7B parameters. The benefits are especially pronounced in smaller models and low-data settings. Remarkably, small models fine-tuned with MIND outperform state-of-the-art LLMs, such as GPT-4o and o3-mini, on this task.
