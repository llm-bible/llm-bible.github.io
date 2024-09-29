---
layout: publication
title: 'Fine-tuning Or Fine-failing? Debunking Performance Myths In Large Language Models'
authors: Barnett Scott, Brannelly Zac, Kurniawan Stefanus, Wong Sheng
conference: "Arxiv"
year: 2024
bibkey: barnett2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11201"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have the unique capability to understand and generate human-like text from input queries. When fine-tuned these models show enhanced performance on domain-specific queries. OpenAI highlights the process of fine-tuning stating To fine-tune a model you are required to provide at least 10 examples. We typically see clear improvements from fine-tuning on 50 to 100 training examples but the right number varies greatly based on the exact use case. This study extends this concept to the integration of LLMs within Retrieval-Augmented Generation (RAG) pipelines which aim to improve accuracy and relevance by leveraging external corpus data for information retrieval. However RAGs promise of delivering optimal responses often falls short in complex query scenarios. This study aims to specifically examine the effects of fine-tuning LLMs on their ability to extract and integrate contextual data to enhance the performance of RAG systems across multiple domains. We evaluate the impact of fine-tuning on the LLMs capacity for data extraction and contextual understanding by comparing the accuracy and completeness of fine-tuned models against baseline performances across datasets from multiple domains. Our findings indicate that fine-tuning resulted in a decline in performance compared to the baseline models contrary to the improvements observed in standalone LLM applications as suggested by OpenAI. This study highlights the need for vigorous investigation and validation of fine-tuned models for domain-specific tasks.
