---
layout: publication
title: 'TAP4LLM: Table Provider On Sampling, Augmenting, And Packing Semi-structured Data For Large Language Model Reasoning'
authors: Sui Yuan, Zou Jiaru, Zhou Mengyu, He Xinyi, Du Lun, Han Shi, Zhang Dongmei
conference: "Arxiv"
year: 2023
bibkey: sui2023table
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09039"}
tags: ['Prompting', 'Uncategorized']
---
Table-based reasoning has shown remarkable progress in combining deep models
with discrete reasoning, which requires reasoning over both free-form natural
language (NL) questions and semi-structured tabular data. However, previous
table reasoning solutions only consider small-sized tables and exhibit
limitations in handling larger tables. In addition, most existing methods
struggle to reason over complex questions since they lack essential information
or they are scattered in different places. To alleviate these challenges, we
propose TAP4LLM as a versatile pre-processing toolbox to generate table prompts
through (1) table sampling, (2) table augmentation, and (3) table packing while
balancing the token allocation trade-off. In each module, we collect and design
several common methods for usage in various scenarios (e.g., speed over
accuracy). We also provide a comprehensive evaluation on performance of each
components inside TAP4LLM and show that our method improves LLMs' reasoning
capabilities in various tabular tasks and enhances the interaction between LLMs
and tabular data by employing effective pre-processing.
