---
layout: publication
title: Building Markovian Generative Architectures Over Pretrained LM Backbones For Efficient Task-oriented Dialog Systems
authors: Liu Hong, Cai Yucheng, Ou Zhijian, Huang Yi, Feng Junlan
conference: "Arxiv"
year: 2022
bibkey: liu2022building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.06452"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Recently Transformer based pretrained language models (PLMs) such as GPT2 and T5 have been leveraged to build generative task-oriented dialog (TOD) systems. A drawback of existing PLM-based models is their non-Markov architectures across turns i.e. the whole history is used as the conditioning input at each turn. First this brings inefficiencies in memory and computation. Furthermore using the whole history increases model complexity and may hurt the training efficiency especially when facing small amounts of labeled training data (the low-resource setting). In this paper motivated by the observation that dialog states could be viewed as Markov states we propose to build Markovian Generative Architectures (MGA) over PLM backbones for efficient TOD systems. Experiments on MultiWOZ2.1 show that in the rich-resource setting the proposed Markov models reduce memory and time costs without performance degradation; in the low-resource setting the training efficiency of the Markov models is more significant.
