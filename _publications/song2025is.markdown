---
layout: publication
title: 'Is LLM The Silver Bullet To Low-resource Languages Machine Translation?'
authors: Yewei Song, Lujun Li, Cedric Lothritz, Saad Ezzini, Lama Sleem, Niccolo Gentile, Radu State, Tegawendé F. Bissyandé, Jacques Klein
conference: "Arxiv"
year: 2025
bibkey: song2025is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.24102"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Low-Resource Languages (LRLs) present significant challenges in natural language processing due to their limited linguistic resources and underrepresentation in standard datasets. While recent advances in Large Language Models (LLMs) and Neural Machine Translation have substantially improved translation capabilities for high-resource languages, performance disparities persist for LRLs, particularly impacting privacy-sensitive and resource-constrained scenarios. This paper systematically evaluates current LLMs in 200 languages using the FLORES-200 benchmark and demonstrates their limitations in LRL translation capability. We also explore alternative data sources, including news articles and bilingual dictionaries, and demonstrate how knowledge distillation from large pre-trained teacher models can significantly improve the performance of small LLMs on LRL translation tasks. For example, this approach increases EN->LB with the LLM-as-a-Judge score on the validation set from 0.36 to 0.89 for Llama-3.2-3B. Furthermore, we examine different fine-tuning configurations, providing practical insights on optimal data scale, training efficiency, and the preservation of generalization capabilities of models under study.
