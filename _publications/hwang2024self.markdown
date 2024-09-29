---
layout: publication
title: Self45;explore To Avoid The Pit Improving The Reasoning Capabilities Of Language Models With Fine45;grained Rewards
authors: Hwang Hyeonbin, Kim Doyoung, Kim Seungone, Ye Seonghyeon, Seo Minjoon
conference: "Arxiv"
year: 2024
bibkey: hwang2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10346"}
  - {name: "Code", url: "https://github.com/hbin0701/Self&#45;Explore"}
tags: ['Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Training on large amounts of rationales (i.e. CoT Fine45;tuning) is effective at improving the reasoning capabilities of large language models (LLMs). However acquiring human45;authored rationales or augmenting rationales from proprietary models is costly and not scalable. In this paper we study the problem of whether LLMs could self45;improve their reasoning capabilities. To this end we propose Self45;Explore where the LLM is tasked to explore the first wrong step (i.e. the first pit) within the rationale and use such signals as fine45;grained rewards for further improvement. On the GSM8K and MATH test set Self45;Explore achieves 11.5737; and 2.8937; improvement on average across three LLMs compared to supervised fine45;tuning (SFT). Our code is available at https://github.com/hbin0701/Self&#45;Explore.
