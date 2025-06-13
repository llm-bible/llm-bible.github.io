---
layout: publication
title: 'Empowering Llms In Task-oriented Dialogues: A Domain-independent Multi-agent Framework And Fine-tuning Strategy'
authors: Zihao Feng, Xiaoxue Wang, Bowen Wu, Weihong Zhong, Zhen Xu, Hailong Cao, Tiejun Zhao, Ying Li, Baoxun Wang
conference: "Arxiv"
year: 2025
bibkey: feng2025empowering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14299"}
tags: ['Agentic', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Task-oriented dialogue systems based on Large Language Models (LLMs) have gained increasing attention across various industries and achieved significant results. Current approaches condense complex procedural workflows into a single agent to achieve satisfactory performance on large-scale LLMs. However, these approaches face challenges to achieve comparable performance on fine-tuned lightweight LLMs, due to their limited capabilities in handling multiple complex logic. In this work, we design a Domain-Independent Multi-Agent Framework (DIMF), which contains Intent Classification Agent, Slot Filling Agent and Response Agent. This approach simplifies the learning complexity and enhances the generalization ability by separating the tasks into domain-independent components. In this framework, we enhance the capabilities in contextual understanding using the Direct Preference Optimisation (DPO) method, and propose a simple and effective Data Distribution Adaptation (DDA) method to mitigate degradation issues during DPO training. Experiments conducted on the MultiWOZ datasets show that our proposed method achieves a better average performance among all the baselines. Extensive analysis also demonstrates that our proposed framework exhibits excellent generalizability and zero-shot capability.
