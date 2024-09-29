---
layout: publication
title: Flexkbqa\: A Flexible Llm-powered Framework For Few-shot Knowledge Base Question Answering
authors: Li Zhenyu, Fan Sunqi, Gu Yu, Li Xiuxing, Duan Zhichao, Dong Bowen, Liu Ning, Wang Jianyong
conference: "Arxiv"
year: 2023
bibkey: li2023flexible
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12060"}
tags: ['Applications', 'Few Shot', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Knowledge base question answering (KBQA) is a critical yet challenging task due to the vast number of entities within knowledge bases and the diversity of natural language questions posed by users. Unfortunately the performance of most KBQA models tends to decline significantly in real-world scenarios where high-quality annotated data is insufficient. To mitigate the burden associated with manual annotation we introduce FlexKBQA by utilizing Large Language Models (LLMs) as program translators for addressing the challenges inherent in the few-shot KBQA task. Specifically FlexKBQA leverages automated algorithms to sample diverse programs such as SPARQL queries from the knowledge base which are subsequently converted into natural language questions via LLMs. This synthetic dataset facilitates training a specialized lightweight model for the KB. Additionally to reduce the barriers of distribution shift between synthetic data and real user questions FlexKBQA introduces an executionguided self-training method to iterative leverage unlabeled user questions. Furthermore we explore harnessing the inherent reasoning capability of LLMs to enhance the entire framework. Consequently FlexKBQA delivers substantial flexibility encompassing data annotation deployment and being domain agnostic. Through extensive experiments on GrailQA WebQSP and KQA Pro we observe that under the few-shot even the more challenging zero-shot scenarios FlexKBQA achieves impressive results with a few annotations surpassing all previous baselines and even approaching the performance of supervised models achieving a remarkable 9337; performance relative to the fully-supervised models. We posit that FlexKBQA represents a significant advancement towards exploring better integration of large and lightweight models. The code is open-sourced.
