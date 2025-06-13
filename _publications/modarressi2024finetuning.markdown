---
layout: publication
title: 'Memllm: Finetuning Llms To Use An Explicit Read-write Memory'
authors: Ali Modarressi, Abdullatif Köksal, Ayyoob Imani, Mohsen Fayyaz, Hinrich Schütze
conference: "Arxiv"
year: 2024
bibkey: modarressi2024finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.11672"}
  - {name: "Code", url: "https://github.com/amodaresi/MemLLM"}
tags: ['Interpretability and Explainability', 'RAG', 'Has Code', 'Language Modeling']
---
While current large language models (LLMs) perform well on many
knowledge-related tasks, they are limited by relying on their parameters as an
implicit storage mechanism. As a result, they struggle with memorizing rare
events and with updating their memory as facts change over time. In addition,
the uninterpretable nature of parametric memory makes it challenging to prevent
hallucination. Model editing and augmenting LLMs with parameters specialized
for memory are only partial solutions. In this paper, we introduce MemLLM, a
novel method of enhancing LLMs by integrating a structured and explicit
read-and-write memory module. MemLLM tackles the aforementioned challenges by
enabling dynamic interaction with the memory and improving the LLM's
capabilities in using stored knowledge. Our experiments indicate that MemLLM
enhances the LLM's performance and interpretability, in language modeling in
general and knowledge-intensive tasks in particular. We see MemLLM as an
important step towards making LLMs more grounded and factual through memory
augmentation. The project repository is publicly available at
https://github.com/amodaresi/MemLLM
