---
layout: publication
title: Mixture Of Soft Prompts For Controllable Data Generation
authors: Derek Chen, Celine Lee, Yunan Lu, Domenic Rosati, Zhou Yu
conference: "Arxiv"
year: 2023
bibkey: chen2023mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2303.01580v2"}
tags: ['Applications', 'Prompting', 'RAG']
---
Large language models (LLMs) effectively generate fluent text when the target output follows natural language patterns. However structured prediction tasks confine the output format to a limited ontology causing even very large models to struggle since they were never trained with such restrictions in mind. The difficulty of using LLMs for direct prediction is exacerbated in few45;shot learning scenarios which commonly arise due to domain shift and resource limitations. We flip the problem on its head by leveraging the LLM as a tool for data augmentation rather than direct prediction. Our proposed Mixture of Soft Prompts (MSP) serves as a parameter45;efficient procedure for generating data in a controlled manner. Denoising mechanisms are further applied to improve the quality of synthesized data. Automatic metrics show our method is capable of producing diverse and natural text while preserving label semantics. Moreover MSP achieves state45;of45;the45;art results on three benchmarks when compared against strong baselines. Our method offers an alternate data45;centric approach for applying LLMs to complex prediction tasks.
