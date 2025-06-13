---
layout: publication
title: 'Llm\(\times\)mapreduce: Simplified Long-sequence Processing Using Large Language Models'
authors: Zihan Zhou, Chong Li, Xinyi Chen, Shuo Wang, Yu Chao, Zhili Li, Haoyu Wang, Rongqiao An, Qi Shi, Zhixing Tan, Xu Han, Xiaodong Shi, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: zhou2024simplified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09342"}
tags: ['Training Techniques', 'Tools', 'Applications', 'Reinforcement Learning']
---
Enlarging the context window of large language models (LLMs) has become a
crucial research area, particularly for applications involving extremely long
texts. In this work, we propose a novel training-free framework for processing
long texts, utilizing a divide-and-conquer strategy to achieve comprehensive
document understanding. The proposed LLM\\(\times\\)MapReduce framework splits the
entire document into several chunks for LLMs to read and then aggregates the
intermediate answers to produce the final output. The main challenge for
divide-and-conquer long text processing frameworks lies in the risk of losing
essential long-range information when splitting the document, which can lead
the model to produce incomplete or incorrect answers based on the segmented
texts. Disrupted long-range information can be classified into two categories:
inter-chunk dependency and inter-chunk conflict. We design a structured
information protocol to better cope with inter-chunk dependency and an
in-context confidence calibration mechanism to resolve inter-chunk conflicts.
Experimental results demonstrate that LLM\\(\times\\)MapReduce can outperform
representative open-source and commercial long-context LLMs, and is applicable
to several different models.
