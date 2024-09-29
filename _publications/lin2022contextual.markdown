---
layout: publication
title: Contextual Transformer For Offline Meta Reinforcement Learning
authors: Lin Runji, Li Ye, Feng Xidong, Zhang Zhaowei, Fung Xian Hong Wu, Zhang Haifeng, Wang Jun, Du Yali, Yang Yaodong
conference: "Arxiv"
year: 2022
bibkey: lin2022contextual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.08016"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
The pretrain45;finetuning paradigm in large45;scale sequence models has made significant progress in natural language processing and computer vision tasks. However such a paradigm is still hindered by several challenges in Reinforcement Learning (RL) including the lack of self45;supervised pretraining algorithms based on offline data and efficient fine45;tuning/prompt45;tuning over unseen downstream tasks. In this work we explore how prompts can improve sequence modeling45;based offline reinforcement learning (offline45;RL) algorithms. Firstly we propose prompt tuning for offline RL where a context vector sequence is concatenated with the input to guide the conditional policy generation. As such we can pretrain a model on the offline dataset with self45;supervised loss and learn a prompt to guide the policy towards desired actions. Secondly we extend our framework to Meta45;RL settings and propose Contextual Meta Transformer (CMT); CMT leverages the context among different tasks as the prompt to improve generalization on unseen tasks. We conduct extensive experiments across three different offline45;RL settings offline single45;agent RL on the D4RL dataset offline Meta45;RL on the MuJoCo benchmark and offline MARL on the SMAC benchmark. Superior results validate the strong performance and generality of our methods.
