---
layout: publication
title: 'Fine Tuning Vs. Retrieval Augmented Generation For Less Popular Knowledge'
authors: Heydar Soudani, Evangelos Kanoulas, Faegheh Hasibi
conference: "Arxiv"
year: 2024
bibkey: soudani2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01432"}
  - {name: "Code", url: "https://github.com/informagi/RAGvsFT"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Language Models (LMs) memorize a vast amount of factual knowledge, exhibiting
strong performance across diverse tasks and domains. However, it has been
observed that the performance diminishes when dealing with less-popular or
low-frequency concepts and entities, for example in domain specific
applications. The two prominent approaches to enhance the performance of LMs on
low-frequent topics are: Retrieval Augmented Generation (RAG) and fine-tuning
(FT) over synthetic data. This paper explores and evaluates the impact of RAG
and FT on customizing LMs in handling low-frequency entities on question
answering tasks. We conduct extensive experiments on twelve LMs of varying size
and type and different fine tuning, data augmentation, and retrieval models.
Our findings indicate that while FT boosts the performance across entities of
varying popularity, RAG surpasses FT by a large margin particularly for least
popular factual knowledge. Additionally, the success of both RAG and FT
approaches is amplified by improving retrieval and data augmentation
techniques. Fine tuning, while beneficial for small LMs, requires extensive
resources. To address this issue, we propose the new Stimulus RAG approach that
surpasses the effectiveness of fine tuning based approaches, thereby
eliminating the need for the costly data augmentation and fine tuning step for
enriching LMs with less popular factual knowledge. The code is available at
\url\{https://github.com/informagi/RAGvsFT\}.
