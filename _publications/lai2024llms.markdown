---
layout: publication
title: Llms Beyond English Scaling The Multilingual Capability Of Llms With Cross45;lingual Feedback
authors: Lai Wen, Mesgar Mohsen, Fraser Alexander
conference: "Arxiv"
year: 2024
bibkey: lai2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01771"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
To democratize large language models (LLMs) to most natural languages it is imperative to make these models capable of understanding and generating texts in many languages in particular low45;resource ones. While recent multilingual LLMs demonstrate remarkable performance in such capabilities these LLMs still support a limited number of human languages due to the lack of training data for low45;resource languages. Moreover these LLMs are not yet aligned with human preference for downstream tasks which is crucial for the success of LLMs in English. In this paper we introduce xLLaMA45;100 and xBLOOM45;100 (collectively xLLMs45;100) which scale the multilingual capabilities of LLaMA and BLOOM to 100 languages. To do so we construct two datasets a multilingual instruction dataset including 100 languages which represents the largest language coverage to date and a cross45;lingual human feedback dataset encompassing 30 languages. We perform multilingual instruction tuning on the constructed instruction data and further align the LLMs with human feedback using the DPO algorithm on our cross45;lingual human feedback dataset. We evaluate the multilingual understanding and generating capabilities of xLLMs45;100 on five multilingual benchmarks. Experimental results show that xLLMs45;100 consistently outperforms its peers across the benchmarks by considerable margins defining a new state45;of45;the45;art multilingual LLM that supports 100 languages.
