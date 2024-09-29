---
layout: publication
title: Fine Tuning Vs. Retrieval Augmented Generation For Less Popular Knowledge
authors: Soudani Heydar, Kanoulas Evangelos, Hasibi Faegheh
conference: "Arxiv"
year: 2024
bibkey: soudani2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01432"}
  - {name: "Code", url: "https://github.com/informagi/RAGvsFT"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large language models (LLMs) memorize a vast amount of factual knowledge exhibiting strong performance across diverse tasks and domains. However it has been observed that the performance diminishes when dealing with less-popular or low-frequency concepts and entities for example in domain specific applications. The two prominent approaches to enhance the performance of LLMs on low-frequent topics are Retrieval Augmented Generation (RAG) and fine-tuning (FT) over synthetic data. This paper explores and evaluates the impact of RAG and FT on customizing LLMs in handling low-frequency entities on question answering task. Our findings indicate that FT significantly boosts the performance across entities of varying popularity especially in the most and least popular groups while RAG surpasses other methods. Additionally the success of both RAG and FT approaches is amplified by advancements in retrieval and data augmentation techniques. We release our data and code at https://github.com/informagi/RAGvsFT.
