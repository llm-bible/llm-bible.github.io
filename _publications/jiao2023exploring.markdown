---
layout: publication
title: Exploring Self45;supervised Logic45;enhanced Training For Large Language Models
authors: Jiao Fangkai, Teng Zhiyang, Ding Bosheng, Liu Zhengyuan, Chen Nancy F., Joty Shafiq
conference: "Arxiv"
year: 2023
bibkey: jiao2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13718"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Existing efforts to improve logical reasoning ability of language models have predominantly relied on supervised fine45;tuning hindering generalization to new domains and/or tasks. The development of Large Langauge Models (LLMs) has demonstrated the capacity of compressing abundant knowledge into a single proxy enabling them to tackle multiple tasks effectively. Our preliminary experiments nevertheless show that LLMs do not show capability on logical reasoning. The performance of LLMs on logical reasoning benchmarks is far behind the existing state45;of45;the45;art baselines. In this paper we make the first attempt to investigate the feasibility of incorporating logical knowledge through self45;supervised post45;training and activating it via in45;context learning which we termed as LogicLLM. Specifically we devise an auto45;regressive objective variant of MERIt and integrate it with two LLM series i.e. FLAN45;T5 and LLaMA with parameter size ranging from 3 billion to 13 billion. The results on two challenging logical reasoning benchmarks demonstrate the effectiveness of LogicLLM. Besides we conduct extensive ablation studies to analyze the key factors in designing logic45;oriented proxy tasks.
