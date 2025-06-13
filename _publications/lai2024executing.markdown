---
layout: publication
title: 'Executing Arithmetic: Fine-tuning Large Language Models As Turing Machines'
authors: Junyu Lai, Jiahe Xu, Yao Yang, Yunpeng Huang, Chun Cao, Jingwei Xu
conference: "Arxiv"
year: 2024
bibkey: lai2024executing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.07896'}
tags: ['GPT', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities across
a wide range of natural language processing and reasoning tasks. However, their
performance in the foundational domain of arithmetic remains unsatisfactory.
When dealing with arithmetic tasks, LLMs often memorize specific examples
rather than learning the underlying computational logic, limiting their ability
to generalize to new problems. In this paper, we propose a Composable
Arithmetic Execution Framework (CAEF) that enables LLMs to learn to execute
step-by-step computations by emulating Turing Machines, thereby gaining a
genuine understanding of computational logic. Moreover, the proposed framework
is highly scalable, allowing composing learned operators to significantly
reduce the difficulty of learning complex operators. In our evaluation, CAEF
achieves nearly 100% accuracy across seven common mathematical operations on
the LLaMA 3.1-8B model, effectively supporting computations involving operands
with up to 100 digits, a level where GPT-4o falls short noticeably in some
settings.
