---
layout: publication
title: 'Language Portability Strategies For Open-domain Dialogue With Pre-trained Language Models From High To Low Resource Languages'
authors: Njifenjou Ahmed, Sucal Virgile, Jabaian Bassam, Lefèvre Fabrice
conference: "Arxiv"
year: 2024
bibkey: njifenjou2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01315"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
In this paper we propose a study of linguistic portability strategies of large pre-trained language models (PLMs) used for open-domain dialogue systems in a high-resource language for this task. In particular the target low-resource language (L\_T) will be simulated with French, as it lacks of task-specific resources and allows our human evaluation, when the source language (L\_S) is English. For obvious reasons, recent works using such models for open-domain dialogue are mostly developed in English. Yet building specific PLMs for each possible target language supposes collecting new datasets and is costly. For this reason, trying to leverage all existing resources (PLMs and data) in both L\_S and L\_T , we wish to assess the performance achievable in L\_T with different approaches. The first two approaches evaluate the usage of Neural Machine Translation (NMT) at different levels: TrainOnTarget where a L\_S dataset is translated before fine-tuning in L\_T and TestOnSource where a L\_S model is coupled with NMT modules during inference. Then, the advent of BLOOM [2], the world first open-access multilingual large PLM, allow researchers to develop new approaches aiming to leverage not only the model's full accessibility but also its multilingualism and translation abilities. In this context the task is learned in L\_S first and adapted to L\_T using the MAD-X Adapter architecture [16]. In the two sets of experiments models are evaluated in spoken dialogue conditions with human and the strategies can be compared in terms of perceived interaction quality.
