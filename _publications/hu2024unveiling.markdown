---
layout: publication
title: 'Minicpm: Unveiling The Potential Of Small Language Models With Scalable Training Strategies'
authors: Shengding Hu, Yuge Tu, Xu Han, Chaoqun He, Ganqu Cui, Xiang Long, Zhi Zheng, Yewei Fang, Yuxiang Huang, Weilin Zhao, Xinrong Zhang, Zheng Leng Thai, Kaihuo Zhang, Chongyi Wang, Yuan Yao, Chenyang Zhao, Jie Zhou, Jie Cai, Zhongwu Zhai, Ning Ding, Chao Jia, Guoyang Zeng, Dahai Li, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: hu2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06395"}
  - {name: "Code", url: "https://github.com/OpenBMB/MiniCPM"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Scaling Laws']
---
The burgeoning interest in developing Large Language Models (LLMs) with up to
trillion parameters has been met with concerns regarding resource efficiency
and practical expense, particularly given the immense cost of experimentation.
This scenario underscores the importance of exploring the potential of Small
Language Models (SLMs) as a resource-efficient alternative. In this context, we
introduce MiniCPM, specifically the 1.2B and 2.4B non-embedding parameter
variants, not only excel in their respective categories but also demonstrate
capabilities on par with 7B-13B LLMs. While focusing on SLMs, our approach
exhibits scalability in both model and data dimensions for future LLM research.
Regarding model scaling, we employ extensive model wind tunnel experiments for
stable and optimal scaling. For data scaling, we introduce a
Warmup-Stable-Decay (WSD) learning rate scheduler (LRS), conducive to
continuous training and domain adaptation. We present an in-depth analysis of
the intriguing training dynamics that occurred in the WSD LRS. With WSD LRS, we
are now able to efficiently study data-model scaling law without extensive
retraining experiments on both axes of model and data, from which we derive the
much higher compute optimal data-model ratio than Chinchilla Optimal.
Additionally, we introduce MiniCPM family, including MiniCPM-DPO, MiniCPM-MoE
and MiniCPM-128K, whose excellent performance further cementing MiniCPM's
foundation in diverse SLM applications. MiniCPM models are available publicly
at https://github.com/OpenBMB/MiniCPM .
