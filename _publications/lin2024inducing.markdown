---
layout: publication
title: 'Inducing Generalization Across Languages And Tasks Using Featurized Low-rank Mixtures'
authors: Lin Chu-cheng, Wang Xinyi, Clark Jonathan H., Lu Han, Zhu Yun, Whitehouse Chenxi, Yu Hongkun
conference: "Arxiv"
year: 2024
bibkey: lin2024inducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17934"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Adapting pretrained large language models (LLMs) to various downstream tasks in tens or hundreds of human languages is computationally expensive. Parameter-efficient fine-tuning (PEFT) significantly reduces the adaptation cost by tuning only a small amount of parameters. However common PEFT methods LoRA (Hu et al. 2022) suffer from suboptimal performance on diverse dataset mixtures due to aggressive parameter tying and negative interference among different datasets. In this work we propose Featurized Low-rank Mixtures (FLix) a novel PEFT method designed for effective multitask multilingual adaptation. FLix associates each unique dataset feature such as the datasets language or task with its own low-rank weight update parameters. By composing feature-specific parameters for each dataset FLix can accommodate diverse dataset mixtures and generalize better to unseen datasets. Our experiments show that FLix leads to significant improvements over a variety of tasks for both supervised learning and zero-shot settings with gains of up to (14.2) inexact match points in zero-shot semantic parsing.
