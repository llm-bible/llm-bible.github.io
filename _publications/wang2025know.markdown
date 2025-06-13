---
layout: publication
title: 'Know You First And Be You Better: Modeling Human-like User Simulators Via Implicit Profiles'
authors: Kuang Wang, Xianfei Li, Shenghao Yang, Li Zhou, Feng Jiang, Haizhou Li
conference: "Arxiv"
year: 2025
bibkey: wang2025know
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18968"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
User simulators are crucial for replicating human interactions with dialogue systems, supporting both collaborative training and automatic evaluation, especially for large language models (LLMs). However, current role-playing methods face challenges such as a lack of utterance-level authenticity and user-level diversity, often hindered by role confusion and dependence on predefined profiles of well-known figures. In contrast, direct simulation focuses solely on text, neglecting implicit user traits like personality and conversation-level consistency. To address these issues, we introduce the User Simulator with Implicit Profiles (USP), a framework that infers implicit user profiles from human-machine interactions to simulate personalized and realistic dialogues. We first develop an LLM-driven extractor with a comprehensive profile schema, then refine the simulation using conditional supervised fine-tuning and reinforcement learning with cycle consistency, optimizing at both the utterance and conversation levels. Finally, a diverse profile sampler captures the distribution of real-world user profiles. Experimental results show that USP outperforms strong baselines in terms of authenticity and diversity while maintaining comparable consistency. Additionally, using USP to evaluate LLM on dynamic multi-turn aligns well with mainstream benchmarks, demonstrating its effectiveness in real-world applications.
