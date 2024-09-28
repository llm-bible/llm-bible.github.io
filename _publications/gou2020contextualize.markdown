---
layout: publication
title: Contextualize Knowledge Bases with Transformer for End-to-end Task-Oriented Dialogue Systems
authors: Gou Yanjie, Lei Yinjie, Liu Lingqiao, Dai Yong, Shen Chunxu
conference: "Arxiv"
year: 2020
bibkey: gou2020contextualize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.05740"}
tags: ['ARXIV', 'Model Architecture', 'Transformer']
---
Incorporating knowledge bases (KB) into end-to-end task-oriented dialogue systems is challenging since it requires to properly represent the entity of KB which is associated with its KB context and dialogue context. The existing works represent the entity with only perceiving a part of its KB context which can lead to the less effective representation due to the information loss and adversely favor KB reasoning and response generation. To tackle this issue we explore to fully contextualize the entity representation by dynamically perceiving all the relevant entities and dialogue history. To achieve this we propose a COntext-aware Memory Enhanced Transformer framework (COMET) which treats the KB as a sequence and leverages a novel Memory Mask to enforce the entity to only focus on its relevant entities and dialogue history while avoiding the distraction from the irrelevant entities. Through extensive experiments we show that our COMET framework can achieve superior performance over the state of the arts.
