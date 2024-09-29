---
layout: publication
title: Learning And Leveraging Verifiers To Improve Planning Capabilities Of Pre45;trained Language Models
authors: Arora Daman, Kambhampati Subbarao
conference: "Arxiv"
year: 2023
bibkey: arora2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17077"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning']
---
There have been wide spread claims in the literature about the emergent reasoning capabilities of Pretrained Large Language Models. However recent studies have found that their ability to plan remains questionable. Through our experiments using GPT45;2 we empirically demonstrate that the performance of a finetuned baseline remains poor because it violates pre45;conditions of actions in the plans that it generates. To improve the planning capabilities of a finetuned LLM we train a verifier which can classify actions as being valid or invalid in a particular state. By randomly sampling actions from the same dataset we generate examples of invalid actions which are then used to train a verifier which can check for action applicability. In the presence of diverse sampling from a generator and a verifier which can prune invalid trajectories we show significant gains in the success rate on the Blocksworld domain. Additionally we show that finetuning the GPT45;2 generator itself to create the verifier generalizes better than finetuning the base GPT45;2. Lastly we investigate the role of the sampling temperature which can be used to control the exploration45;exploitation tradeoff.
