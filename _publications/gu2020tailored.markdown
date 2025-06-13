---
layout: publication
title: 'A Tailored Pre-training Model For Task-oriented Dialog Generation'
authors: Jing Gu, Qingyang Wu, Chongruo Wu, Weiyan Shi, Zhou Yu
conference: "Arxiv"
year: 2020
bibkey: gu2020tailored
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.13835"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Distillation', 'GPT', 'Pretraining Methods', 'BERT', 'Pre-Training']
---
The recent success of large pre-trained language models such as BERT and
GPT-2 has suggested the effectiveness of incorporating language priors in
downstream dialog generation tasks. However, the performance of pre-trained
models on the dialog task is not as optimal as expected. In this paper, we
propose a Pre-trained Role Alternating Language model (PRAL), designed
specifically for task-oriented conversational systems. We adopted (Wu et al.,
2019) that models two speakers separately. We also design several techniques,
such as start position randomization, knowledge distillation, and history
discount to improve pre-training performance. We introduce a task-oriented
dialog pretraining dataset by cleaning 13 existing data sets. We test PRAL on
three different downstream tasks. The results show that PRAL performs better or
on par with state-of-the-art methods.
