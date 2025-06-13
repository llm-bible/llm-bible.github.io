---
layout: publication
title: 'On The Effectiveness Of Incremental Training Of Large Language Models'
authors: Miles Q. Li, Benjamin C. M. Fung, Shih-chia Huang
conference: "Arxiv"
year: 2024
bibkey: li2024effectiveness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18700"}
tags: ['Training Techniques', 'Efficiency and Optimization']
---
Training large language models is a computationally intensive process that
often requires substantial resources to achieve state-of-the-art results.
Incremental layer-wise training has been proposed as a potential strategy to
optimize the training process by progressively introducing layers, with the
expectation that this approach would lead to faster convergence and more
efficient use of computational resources. In this paper, we investigate the
effectiveness of incremental training for LLMs, dividing the training process
into multiple stages where layers are added progressively. Our experimental
results indicate that while the incremental approach initially demonstrates
some computational efficiency, it ultimately requires greater overall
computational costs to reach comparable performance to traditional full-scale
training. Although the incremental training process can eventually close the
performance gap with the baseline, it does so only after significantly extended
continual training. These findings suggest that incremental layer-wise training
may not be a viable alternative for training large language models,
highlighting its limitations and providing valuable insights into the
inefficiencies of this approach.
