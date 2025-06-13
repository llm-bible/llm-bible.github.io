---
layout: publication
title: 'Funreason: Enhancing Large Language Models'' Function Calling Via Self-refinement Multiscale Loss And Automated Data Refinement'
authors: Bingguang Hao, Maolin Wang, Zengzhuang Xu, Cunyin Peng, Yicheng Chen, Xiangyu Zhao, Jinjie Gu, Chenyi Zhuang
conference: "Arxiv"
year: 2025
bibkey: hao2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20192"}
  - {name: "Code", url: "https://github.com/BingguangHao/FunReason"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
The integration of large language models (LLMs) with function calling has emerged as a crucial capability for enhancing their practical utility in real-world applications. However, effectively combining reasoning processes with accurate function execution remains a significant challenge. Traditional training approaches often struggle to balance the detailed reasoning steps with the precision of function calls, leading to suboptimal performance. To address these limitations, we introduce FunReason, a novel framework that enhances LLMs' function calling capabilities through an automated data refinement strategy and a Self-Refinement Multiscale Loss (SRML) approach. FunReason leverages LLMs' natural reasoning abilities to generate high-quality training examples, focusing on query parseability, reasoning coherence, and function call precision. The SRML approach dynamically balances the contribution of reasoning processes and function call accuracy during training, addressing the inherent trade-off between these two critical aspects. FunReason achieves performance comparable to GPT-4o while effectively mitigating catastrophic forgetting during fine-tuning. FunReason provides a comprehensive solution for enhancing LLMs' function calling capabilities by introducing a balanced training methodology and a data refinement pipeline. For code and dataset, please refer to our repository at GitHub https://github.com/BingguangHao/FunReason
