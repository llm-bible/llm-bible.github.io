---
layout: publication
title: 'Coffee-gym: An Environment For Evaluating And Improving Natural Language Feedback On Erroneous Code'
authors: Hyungjoo Chae, Taeyoon Kwon, Seungjun Moon, Yongho Song, Dongjin Kang, Kai Tzu-iunn Ong, Beong-woo Kwak, Seonghyeon Bae, Seung-won Hwang, Jinyoung Yeo
conference: "Arxiv"
year: 2024
bibkey: chae2024coffee
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19715"}
tags: ['Training Techniques', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
This paper presents Coffee-Gym, a comprehensive RL environment for training
models that provide feedback on code editing. Coffee-Gym includes two major
components: (1) Coffee, a dataset containing humans' code edit traces for
coding questions and machine-written feedback for editing erroneous code; (2)
CoffeeEval, a reward function that faithfully reflects the helpfulness of
feedback by assessing the performance of the revised code in unit tests. With
them, Coffee-Gym addresses the unavailability of high-quality datasets for
training feedback models with RL, and provides more accurate rewards than the
SOTA reward model (i.e., GPT-4). By applying Coffee-Gym, we elicit feedback
models that outperform baselines in enhancing open-source code LLMs' code
editing, making them comparable with closed-source LLMs. We make the dataset
and the model checkpoint publicly available.
