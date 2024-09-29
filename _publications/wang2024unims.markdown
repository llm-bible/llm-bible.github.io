---
layout: publication
title: 'Unims-rag: A Unified Multi-source Retrieval-augmented Generation For Personalized Dialogue Systems'
authors: Wang Hongru, Huang Wenyu, Deng Yang, Wang Rui, Wang Zezhong, Wang Yufei, Mi Fei, Pan Jeff Z., Wong Kam-fai
conference: "Arxiv"
year: 2024
bibkey: wang2024unims
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13256"}
tags: ['Applications', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) has shown exceptional capabilities in many natual language understanding and generation tasks. However the personalization issue still remains a much-coveted property especially when it comes to the multiple sources involved in the dialogue system. To better plan and incorporate the use of multiple sources in generating personalized response we firstly decompose it into three sub-tasks Knowledge Source Selection Knowledge Retrieval and Response Generation. We then propose a novel Unified Multi-Source Retrieval-Augmented Generation system (UniMS-RAG) Specifically we unify these three sub-tasks with different formulations into the same sequence-to-sequence paradigm during the training to adaptively retrieve evidences and evaluate the relevance on-demand using special tokens called acting tokens and evaluation tokens. Enabling language models to generate acting tokens facilitates interaction with various knowledge sources allowing them to adapt their behavior to diverse task requirements. Meanwhile evaluation tokens gauge the relevance score between the dialogue context and the retrieved evidence. In addition we carefully design a self-refinement mechanism to iteratively refine the generated response considering 1) the consistency scores between the generated response and retrieved evidence; and 2) the relevance scores. Experiments on two personalized datasets (DuLeMon and KBP) show that UniMS-RAG achieves state-of-the-art performance on the knowledge source selection and response generation task with itself as a retriever in a unified manner. Extensive analyses and discussions are provided for shedding some new perspectives for personalized dialogue systems.
