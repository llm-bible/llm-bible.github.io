---
layout: publication
title: Language Portability Strategies For Open45;domain Dialogue With Pre45;trained Language Models From High To Low Resource Languages
authors: Njifenjou Ahmed, Sucal Virgile, Jabaian Bassam, Lefèvre Fabrice
conference: "Arxiv"
year: 2024
bibkey: njifenjou2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01315"}
tags: ['Applications', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
In this paper we propose a study of linguistic portability strategies of large pre45;trained language models (PLMs) used for open45;domain dialogue systems in a high45;resource language for this task. In particular the target low45;resource language (L95;T) will be simulated with French as it lacks of task45;specific resources and allows our human evaluation when the source language (L95;S) is English. For obvious reasons recent works using such models for open45;domain dialogue are mostly developed in English. Yet building specific PLMs for each possible target language supposes collecting new datasets and is costly. For this reason trying to leverage all existing resources (PLMs and data) in both L95;S and L95;T we wish to assess the performance achievable in L95;T with different approaches. The first two approaches evaluate the usage of Neural Machine Translation (NMT) at different levels TrainOnTarget where a L95;S dataset is translated before fine45;tuning in L95;T and TestOnSource where a L95;S model is coupled with NMT modules during inference. Then the advent of BLOOM 2 the world first open45;access multilingual large PLM allow researchers to develop new approaches aiming to leverage not only the models full accessibility but also its multilingualism and translation abilities. In this context the task is learned in L95;S first and adapted to L95;T using the MAD45;X Adapter architecture 16. In the two sets of experiments models are evaluated in spoken dialogue conditions with human and the strategies can be compared in terms of perceived interaction quality.
