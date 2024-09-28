---
layout: publication
title: Enhancing LLM Factual Accuracy with RAG to Counter Hallucinations A Case Study on Domain-Specific Queries in Private Knowledge-Bases
authors: Li Jiarui, Yuan Ye, Zhang Zehua
conference: "Arxiv"
year: 2024
bibkey: li2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10446"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
We proposed an end-to-end system design towards utilizing Retrieval Augmented Generation (RAG) to improve the factual accuracy of Large Language Models (LLMs) for domain-specific and time-sensitive queries related to private knowledge-bases. Our system integrates RAG pipeline with upstream datasets processing and downstream performance evaluation. Addressing the challenge of LLM hallucinations we finetune models with a curated dataset which originates from CMUs extensive resources and annotated with the teacher model. Our experiments demonstrate the systems effectiveness in generating more accurate answers to domain-specific and time-sensitive inquiries. The results also revealed the limitations of fine-tuning LLMs with small-scale and skewed datasets. This research highlights the potential of RAG systems in augmenting LLMs with external datasets for improved performance in knowledge-intensive tasks. Our code and models are available on Github.
