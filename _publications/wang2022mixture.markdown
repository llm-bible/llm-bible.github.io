---
layout: publication
title: Adamix Mixture45;of45;adaptations For Parameter45;efficient Model Tuning
authors: Wang Yaqing, Agarwal Sahaj, Mukherjee Subhabrata, Liu Xiaodong, Gao Jing, Awadallah Ahmed Hassan, Gao Jianfeng
conference: "Arxiv"
year: 2022
bibkey: wang2022mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17451"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Standard fine45;tuning of large pre45;trained language models (PLMs) for downstream tasks requires updating hundreds of millions to billions of parameters and storing a large copy of the PLM weights for every task resulting in increased cost for storing sharing and serving the models. To address this parameter45;efficient fine45;tuning (PEFT) techniques were introduced where small trainable components are injected in the PLM and updated during fine45;tuning. We propose AdaMix as a general PEFT method that tunes a mixture of adaptation modules 45;45; given the underlying PEFT method of choice 45;45; introduced in each Transformer layer while keeping most of the PLM weights frozen. For instance AdaMix can leverage a mixture of adapters like Houlsby or a mixture of low rank decomposition matrices like LoRA to improve downstream task performance over the corresponding PEFT methods for fully supervised and few45;shot NLU and NLG tasks. Further we design AdaMix such that it matches the same computational cost and the number of tunable parameters as the underlying PEFT method. By only tuning 0.145;0.237; of PLM parameters we show that AdaMix outperforms SOTA parameter45;efficient fine45;tuning and full model fine45;tuning for both NLU and NLG tasks.
