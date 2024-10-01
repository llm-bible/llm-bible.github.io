---
layout: publication
title: 'Commit: Coordinated Instruction Tuning For Multimodal Large Language Models'
authors: Wu Junda, Li Xintong, Yu Tong, Wang Yu, Chen Xiang, Gu Jiuxiang, Yao Lina, Shang Jingbo, Mcauley Julian
conference: "Arxiv"
year: 2024
bibkey: wu2024coordinated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20454"}
tags: ['Efficiency And Optimization', 'Multimodal Models']
---
Instruction tuning in multimodal large language models (MLLMs) aims to smoothly integrate a backbone LLM with a pre-trained feature encoder for downstream tasks. The major challenge is how to efficiently find the synergy through cooperative learning where LLMs adapt their reasoning abilities in downstream tasks while feature encoders adjust their encoding to provide more relevant modal information. In this paper, we analyze the MLLM instruction tuning from both theoretical and empirical perspectives, where we find unbalanced learning between the two components, i.e., the feature encoder and the LLM, can cause diminishing learning gradients that slow the model convergence and often lead to sub-optimal results due to insufficient learning. Inspired by our findings, we propose a measurement to quantitatively evaluate the learning balance, based on which we further design a dynamic learning scheduler that better coordinates the learning. In addition, we introduce an auxiliary loss regularization method to promote updating of the generation distribution of MLLMs considering the learning state of each model component, which potentially prevents each component from gradient diminishing and enables a more accurate estimation of the learning balance coefficient. We conduct experiments with multiple LLM backbones and feature encoders, where our techniques are model-agnostic and can be generically integrated with various MLLM backbones. Experiment results on multiple downstream tasks and modalities in vision and audio, demonstrate the proposed method's better efficiency and effectiveness in MLLM instruction tuning.
