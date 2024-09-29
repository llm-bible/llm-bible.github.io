---
layout: publication
title: Rella Retrieval45;enhanced Large Language Models For Lifelong Sequential Behavior Comprehension In Recommendation
authors: Lin Jianghao, Shan Rong, Zhu Chenxu, Du Kounianhua, Chen Bo, Quan Shigang, Tang Ruiming, Yu Yong, Zhang Weinan
conference: "Arxiv"
year: 2023
bibkey: lin2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11131"}
  - {name: "Code", url: "https://github.com/LaVieEnRose365/ReLLa&#125;"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
With large language models (LLMs) achieving remarkable breakthroughs in natural language processing (NLP) domains LLM45;enhanced recommender systems have received much attention and have been actively explored currently. In this paper we focus on adapting and empowering a pure large language model for zero45;shot and few45;shot recommendation tasks. First and foremost we identify and formulate the lifelong sequential behavior incomprehension problem for LLMs in recommendation domains i.e. LLMs fail to extract useful information from a textual context of long user behavior sequence even if the length of context is far from reaching the context limitation of LLMs. To address such an issue and improve the recommendation performance of LLMs we propose a novel framework namely Retrieval45;enhanced Large Language models (ReLLa) for recommendation tasks in both zero45;shot and few45;shot settings. For zero45;shot recommendation we perform semantic user behavior retrieval (SUBR) to improve the data quality of testing samples which greatly reduces the difficulty for LLMs to extract the essential knowledge from user behavior sequences. As for few45;shot recommendation we further design retrieval45;enhanced instruction tuning (ReiT) by adopting SUBR as a data augmentation technique for training samples. Specifically we develop a mixed training dataset consisting of both the original data samples and their retrieval45;enhanced counterparts. We conduct extensive experiments on three real45;world public datasets to demonstrate the superiority of ReLLa compared with existing baseline models as well as its capability for lifelong sequential behavior comprehension. To be highlighted with only less than 1037; training samples few45;shot ReLLa can outperform traditional CTR models that are trained on the entire training set (e.g. DCNv2 DIN SIM). The code is available url123;https://github.com/LaVieEnRose365/ReLLa&#125;.
