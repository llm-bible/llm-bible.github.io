---
layout: publication
title: 'Quantifying Memorization And Retriever Performance In Retrieval-augmented Vision-language Models'
authors: Peter Carragher, Abhinand Jha, R Raghav, Kathleen M. Carley
conference: "Arxiv"
year: 2025
bibkey: carragher2025quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13836"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'RAG', 'GPT']
---
Large Language Models (LLMs) demonstrate remarkable capabilities in question
answering (QA), but metrics for assessing their reliance on memorization versus
retrieval remain underdeveloped. Moreover, while finetuned models are
state-of-the-art on closed-domain tasks, general-purpose models like GPT-4o
exhibit strong zero-shot performance. This raises questions about the
trade-offs between memorization, generalization, and retrieval. In this work,
we analyze the extent to which multimodal retrieval-augmented VLMs memorize
training data compared to baseline VLMs. Using the WebQA benchmark, we contrast
finetuned models with baseline VLMs on multihop retrieval and question
answering, examining the impact of finetuning on data memorization. To quantify
memorization in end-to-end retrieval and QA systems, we propose several proxy
metrics by investigating instances where QA succeeds despite retrieval failing.
Our results reveal the extent to which finetuned models rely on memorization.
In contrast, retrieval-augmented VLMs have lower memorization scores, at the
cost of accuracy (72% vs 52% on WebQA test set). As such, our measures pose a
challenge for future work to reconcile memorization and generalization in both
Open-Domain QA and joint Retrieval-QA tasks.
