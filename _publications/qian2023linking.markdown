---
layout: publication
title: Toolink: Linking Toolkit Creation And Using Through Chain-of-solving On Open-source Model
authors: Qian Cheng, Xiong Chenyan, Liu Zhenghao, Liu Zhiyuan
conference: "Arxiv"
year: 2023
bibkey: qian2023linking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05155"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Security', 'Tools']
---
Large Language Models (LLMs) have demonstrated remarkable progress in utilizing tools but their closed-source nature and high inference costs pose limitations on their adaptability necessitating a valid method that leverages smaller open-sourced models. In this paper we introduce Toolink a comprehensive framework that performs task-solving by first creating a toolkit and then integrating the planning and calling of tools through a chain-of-solving (CoS) approach. We first validate the efficacy of Toolink in harnessing the models creativity and CoS ability on ChatGPT. Subsequently we curate CoS-GPT a chain-of-solving dataset designed for tool-using and finetune the LLaMA-7B model. It results in LLaMA-CoS a powerful open-source model with advanced tool-planning and tool-calling capabilities. Evaluation of diverse tasks from BIG-bench demonstrates its CoS ability matches that of ChatGPT while its performance surpasses the chain-of-thought approach. Further studies highlight the generalization of LLaMA-CoS to unseen tasks and showcase its capability in using toolkits not explicitly tailored for the target task affirming its robustness in real-world scenarios.
