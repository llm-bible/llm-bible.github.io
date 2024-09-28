---
layout: publication
title: Bridging the Information Gap Between Domain-Specific Model and General LLM for Personalized Recommendation
authors: Zhang Wenxuan, Liu Hongzhi, Du Yingpeng, Zhu Chen, Song Yang, Zhu Hengshu, Wu Zhonghai
conference: "Arxiv"
year: 2023
bibkey: zhang2023bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.03778"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Generative large language models(LLMs) are proficient in solving general problems but often struggle to handle domain-specific tasks. This is because most of domain-specific tasks such as personalized recommendation rely on task-related information for optimal performance. Current methods attempt to supplement task-related information to LLMs by designing appropriate prompts or employing supervised fine-tuning techniques. Nevertheless these methods encounter the certain issue that information such as community behavior pattern in RS domain is challenging to express in natural language which limits the capability of LLMs to surpass state-of-the-art domain-specific models. On the other hand domain-specific models for personalized recommendation which mainly rely on user interactions are susceptible to data sparsity due to their limited common knowledge capabilities. To address these issues we proposes a method to bridge the information gap between the domain-specific models and the general large language models. Specifically we propose an information sharing module which serves as an information storage mechanism and also acts as a bridge for collaborative training between the LLMs and domain-specific models. By doing so we can improve the performance of LLM-based recommendation with the help of user behavior pattern information mined by domain-specific models. On the other hand the recommendation performance of domain-specific models can also be improved with the help of common knowledge learned by LLMs. Experimental results on three real-world datasets have demonstrated the effectiveness of the proposed method.
