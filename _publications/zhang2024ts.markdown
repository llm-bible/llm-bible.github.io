---
layout: publication
title: Ts-align&#58; A Teacher-student Collaborative Framework For Scalable Iterative Finetuning Of Large Language Models
authors: Zhang Chen, Tang Chengguang, Chong Dading, Shi Ke, Tang Guohua, Jiang Feng, Li Haizhou
conference: "Arxiv"
year: 2024
bibkey: zhang2024ts
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20215"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Mainstream approaches to aligning large language models (LLMs) heavily rely on human preference data particularly when models require periodic updates. The standard process for iterative alignment of LLMs involves collecting new human feedback for each update. However the data collection process is costly and challenging to scale. To address this issue we introduce the TS-Align framework which fine-tunes a policy model using pairwise feedback data automatically mined from its outputs. This automatic mining process is efficiently accomplished through the collaboration between a large-scale teacher model and a small-scale student model. The policy fine-tuning process can be iteratively repeated using on-policy generations within our proposed teacher-student collaborative framework. Through extensive experiments we demonstrate that our final aligned policy outperforms the base policy model with an average win rate of 69.737; across seven conversational or instruction-following datasets. Furthermore we show that the ranking capability of the teacher is effectively distilled into the student through our pipeline resulting in a small-scale yet effective reward model for policy model alignment.
