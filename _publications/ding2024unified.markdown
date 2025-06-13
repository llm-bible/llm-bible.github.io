---
layout: publication
title: 'Unified Parameter-efficient Unlearning For Llms'
authors: Chenlu Ding, Jiancan Wu, Yancheng Yuan, Jinda Lu, Kai Zhang, Alex Su, Xiang Wang, Xiangnan He
conference: "Arxiv"
year: 2024
bibkey: ding2024unified
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.00383'}
tags: ['Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The advent of Large Language Models (LLMs) has revolutionized natural
language processing, enabling advanced understanding and reasoning capabilities
across a variety of tasks. Fine-tuning these models for specific domains,
particularly through Parameter-Efficient Fine-Tuning (PEFT) strategies like
LoRA, has become a prevalent practice due to its efficiency. However, this
raises significant privacy and security concerns, as models may inadvertently
retain and disseminate sensitive or undesirable information. To address these
issues, we introduce a novel instance-wise unlearning framework, LLMEraser,
which systematically categorizes unlearning tasks and applies precise parameter
adjustments using influence functions. Unlike traditional unlearning techniques
that are often limited in scope and require extensive retraining, LLMEraser is
designed to handle a broad spectrum of unlearning tasks without compromising
model performance. Extensive experiments on benchmark datasets demonstrate that
LLMEraser excels in efficiently managing various unlearning scenarios while
maintaining the overall integrity and efficacy of the models.
