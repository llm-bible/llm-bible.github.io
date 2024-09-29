---
layout: publication
title: Quickllama Query45;aware Inference Acceleration For Large Language Models
authors: Li Jingyao, Shi Han, Jiang Xin, Li Zhenguo, Xu Hong, Jia Jiaya
conference: "Arxiv"
year: 2024
bibkey: li2024query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07528"}
  - {name: "Code", url: "https://github.com/dvlab&#45;research/Q&#45;LLM"}
tags: ['Has Code', 'Pretraining Methods', 'Training Techniques']
---
The capacity of Large Language Models (LLMs) to comprehend and reason over long contexts is pivotal for advancements in diverse fields. Yet they still stuggle with capturing long45;distance dependencies within sequences to deeply understand semantics. To address this issue we introduce Query45;aware Inference for LLMs (Q45;LLM) a system designed to process extensive sequences akin to human cognition. By focusing on memory data relevant to a given query Q45;LLM can accurately capture pertinent information within a fixed window size and provide precise answers to queries. It doesnt require extra training and can be seamlessly integrated with any LLMs. Q45;LLM using LLaMA3 (QuickLLaMA) can read Harry Potter within 30s and accurately answer the questions. On widely recognized benchmarks Q45;LLM improved by 7.1737; compared to the current state45;of45;the45;art on LLaMA3 and by 3.2637; on Mistral on the ∞45;bench. In the Needle45;in45;a45;Haystack and BABILong task Q45;LLM improved upon the current SOTA by 7.037; and 6.137;. Our code can be found in https://github.com/dvlab&#45;research/Q&#45;LLM.
