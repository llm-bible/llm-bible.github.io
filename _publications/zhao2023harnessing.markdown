---
layout: publication
title: 'Tabula: Harnessing Language Models For Tabular Data Synthesis'
authors: Zhao Zilong, Birke Robert, Chen Lydia
conference: "Arxiv"
year: 2023
bibkey: zhao2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.12746"}
tags: ['Pretraining Methods', 'RAG', 'Security', 'Training Techniques']
---
Given the ubiquitous use of tabular data in industries and the growing concerns in data privacy and security tabular data synthesis emerges as a critical research area. The recent state-of-the-art methods show that large language models (LLMs) can be adopted to generate realistic tabular data. As LLMs pre-process tabular data as full text they have the advantage of avoiding the curse of dimensionality associated with one-hot encoding high-dimensional data. However their long training time and limited re-usability on new tasks prevent them from replacing exiting tabular generative models. In this paper we propose Tabula a tabular data synthesizer based on the language model structure. Through Tabula we demonstrate the inherent limitation of employing pre-trained language models designed for natural language processing (NLP) in the context of tabular data synthesis. Our investigation delves into the development of a dedicated foundational model tailored specifically for tabular data synthesis. Additionally we propose a token sequence compression strategy to significantly reduce training time while preserving the quality of synthetic data. Extensive experiments on six datasets demonstrate that using a language model structure without loading the well-trained model weights yields a better starting model for tabular data synthesis. Moreover the Tabula model previously trained on other tabular data serves as an excellent foundation model for new tabular data synthesis tasks. Additionally the token sequence compression method substantially reduces the models training time. Results show that Tabula averagely reduces 46.237; training time per epoch comparing to current LLMs-based state-of-the-art algorithm and consistently achieves even higher synthetic data utility.
