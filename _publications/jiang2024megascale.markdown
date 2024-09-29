---
layout: publication
title: Megascale Scaling Large Language Model Training To More Than 10000 Gpus
authors: Jiang Ziheng, Lin Haibin, Zhong Yinmin, Huang Qi, Chen Yangrui, Zhang Zhi, Peng Yanghua, Li Xiang, Xie Cong, Nong Shibiao, Jia Yulu, He Sun, Chen Hongmin, Bai Zhihao, Hou Qi, Yan Shipeng, Zhou Ding, Sheng Yiyao, Jiang Zhuo, Xu Haohan, Wei Haoran, Zhang Zhang, Nie Pengfei, Zou Leqi, Zhao Sida, Xiang Liang, Liu Zherui, Li Zhe, Jia Xiaoying, Ye Jianxi, Jin Xin, Liu Xin
conference: "Arxiv"
year: 2024
bibkey: jiang2024megascale
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15627"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We present the design implementation and engineering experience in building and deploying MegaScale a production system for training large language models (LLMs) at the scale of more than 10000 GPUs. Training LLMs at this scale brings unprecedented challenges to training efficiency and stability. We take a full-stack approach that co-designs the algorithmic and system components across model block and optimizer design computation and communication overlapping operator optimization data pipeline and network performance tuning. Maintaining high efficiency throughout the training process (i.e. stability) is an important consideration in production given the long extent of LLM training jobs. Many hard stability issues only emerge at large scale and in-depth observability is the key to address them. We develop a set of diagnosis tools to monitor system components and events deep in the stack identify root causes and derive effective techniques to achieve fault tolerance and mitigate stragglers. MegaScale achieves 55.237; Model FLOPs Utilization (MFU) when training a 175B LLM model on 12288 GPUs improving the MFU by 1.34x compared to Megatron-LM. We share our operational experience in identifying and fixing failures and stragglers. We hope by articulating the problems and sharing our experience from a systems perspective this work can inspire future LLM systems research.
