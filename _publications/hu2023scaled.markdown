---
layout: publication
title: 'Scaled Prompt-tuning For Few-shot Natural Language Generation'
authors: Hu Ting, Meinel Christoph, Yang Haojin
conference: "Arxiv"
year: 2023
bibkey: hu2023scaled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06759"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
The increasingly Large Language Models (LLMs) demonstrate stronger language understanding and generation capabilities while the memory demand and computation cost of fine-tuning LLMs on downstream tasks are non-negligible. Besides fine-tuning generally requires a certain amount of data from individual tasks whilst data collection cost is another issue to consider in real-world applications. In this work we focus on Parameter-Efficient Fine-Tuning (PEFT) methods for few-shot Natural Language Generation (NLG) which freeze most parameters in LLMs and tune a small subset of parameters in few-shot cases so that memory footprint training cost and labeling cost are reduced while maintaining or even improving the performance. We propose a Scaled Prompt-Tuning (SPT) method which surpasses conventional PT with better performance and generalization ability but without an obvious increase in training cost. Further study on intermediate SPT suggests the superior transferability of SPT in few-shot scenarios providing a recipe for data-deficient and computation-limited circumstances. Moreover a comprehensive comparison of existing PEFT methods reveals that certain approaches exhibiting decent performance with modest training cost such as Prefix-Tuning in prior study could struggle in few-shot NLG tasks especially on challenging datasets.
