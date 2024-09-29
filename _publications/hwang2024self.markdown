---
layout: publication
title: Self-explore To Avoid The Pit: Improving The Reasoning Capabilities Of Language Models With Fine-grained Rewards
authors: Hwang Hyeonbin, Kim Doyoung, Kim Seungone, Ye Seonghyeon, Seo Minjoon
conference: "Arxiv"
year: 2024
bibkey: hwang2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10346"}
  - {name: "Code", url: "https://github.com/hbin0701/Self-Explore"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Training on large amounts of rationales (i.e. CoT Fine-tuning) is effective at improving the reasoning capabilities of large language models (LLMs). However acquiring human-authored rationales or augmenting rationales from proprietary models is costly and not scalable. In this paper we study the problem of whether LLMs could self-improve their reasoning capabilities. To this end we propose Self-Explore where the LLM is tasked to explore the first wrong step (i.e. the first pit) within the rationale and use such signals as fine-grained rewards for further improvement. On the GSM8K and MATH test set Self-Explore achieves 11.5737; and 2.8937; improvement on average across three LLMs compared to supervised fine-tuning (SFT). Our code is available at https://github.com/hbin0701/Self-Explore."
