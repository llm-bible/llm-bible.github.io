---
layout: publication
title: Quickllama&#58; Query-aware Inference Acceleration For Large Language Models
authors: Li Jingyao, Shi Han, Jiang Xin, Li Zhenguo, Xu Hong, Jia Jiaya
conference: "Arxiv"
year: 2024
bibkey: li2024query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07528"}
  - {name: "Code", url: "https://github.com/dvlab-research/Q-LLM"}
tags: ['Has Code', 'Pretraining Methods', 'Training Techniques']
---
The capacity of Large Language Models (LLMs) to comprehend and reason over long contexts is pivotal for advancements in diverse fields. Yet they still stuggle with capturing long-distance dependencies within sequences to deeply understand semantics. To address this issue we introduce Query-aware Inference for LLMs (Q-LLM) a system designed to process extensive sequences akin to human cognition. By focusing on memory data relevant to a given query Q-LLM can accurately capture pertinent information within a fixed window size and provide precise answers to queries. It doesnt require extra training and can be seamlessly integrated with any LLMs. Q-LLM using LLaMA3 (QuickLLaMA) can read Harry Potter within 30s and accurately answer the questions. On widely recognized benchmarks Q-LLM improved by 7.1737; compared to the current state-of-the-art on LLaMA3 and by 3.2637; on Mistral on the (infty)-bench. In the Needle-in-a-Haystack and BABILong task Q-LLM improved upon the current SOTA by 7.037; and 6.137;. Our code can be found in https://github.com/dvlab-research/Q-LLM."
