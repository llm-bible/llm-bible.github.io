---
layout: publication
title: 'Incentivizing Llms To Self-verify Their Answers'
authors: Fuxiang Zhang, Jiacheng Xu, Chaojie Wang, Ce Cui, Yang Liu, Bo An
conference: "Arxiv"
year: 2025
bibkey: zhang2025incentivizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01369"}
  - {name: "Code", url: "https://github.com/mansicer/self-verification"}
tags: ['Pre-Training', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques', 'Has Code', 'Scaling Laws']
---
Large Language Models (LLMs) have demonstrated remarkable progress in complex reasoning tasks through both post-training and test-time scaling laws. While prevalent test-time scaling approaches are often realized by using external reward models to guide the model generation process, we find only marginal gains can be acquired when scaling a model post-trained on specific reasoning tasks. We identify that the limited improvement stems from distribution discrepancies between the specific post-trained generator and the general reward model. To address this, we propose a framework that incentivizes LLMs to self-verify their own answers. By unifying answer generation and verification within a single reinforcement learning (RL) process, we train models that can effectively assess the correctness of their own solutions. The trained model can further scale its performance during inference time by verifying its generations, without the need for external verifiers. We train our self-verification models based on Qwen2.5-Math-7B and DeepSeek-R1-Distill-Qwen-1.5B, demonstrating its capabilities across varying reasoning context lengths. Experiments on multiple mathematical reasoning benchmarks show that our models can not only improve post-training performance but also enable effective test-time scaling. Our code is available at https://github.com/mansicer/self-verification.
