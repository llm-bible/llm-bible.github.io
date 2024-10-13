---
layout: publication
title: 'Prompt Tuning As User Inherent Profile Inference Machine'
authors: Lu Yusheng, Du Zhaocheng, Li Xiangyang, Zhao Xiangyu, Liu Weiwen, Wang Yichao, Guo Huifeng, Tang Ruiming, Dong Zhenhua, Duan Yongrui
conference: "Arxiv"
year: 2024
bibkey: lu2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06577"}
tags: ['Efficiency And Optimization', 'Prompting', 'Quantization', 'Reinforcement Learning', 'Security']
---
Large Language Models (LLMs) have exhibited significant promise in
recommender systems by empowering user profiles with their extensive world
knowledge and superior reasoning capabilities. However, LLMs face challenges
like unstable instruction compliance, modality gaps, and high inference
latency, leading to textual noise and limiting their effectiveness in
recommender systems. To address these challenges, we propose UserIP-Tuning,
which uses prompt-tuning to infer user profiles. It integrates the causal
relationship between user profiles and behavior sequences into LLMs' prompts.
And employs expectation maximization to infer the embedded latent profile,
minimizing textual noise by fixing the prompt template. Furthermore, A profile
quantization codebook bridges the modality gap by categorizing profile
embeddings into collaborative IDs, which are pre-stored for online deployment.
This improves time efficiency and reduces memory usage. Experiments on four
public datasets show that UserIP-Tuning outperforms state-of-the-art
recommendation algorithms. Additional tests and case studies confirm its
effectiveness, robustness, and transferability.
