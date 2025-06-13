---
layout: publication
title: 'Learning And Leveraging Verifiers To Improve Planning Capabilities Of Pre-trained Language Models'
authors: Daman Arora, Subbarao Kambhampati
conference: "Arxiv"
year: 2023
bibkey: arora2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17077"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning']
---
There have been wide spread claims in the literature about the emergent
reasoning capabilities of Pretrained Large Language Models. However, recent
studies, have found that their ability to plan remains questionable. Through
our experiments using GPT-2, we empirically demonstrate that the performance of
a finetuned baseline remains poor because it violates pre-conditions of actions
in the plans that it generates. To improve the planning capabilities of a
finetuned LLM, we train a verifier, which can classify actions as being valid
or invalid in a particular state. By randomly sampling actions from the same
dataset, we generate examples of invalid actions which are then used to train a
verifier which can check for action applicability. In the presence of diverse
sampling from a generator and a verifier which can prune invalid trajectories,
we show significant gains in the success rate on the Blocksworld domain.
Additionally, we show that finetuning the GPT-2 generator itself to create the
verifier generalizes better than finetuning the base GPT-2. Lastly, we
investigate the role of the sampling temperature which can be used to control
the exploration-exploitation tradeoff.
