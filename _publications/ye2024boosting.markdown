---
layout: publication
title: Boosting Conversational Question Answering with Fine-Grained Retrieval-Augmentation and Self-Check
authors: Ye Linhao, Lei Zhikai, Yin Jianghao, Chen Qin, Zhou Jie, He Liang
conference: "Arxiv"
year: 2024
bibkey: ye2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18243"}
tags: ['Applications', 'RAG']
---
Retrieval-Augmented Generation (RAG) aims to generate more reliable and accurate responses by augmenting large language models (LLMs) with the external vast and dynamic knowledge. Most previous work focuses on using RAG for single-round question answering while how to adapt RAG to the complex conversational setting wherein the question is interdependent on the preceding context is not well studied. In this paper we propose a conversation-level RAG approach which incorporates fine-grained retrieval augmentation and self-check for conversational question answering (CQA). In particular our approach consists of three components namely conversational question refiner fine-grained retriever and self-check based response generator which work collaboratively for question understanding and relevant information acquisition in conversational settings. Extensive experiments demonstrate the great advantages of our approach over the state-of-the-art baselines. Moreover we also release a Chinese CQA dataset with new features including reformulated question extracted keyword retrieved paragraphs and their helpfulness which facilitates further researches in RAG enhanced CQA.
