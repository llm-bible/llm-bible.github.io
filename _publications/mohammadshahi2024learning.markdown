---
layout: publication
title: Routoo\: Learning To Route To Large Language Models Effectively
authors: Mohammadshahi Alireza, Shaikh Arshad Rafiq, Yazdani Majid
conference: "Arxiv"
year: 2024
bibkey: mohammadshahi2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.13979"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Developing foundational large language models (LLMs) is becoming increasingly costly and inefficient. Also closed-source and larger open-source models generally offer better response quality but come with higher inference costs than smaller models. In this paper we introduce Routoo an architecture designed to optimize the selection of LLMs for specific prompts based on performance cost and efficiency. Routoo consists of two key components a performance predictor and a cost-aware decoding. The performance predictor is a lightweight LLM that estimates the performance of various underlying LLMs without needing to execute and evaluate them. The cost-aware decoding then selects the most suitable model based on these predictions and other constraints like cost and latency. We evaluated Routoo using the MMLU benchmark across 57 domains employing open-source models. Our results show that Routoo matches the performance of the Mixtral 8x7b model while reducing inference costs by one-third. Additionally by allowing increased costs Routoo surpasses Mixtrals accuracy by over 537; at equivalent costs achieving an accuracy of 75.937;. When integrating GPT4 into our model pool Routoo nearly matches GPT4s performance at half the cost and exceeds it with a 2537; cost reduction. These outcomes highlight Routoos potential to create new SOTA in a cost-effective manner by leveraging the collective knowledge of multiple LLMs.
