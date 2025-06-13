---
layout: publication
title: 'Life After BERT: What Do Other Muppets Understand About Language?'
authors: Vladislav Lialin, Kevin Zhao, Namrata Shivagunde, Anna Rumshisky
conference: "Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics Volume 1 Long Papers pages 3180-3193 2022"
year: 2022
bibkey: lialin2022life
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.10696'}
tags: ['Language Modeling', 'Transformer', 'Training Techniques', 'BERT', 'Model Architecture', 'GPT', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Existing pre-trained transformer analysis works usually focus only on one or
two model families at a time, overlooking the variability of the architecture
and pre-training objectives. In our work, we utilize the oLMpics benchmark and
psycholinguistic probing datasets for a diverse set of 29 models including T5,
BART, and ALBERT. Additionally, we adapt the oLMpics zero-shot setup for
autoregressive models and evaluate GPT networks of different sizes. Our
findings show that none of these models can resolve compositional questions in
a zero-shot fashion, suggesting that this skill is not learnable using existing
pre-training objectives. Furthermore, we find that global model decisions such
as architecture, directionality, size of the dataset, and pre-training
objective are not predictive of a model's linguistic capabilities.
