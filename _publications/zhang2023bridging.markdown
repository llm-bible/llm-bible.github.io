---
layout: publication
title: Bridging The Information Gap Between Domain45;specific Model And General LLM For Personalized Recommendation
authors: Zhang Wenxuan, Liu Hongzhi, Du Yingpeng, Zhu Chen, Song Yang, Zhu Hengshu, Wu Zhonghai
conference: "Arxiv"
year: 2023
bibkey: zhang2023bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.03778"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Generative large language models(LLMs) are proficient in solving general problems but often struggle to handle domain45;specific tasks. This is because most of domain45;specific tasks such as personalized recommendation rely on task45;related information for optimal performance. Current methods attempt to supplement task45;related information to LLMs by designing appropriate prompts or employing supervised fine45;tuning techniques. Nevertheless these methods encounter the certain issue that information such as community behavior pattern in RS domain is challenging to express in natural language which limits the capability of LLMs to surpass state45;of45;the45;art domain45;specific models. On the other hand domain45;specific models for personalized recommendation which mainly rely on user interactions are susceptible to data sparsity due to their limited common knowledge capabilities. To address these issues we proposes a method to bridge the information gap between the domain45;specific models and the general large language models. Specifically we propose an information sharing module which serves as an information storage mechanism and also acts as a bridge for collaborative training between the LLMs and domain45;specific models. By doing so we can improve the performance of LLM45;based recommendation with the help of user behavior pattern information mined by domain45;specific models. On the other hand the recommendation performance of domain45;specific models can also be improved with the help of common knowledge learned by LLMs. Experimental results on three real45;world datasets have demonstrated the effectiveness of the proposed method.
