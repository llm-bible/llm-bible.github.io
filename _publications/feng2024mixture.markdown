---
layout: publication
title: Mixture45;of45;loras An Efficient Multitask Tuning For Large Language Models
authors: Feng Wenfeng, Hao Chuzhan, Zhang Yuewei, Han Yu, Wang Hao
conference: "Arxiv"
year: 2024
bibkey: feng2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03432"}
tags: ['Fine Tuning', 'Model Architecture', 'Training Techniques']
---
Instruction Tuning has the potential to stimulate or enhance specific capabilities of large language models (LLMs). However achieving the right balance of data is crucial to prevent catastrophic forgetting and interference between tasks. To address these limitations and enhance training flexibility we propose the Mixture45;of45;LoRAs (MoA) architecture which is a novel and parameter45;efficient tuning method designed for multi45;task learning with LLMs. In this paper we start by individually training multiple domain45;specific LoRA modules using corresponding supervised corpus data. These LoRA modules can be aligned with the expert design principles observed in Mixture45;of45;Experts (MoE). Subsequently we combine the multiple LoRAs using an explicit routing strategy and introduce domain labels to facilitate multi45;task learning which help prevent interference between tasks and ultimately enhances the performance of each individual task. Furthermore each LoRA model can be iteratively adapted to a new domain allowing for quick domain45;specific adaptation. Experiments on diverse tasks demonstrate superior and robust performance which can further promote the wide application of domain45;specific LLMs.
