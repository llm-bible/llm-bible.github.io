---
layout: publication
title: Chain-of-Thought Tuning Masked Language Models can also Think Step By Step in Natural Language Understanding
authors: Fan Caoyun, Tian Jidong, Li Yitian, Chen Wenqing, He Hao, Jin Yaohui
conference: "Arxiv"
year: 2023
bibkey: fan2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11721"}
tags: ['Applications', 'BERT', 'Masked Language Model', 'Pretraining Methods', 'Prompting', 'Tools']
---
Chain-of-Thought (CoT) is a technique that guides Large Language Models (LLMs) to decompose complex tasks into multi-step reasoning through intermediate steps in natural language form. Briefly CoT enables LLMs to think step by step. However although many Natural Language Understanding (NLU) tasks also require thinking step by step LLMs perform less well than small-scale Masked Language Models (MLMs). To migrate CoT from LLMs to MLMs we propose Chain-of-Thought Tuning (CoTT) a two-step reasoning framework based on prompt tuning to implement step-by-step thinking for MLMs on NLU tasks. From the perspective of CoT CoTTs two-step framework enables MLMs to implement task decomposition; CoTTs prompt tuning allows intermediate steps to be used in natural language form. Thereby the success of CoT can be extended to NLU tasks through MLMs. To verify the effectiveness of CoTT we conduct experiments on two NLU tasks hierarchical classification and relation extraction and the results show that CoTT outperforms baselines and achieves state-of-the-art performance.
