---
layout: publication
title: Mafin Enhancing Black-box Embeddings With Model Augmented Fine-tuning
authors: Zhang Mingtian, Lan Shawn, Hayes Peter, Barber David
conference: "Arxiv"
year: 2024
bibkey: zhang2024mafin
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12177"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Retrieval Augmented Generation (RAG) has emerged as an effective solution for mitigating hallucinations in Large Language Models (LLMs). The retrieval stage in RAG typically involves a pre-trained embedding model which converts queries and passages into vectors to capture their semantics. However a standard pre-trained embedding model may exhibit sub-optimal performance when applied to specific domain knowledge necessitating fine-tuning. This paper addresses scenarios where the embeddings are only available from a black-box model. We introduce Model augmented fine-tuning (Mafin) -- a novel approach for fine-tuning a black-box embedding model by augmenting it with a trainable embedding model. Our results demonstrate that Mafin significantly enhances the performance of the black-box embeddings by only requiring the training of a small augmented model. We validate the effectiveness of our method on both labeled and unlabeled datasets illustrating its broad applicability and efficiency.
