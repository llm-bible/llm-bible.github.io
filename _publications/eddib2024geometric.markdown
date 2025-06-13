---
layout: publication
title: 'Gelora: Geometric Adaptive Ranks For Efficient Lora Fine-tuning'
authors: Abdessalam Ed-dib, Zhanibek Datbayev, Amine Mohamed Aboussalah
conference: "Arxiv"
year: 2024
bibkey: eddib2024geometric
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.09250'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) is computationally intensive because
it requires updating all parameters. Low-Rank Adaptation (LoRA) improves
efficiency by modifying only a subset of weights but introduces a trade-off
between expressivity and computational cost: lower ranks reduce resources but
limit expressiveness, while higher ranks enhance expressivity at increased
cost. Despite recent advances in adaptive LoRA techniques, existing methods
fail to provide a theoretical basis for optimizing the trade-off between model
performance and efficiency. We propose Geometric Low-Rank Adaptation (GeLoRA),
a novel framework that computes the intrinsic dimensionality of hidden state
representations to adaptively select LoRA ranks. We demonstrate that the
intrinsic dimension provides a lower bound for the optimal rank of LoRA
matrices, allowing for a principled selection that balances efficiency and
expressivity. GeLoRA dynamically adjusts the rank for each layer based on the
intrinsic dimensionality of its input and output representations, recognizing
that not all model parameters equally impact fine-tuning. Empirical validation
on multiple tasks shows that GeLoRA consistently outperforms recent baselines
within the same parameter budget.
