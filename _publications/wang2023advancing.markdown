---
layout: publication
title: Openchat Advancing Open45;source Language Models With Mixed45;quality Data
authors: Wang Guan, Cheng Sijie, Zhan Xianyuan, Li Xiangang, Song Sen, Liu Yang
conference: "Arxiv"
year: 2023
bibkey: wang2023advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11235"}
  - {name: "Code", url: "https://github.com/imoneoi/openchat"}
  - {name: "Code", url: "https://huggingface.co/openchat"}
tags: ['Agentic', 'Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Nowadays open45;source large language models like LLaMA have emerged. Recent developments have incorporated supervised fine45;tuning (SFT) and reinforcement learning fine45;tuning (RLFT) to align these models with human goals. However SFT methods treat all training data with mixed quality equally while RLFT methods require high45;quality pairwise or ranking45;based preference data. In this study we present a novel framework named OpenChat to advance open45;source language models with mixed45;quality data. Specifically we consider the general SFT training data consisting of a small amount of expert data mixed with a large proportion of sub45;optimal data without any preference labels. We propose the C(onditioned)45;RLFT which regards different data sources as coarse45;grained reward labels and learns a class45;conditioned policy to leverage complementary data quality information. Interestingly the optimal policy in C45;RLFT can be easily solved through single45;stage RL45;free supervised learning which is lightweight and avoids costly human preference labeling. Through extensive experiments on three standard benchmarks our openchat45;13b fine45;tuned with C45;RLFT achieves the highest average performance among all 13b open45;source language models. Moreover we use AGIEval to validate the model generalization performance in which only openchat45;13b surpasses the base model. Finally we conduct a series of analyses to shed light on the effectiveness and robustness of OpenChat. Our code data and models are publicly available at https://github.com/imoneoi/openchat and https://huggingface.co/openchat.
