---
layout: publication
title: "Mastering Robot Manipulation With Multimodal Prompts Through Pretraining And Multi-task Fine-tuning"
authors: Li Jiachen, Gao Qiaozi, Johnston Michael, Gao Xiaofeng, He Xuehai, Shakiah Suhaila, Shi Hangjie, Ghanadan Reza, Wang William Yang
conference: "Arxiv"
year: 2023
bibkey: li2023mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09676"}
  - {name: "Code", url: "https://midas-icml.github.io/"}
tags: ['Fine Tuning', 'Has Code', 'In Context Learning', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Prompt-based learning has been demonstrated as a compelling paradigm contributing to large language models tremendous success (LLMs). Inspired by their success in language tasks existing research has leveraged LLMs in embodied instruction following and task planning. In this work we tackle the problem of training a robot to understand multimodal prompts interleaving vision signals with text descriptions. This type of task poses a major challenge to robots capability to understand the interconnection and complementarity between vision and language signals. In this work we introduce an effective framework that learns a policy to perform robot manipulation with multimodal prompts from multi-task expert trajectories. Our methods consist of a two-stage training pipeline that performs inverse dynamics pretraining and multi-task finetuning. To facilitate multimodal understanding we design our multimodal prompt encoder by augmenting a pretrained LM with a residual connection to the visual input and model the dependencies among action dimensions. Empirically we evaluate the efficacy of our method on the VIMA-BENCH and establish a new state-of-the-art (1037; improvement in success rate). Moreover we demonstrate that our model exhibits remarkable in-context learning ability. Project page (url)https://midas-icml.github.io/\}."
