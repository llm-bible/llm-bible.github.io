---
layout: publication
title: 'Loramoe: Alleviate World Knowledge Forgetting In Large Language Models Via Moe-style Plugin'
authors: Shihan Dou, Enyu Zhou, Yan Liu, Songyang Gao, Jun Zhao, Wei Shen, Yuhao Zhou, Zhiheng Xi, Xiao Wang, Xiaoran Fan, Shiliang Pu, Jiang Zhu, Rui Zheng, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2023
bibkey: dou2023alleviate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09979"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Supervised fine-tuning (SFT) is a crucial step for large language models
(LLMs), enabling them to align with human instructions and enhance their
capabilities in downstream tasks. Increasing instruction data substantially is
a direct solution to align the model with a broader range of downstream tasks
or notably improve its performance on a specific task. However, we find that
large-scale increases in instruction data can damage the world knowledge
previously stored in LLMs. To address this challenge, we propose LoRAMoE, a
novelty framework that introduces several low-rank adapters (LoRA) and
integrates them by using a router network, like a plugin version of Mixture of
Experts (MoE). It freezes the backbone model and forces a portion of LoRAs to
focus on leveraging world knowledge to solve downstream tasks, to alleviate
world knowledge-edge forgetting. Experimental results show that, as the
instruction data increases, LoRAMoE can significantly improve the ability to
process downstream tasks, while maintaining the world knowledge stored in the
LLM.
