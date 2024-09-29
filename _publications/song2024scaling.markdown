---
layout: publication
title: "Scaling Data Diversity For Fine-tuning Language Models In Human Alignment"
authors: Song Feifan, Yu Bowen, Lang Hao, Yu Haiyang, Huang Fei, Wang Houfeng, Li Yongbin
conference: "Arxiv"
year: 2024
bibkey: song2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11124"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Alignment with human preference prevents large language models (LLMs) from generating misleading or toxic content while requiring high-cost human feedback. Assuming resources of human annotation are limited there are two different ways of allocating considered more diverse PROMPTS or more diverse RESPONSES to be labeled. Nonetheless a straightforward comparison between their impact is absent. In this work we first control the diversity of both sides according to the number of samples for fine-tuning which can directly reflect their influence. We find that instead of numerous prompts more responses but fewer prompts better trigger LLMs for human alignment. Additionally the concept of diversity for prompts can be more complex than responses that are typically quantified by single digits. Consequently a new formulation of prompt diversity is proposed further implying a linear correlation with the final performance of LLMs after fine-tuning. We also leverage it on data augmentation and conduct experiments to show its effect on different algorithms.
