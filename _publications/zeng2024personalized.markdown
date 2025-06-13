---
layout: publication
title: 'Personalized LLM For Generating Customized Responses To The Same Query From Different Users'
authors: Hang Zeng, Chaoyue Niu, Fan Wu, Chengfei Lv, Guihai Chen
conference: "Arxiv"
year: 2024
bibkey: zeng2024personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11736"}
tags: ['Pretraining Methods', 'Model Architecture', 'Reinforcement Learning']
---
Existing work on large language model (LLM) personalization assigned
different responding roles to LLM, but overlooked the diversity of questioners.
In this work, we propose a new form of questioner-aware LLM personalization,
generating different responses even for the same query from different
questioners. We design a dual-tower model architecture with a cross-questioner
general encoder and a questioner-specific encoder. We further apply contrastive
learning with multi-view augmentation, pulling close the dialogue
representations of the same questioner, while pulling apart those of different
questioners. To mitigate the impact of question diversity on
questioner-contrastive learning, we cluster the dialogues based on question
similarity and restrict the scope of contrastive learning within each cluster.
We also build a multi-questioner dataset from English and Chinese scripts and
WeChat records, called MQDialog, containing 173 questioners and 12 responders.
Extensive evaluation with different metrics shows a significant improvement in
the quality of personalized response generation.
