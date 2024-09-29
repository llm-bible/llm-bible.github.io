---
layout: publication
title: Scaled Prompt45;tuning For Few45;shot Natural Language Generation
authors: Hu Ting, Meinel Christoph, Yang Haojin
conference: "Arxiv"
year: 2023
bibkey: hu2023scaled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06759"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
The increasingly Large Language Models (LLMs) demonstrate stronger language understanding and generation capabilities while the memory demand and computation cost of fine45;tuning LLMs on downstream tasks are non45;negligible. Besides fine45;tuning generally requires a certain amount of data from individual tasks whilst data collection cost is another issue to consider in real45;world applications. In this work we focus on Parameter45;Efficient Fine45;Tuning (PEFT) methods for few45;shot Natural Language Generation (NLG) which freeze most parameters in LLMs and tune a small subset of parameters in few45;shot cases so that memory footprint training cost and labeling cost are reduced while maintaining or even improving the performance. We propose a Scaled Prompt45;Tuning (SPT) method which surpasses conventional PT with better performance and generalization ability but without an obvious increase in training cost. Further study on intermediate SPT suggests the superior transferability of SPT in few45;shot scenarios providing a recipe for data45;deficient and computation45;limited circumstances. Moreover a comprehensive comparison of existing PEFT methods reveals that certain approaches exhibiting decent performance with modest training cost such as Prefix45;Tuning in prior study could struggle in few45;shot NLG tasks especially on challenging datasets.
