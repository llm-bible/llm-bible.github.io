---
layout: publication
title: Lawyer Llama Technical Report
authors: Huang Quzhe, Tao Mingxu, Zhang Chen, An Zhenwei, Jiang Cong, Chen Zhibin, Wu Zirui, Feng Yansong
conference: "Arxiv"
year: 2023
bibkey: huang2023lawyer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15062"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) like LLaMA have exhibited remarkable performance across various tasks. Nevertheless when deployed to specific domains such as law or medicine the models still confront the challenge of a deficiency in domain-specific knowledge and an inadequate capability to leverage that knowledge to resolve domain-related problems. In this paper we propose a new framework to adapt LLMs to specific domains and build Lawyer LLaMA a legal domain LLM based on this framework. Specifically we inject domain knowledge during the continual training stage and teach the model to learn professional skills using properly designed supervised fine-tuning tasks. Moreover to alleviate the hallucination problem during the models generation we add a retrieval module and extract relevant legal articles before the model answers any queries. When learning domain-specific skills we find that experts experience is much more useful than experiences distilled from ChatGPT where hundreds of expert-written data outperform tens of thousands of ChatGPT-generated ones. We will release our model and data.
