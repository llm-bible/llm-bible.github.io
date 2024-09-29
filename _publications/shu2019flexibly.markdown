---
layout: publication
title: "Flexibly-structured Model For Task-oriented Dialogues"
authors: Shu Lei, Molino Piero, Namazifar Mahdi, Xu Hu, Liu Bing, Zheng Huaixiu, Tur Gokhan
conference: "Arxiv"
year: 2019
bibkey: shu2019flexibly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.02402"}
  - {name: "Code", url: "https://github.com/uber-research/FSDM"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
This paper proposes a novel end-to-end architecture for task-oriented dialogue systems. It is based on a simple and practical yet very effective sequence-to-sequence approach where language understanding and state tracking tasks are modeled jointly with a structured copy-augmented sequential decoder and a multi-label decoder for each slot. The policy engine and language generation tasks are modeled jointly following that. The copy-augmented sequential decoder deals with new or unknown values in the conversation while the multi-label decoder combined with the sequential decoder ensures the explicit assignment of values to slots. On the generation part slot binary classifiers are used to improve performance. This architecture is scalable to real-world scenarios and is shown through an empirical evaluation to achieve state-of-the-art performance on both the Cambridge Restaurant dataset and the Stanford in-car assistant dataset(footnote)The code is available at (url)https://github.com/uber-research/FSDM\}\}"
