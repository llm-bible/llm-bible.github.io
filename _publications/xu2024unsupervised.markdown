---
layout: publication
title: Unsupervised Information Refinement Training Of Large Language Models For Retrieval45;augmented Generation
authors: Xu Shicheng, Pang Liang, Yu Mo, Meng Fandong, Shen Huawei, Cheng Xueqi, Zhou Jie
conference: "Arxiv"
year: 2024
bibkey: xu2024unsupervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.18150"}
tags: ['Applications', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Retrieval45;augmented generation (RAG) enhances large language models (LLMs) by incorporating additional information from retrieval. However studies have shown that LLMs still face challenges in effectively using the retrieved information even ignoring it or being misled by it. The key reason is that the training of LLMs does not clearly make LLMs learn how to utilize input retrieved texts with varied quality. In this paper we propose a novel perspective that considers the role of LLMs in RAG as Information Refiner which means that regardless of correctness completeness or usefulness of retrieved texts LLMs can consistently integrate knowledge within the retrieved texts and model parameters to generate the texts that are more concise accurate and complete than the retrieved texts. To this end we propose an information refinement training method named InFO45;RAG that optimizes LLMs for RAG in an unsupervised manner. InFO45;RAG is low45;cost and general across various tasks. Extensive experiments on zero45;shot prediction of 11 datasets in diverse tasks including Question Answering Slot45;Filling Language Modeling Dialogue and Code Generation show that InFO45;RAG improves the performance of LLaMA2 by an average of 9.3937; relative points. InFO45;RAG also shows advantages in in45;context learning and robustness of RAG.
