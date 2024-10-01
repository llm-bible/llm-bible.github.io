---
layout: publication
title: 'Not All Experts Are Equal: Efficient Expert Pruning And Skipping For Mixture-of-experts Large Language Models'
authors: Lu Xudong, Liu Qi, Xu Yuhui, Zhou Aojun, Huang Siyuan, Zhang Bo, Yan Junchi, Li Hongsheng
conference: "Arxiv"
year: 2024
bibkey: lu2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14800"}
  - {name: "Code", url: "https://github.com/Lucky-Lance/Expert_Sparsity"}
tags: ['Efficiency And Optimization', 'Has Code', 'Pruning', 'Training Techniques']
---
A pivotal advancement in the progress of large language models (LLMs) is the emergence of the Mixture-of-Experts (MoE) LLMs. Compared to traditional LLMs, MoE LLMs can achieve higher performance with fewer parameters, but it is still hard to deploy them due to their immense parameter sizes. Different from previous weight pruning methods that rely on specifically designed hardware, this paper mainly aims to enhance the deployment efficiency of MoE LLMs by introducing plug-and-play expert-level sparsification techniques. Specifically, we propose, for the first time to our best knowledge, post-training approaches for task-agnostic and task-specific expert pruning and skipping of MoE LLMs, tailored to improve deployment efficiency while maintaining model performance across a wide range of tasks. Extensive experiments show that our proposed methods can simultaneously reduce model sizes and increase the inference speed, while maintaining satisfactory performance. Data and code will be available at https://github.com/Lucky-Lance/Expert\_Sparsity.
