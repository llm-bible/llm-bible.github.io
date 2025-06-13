---
layout: publication
title: 'Mastering Robot Manipulation With Multimodal Prompts Through Pretraining And Multi-task Fine-tuning'
authors: Jiachen Li, Qiaozi Gao, Michael Johnston, Xiaofeng Gao, Xuehai He, Suhaila Shakiah, Hangjie Shi, Reza Ghanadan, William Yang Wang
conference: "Arxiv"
year: 2023
bibkey: li2023mastering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.09676'}
  - {name: "Code", url: 'https://midas-icml.github.io/'}
tags: ['Has Code', 'RAG', 'Tools', 'Training Techniques', 'Fine-Tuning', 'ICML', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Prompt-based learning has been demonstrated as a compelling paradigm
contributing to large language models' tremendous success (LLMs). Inspired by
their success in language tasks, existing research has leveraged LLMs in
embodied instruction following and task planning. In this work, we tackle the
problem of training a robot to understand multimodal prompts, interleaving
vision signals with text descriptions. This type of task poses a major
challenge to robots' capability to understand the interconnection and
complementarity between vision and language signals. In this work, we introduce
an effective framework that learns a policy to perform robot manipulation with
multimodal prompts from multi-task expert trajectories. Our methods consist of
a two-stage training pipeline that performs inverse dynamics pretraining and
multi-task finetuning. To facilitate multimodal understanding, we design our
multimodal prompt encoder by augmenting a pretrained LM with a residual
connection to the visual input and model the dependencies among action
dimensions. Empirically, we evaluate the efficacy of our method on the
VIMA-BENCH and establish a new state-of-the-art (10% improvement in success
rate). Moreover, we demonstrate that our model exhibits remarkable in-context
learning ability. Project page: \url\{https://midas-icml.github.io/\}.
