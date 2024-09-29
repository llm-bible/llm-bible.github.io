---
layout: publication
title: Benchmarking Retrieval45;augmented Generation For Medicine
authors: Xiong Guangzhi, Jin Qiao, Lu Zhiyong, Zhang Aidong
conference: "Arxiv"
year: 2024
bibkey: xiong2024benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13178"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG']
---
While large language models (LLMs) have achieved state45;of45;the45;art performance on a wide range of medical question answering (QA) tasks they still face challenges with hallucinations and outdated knowledge. Retrieval45;augmented generation (RAG) is a promising solution and has been widely adopted. However a RAG system can involve multiple flexible components and there is a lack of best practices regarding the optimal RAG setting for various medical purposes. To systematically evaluate such systems we propose the Medical Information Retrieval45;Augmented Generation Evaluation (MIRAGE) a first45;of45;its45;kind benchmark including 7663 questions from five medical QA datasets. Using MIRAGE we conducted large45;scale experiments with over 1.8 trillion prompt tokens on 41 combinations of different corpora retrievers and backbone LLMs through the MedRAG toolkit introduced in this work. Overall MedRAG improves the accuracy of six different LLMs by up to 1837; over chain45;of45;thought prompting elevating the performance of GPT45;3.5 and Mixtral to GPT45;445;level. Our results show that the combination of various medical corpora and retrievers achieves the best performance. In addition we discovered a log45;linear scaling property and the lost45;in45;the45;middle effects in medical RAG. We believe our comprehensive evaluations can serve as practical guidelines for implementing RAG systems for medicine.
