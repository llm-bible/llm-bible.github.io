---
layout: publication
title: 'Dissecting Language Models: Machine Unlearning Via Selective Pruning'
authors: Pochinkov Nicholas, Schoots Nandi
conference: "Arxiv"
year: 2024
bibkey: pochinkov2024dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01267"}
  - {name: "Code", url: "https://github.com/nickypro/selective-pruning"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pruning', 'Tools']
---
'Understanding and shaping the behaviour of Large Language Models (LLMs) is increasingly important as applications become more powerful and more frequently adopted. This paper introduces a machine unlearning method specifically designed for LLMs. We introduce a selective pruning method for LLMs that removes neurons based on their relative importance on a targeted capability compared to overall network performance. This approach is a compute- and data-efficient method for identifying and removing neurons that enable specific behaviours. Our findings reveal that both feed-forward and attention neurons in LLMs are specialized; that is, for specific tasks, certain neurons are more crucial than others. Code from all experiments is available at https://github.com/nickypro/selective-pruning'
