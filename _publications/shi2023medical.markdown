---
layout: publication
title: MKRAG Medical Knowledge Retrieval Augmented Generation For Medical Question Answering
authors: Shi Yucheng, Xu Shaochen, Yang Tianze, Liu Zhengliang, Liu Tianming, Li Quanzheng, Li Xiang, Liu Ninghao
conference: "Arxiv"
year: 2023
bibkey: shi2023medical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16035"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) although powerful in general domains often perform poorly on domain-specific tasks such as medical question answering (QA). In addition LLMs tend to function as black-boxes making it challenging to modify their behavior. To address the problem our work employs a transparent process of retrieval augmented generation (RAG) aiming to improve LLM responses without the need for fine-tuning or retraining. Specifically we propose a comprehensive retrieval strategy to extract medical facts from an external knowledge base and then inject them into the LLMs query prompt. Focusing on medical QA we evaluate the impact of different retrieval models and the number of facts on LLM performance using the MedQA-SMILE dataset. Notably our retrieval-augmented Vicuna-7B model exhibited an accuracy improvement from 44.4637; to 48.5437;. This work underscores the potential of RAG to enhance LLM performance offering a practical approach to mitigate the challenges posed by black-box LLMs.
