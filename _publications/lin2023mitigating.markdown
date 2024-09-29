---
layout: publication
title: 'Mitigating The Alignment Tax Of RLHF'
authors: Lin Yong, Lin Hangyu, Xiong Wei, Diao Shizhe, Liu Jianmeng, Zhang Jipeng, Pan Rui, Wang Haoxiang, Hu Wenbin, Zhang Hanning, Dong Hanze, Pi Renjie, Zhao Han, Jiang Nan, Ji Heng, Yao Yuan, Zhang Tong
conference: "Arxiv"
year: 2023
bibkey: lin2023mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.06256"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
LLMs acquire a wide range of abilities during pre-training but aligning LLMs under Reinforcement Learning with Human Feedback (RLHF) can lead to forgetting which is also known as the alignment tax. To empirically verify this hypothesis we conducted experiments with existing RLHF algorithms using OpenLLaMA-3B which revealed a pronounced alignment tax in NLP tasks. On the other hand despite various techniques to mitigate forgetting they are often at odds with the RLHF performance leading to a trade-off between reward maximization and forgetting mitigation. In light of the above pressing issue in aligning LLMs in this paper we explore model averaging which interpolates between pre and post RLHF model weights to achieve a more efficient reward-tax Pareto front. To understand its effectiveness We offer theoretical insights into model averaging revealing that it enhances performance Pareto front by increasing feature diversity on the layers where tasks share overlapped feature spaces. Empirical evidence corroborates our analysis by showing the benefits of averaging low-level transformer layers. Building on the analysis and the observation that averaging different layers of the transformer leads to significantly different reward-tax trade-offs we propose Adaptive Model Averaging (AMA) to adaptively find various combination ratios of model layers. AMA seeks to maximize the alignment reward while incurring minimal alignment tax. Moreover we validate AMAs performance across a range of RLHF algorithms over OpenLLaMA-3B and further extend our findings to Mistral-7B.
