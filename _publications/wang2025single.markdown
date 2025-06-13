---
layout: publication
title: 'Stshield: Single-token Sentinel For Real-time Jailbreak Detection In Large Language Models'
authors: Xunguang Wang, Wenxuan Wang, Zhenlan Ji, Zongjie Li, Pingchuan Ma, Daoyuan Wu, Shuai Wang
conference: "Arxiv"
year: 2025
bibkey: wang2025single
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17932"}
tags: ['Fine-Tuning', 'Responsible AI', 'Tools', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) have become increasingly vulnerable to jailbreak
attacks that circumvent their safety mechanisms. While existing defense methods
either suffer from adaptive attacks or require computationally expensive
auxiliary models, we present STShield, a lightweight framework for real-time
jailbroken judgement. STShield introduces a novel single-token sentinel
mechanism that appends a binary safety indicator to the model's response
sequence, leveraging the LLM's own alignment capabilities for detection. Our
framework combines supervised fine-tuning on normal prompts with adversarial
training using embedding-space perturbations, achieving robust detection while
preserving model utility. Extensive experiments demonstrate that STShield
successfully defends against various jailbreak attacks, while maintaining the
model's performance on legitimate queries. Compared to existing approaches,
STShield achieves superior defense performance with minimal computational
overhead, making it a practical solution for real-world LLM deployment.
