---
layout: publication
title: The First Step Is The Hardest: Pitfalls Of Representing And Tokenizing Temporal Data For Large Language Models
authors: Spathis Dimitris, Kawsar Fahim
conference: "Arxiv"
year: 2023
bibkey: spathis2023first
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06236"}
tags: ['Multimodal Models', 'Prompting', 'TACL']
---
Large Language Models (LLMs) have demonstrated remarkable generalization across diverse tasks leading individuals to increasingly use them as personal assistants and universal computing engines. Nevertheless a notable obstacle emerges when feeding numerical/temporal data into these models such as data sourced from wearables or electronic health records. LLMs employ tokenizers in their input that break down text into smaller units. However tokenizers are not designed to represent numerical values and might struggle to understand repetitive patterns and context treating consecutive values as separate tokens and disregarding their temporal relationships. Here we discuss recent works that employ LLMs for human-centric tasks such as in mobile health sensing and present a case study showing that popular LLMs tokenize temporal data incorrectly. To address that we highlight potential solutions such as prompt tuning with lightweight embedding layers as well as multimodal adapters that can help bridge this modality gap. While the capability of language models to generalize to other modalities with minimal or no finetuning is exciting this paper underscores the fact that their outputs cannot be meaningful if they stumble over input nuances.
