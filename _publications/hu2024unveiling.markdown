---
layout: publication
title: Minicpm\: Unveiling The Potential Of Small Language Models With Scalable Training Strategies
authors: Hu Shengding, Tu Yuge, Han Xu, He Chaoqun, Cui Ganqu, Long Xiang, Zheng Zhi, Fang Yewei, Huang Yuxiang, Zhao Weilin, Zhang Xinrong, Thai Zheng Leng, Zhang Kaihuo, Wang Chongyi, Yao Yuan, Zhao Chenyang, Zhou Jie, Cai Jie, Zhai Zhongwu, Ding Ning, Jia Chao, Zeng Guoyang, Li Dahai, Liu Zhiyuan, Sun Maosong
conference: "Arxiv"
year: 2024
bibkey: hu2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06395"}
  - {name: "Code", url: "https://github.com/OpenBMB/MiniCPM"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques']
---
The burgeoning interest in developing Large Language Models (LLMs) with up to trillion parameters has been met with concerns regarding resource efficiency and practical expense particularly given the immense cost of experimentation. This scenario underscores the importance of exploring the potential of Small Language Models (SLMs) as a resource-efficient alternative. In this context we introduce MiniCPM specifically the 1.2B and 2.4B non-embedding parameter variants not only excel in their respective categories but also demonstrate capabilities on par with 7B-13B LLMs. While focusing on SLMs our approach exhibits scalability in both model and data dimensions for future LLM research. Regarding model scaling we employ extensive model wind tunnel experiments for stable and optimal scaling. For data scaling we introduce a Warmup-Stable-Decay (WSD) learning rate scheduler (LRS) conducive to continuous training and domain adaptation. We present an in-depth analysis of the intriguing training dynamics that occurred in the WSD LRS. With WSD LRS we are now able to efficiently study data-model scaling law without extensive retraining experiments on both axes of model and data from which we derive the much higher compute optimal data-model ratio than Chinchilla Optimal. Additionally we introduce MiniCPM family including MiniCPM-DPO MiniCPM-MoE and MiniCPM-128K whose excellent performance further cementing MiniCPMs foundation in diverse SLM applications. MiniCPM models are available publicly at https://github.com/OpenBMB/MiniCPM .
