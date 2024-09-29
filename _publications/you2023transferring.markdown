---
layout: publication
title: $P^{3}O$&#58; Transferring Visual Representations For Reinforcement Learning Via Prompting
authors: You Guoliang, Chu Xiaomeng, Duan Yifan, Peng Jie, Ji Jianmin, Zhang Yu, Zhang Yanyong
conference: "Arxiv"
year: 2023
bibkey: you2023transferring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12371"}
tags: ['Agentic', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
It is important for deep reinforcement learning (DRL) algorithms to transfer their learned policies to new environments that have different visual inputs. In this paper we introduce Prompt based Proximal Policy Optimization (P^3O) a three-stage DRL algorithm that transfers visual representations from a target to a source environment by applying prompting. The process of P^3O consists of three stages pre-training prompting and predicting. In particular we specify a prompt-transformer for representation conversion and propose a two-step training process to train the prompt-transformer for the target environment while the rest of the DRL pipeline remains unchanged. We implement P^3O and evaluate it on the OpenAI CarRacing video game. The experimental results show that P^3O outperforms the state-of-the-art visual transferring schemes. In particular P^3O allows the learned policies to perform well in environments with different visual inputs which is much more effective than retraining the policies in these environments.
