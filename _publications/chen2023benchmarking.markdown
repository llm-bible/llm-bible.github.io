---
layout: publication
title: Benchmarking Large Language Models In Retrieval45;augmented Generation
authors: Chen Jiawei, Lin Hongyu, Han Xianpei, Sun Le
conference: "Arxiv"
year: 2023
bibkey: chen2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.01431"}
tags: ['RAG', 'Security']
---
Retrieval45;Augmented Generation (RAG) is a promising approach for mitigating the hallucination of large language models (LLMs). However existing research lacks rigorous evaluation of the impact of retrieval45;augmented generation on different large language models which make it challenging to identify the potential bottlenecks in the capabilities of RAG for different LLMs. In this paper we systematically investigate the impact of Retrieval45;Augmented Generation on large language models. We analyze the performance of different large language models in 4 fundamental abilities required for RAG including noise robustness negative rejection information integration and counterfactual robustness. To this end we establish Retrieval45;Augmented Generation Benchmark (RGB) a new corpus for RAG evaluation in both English and Chinese. RGB divides the instances within the benchmark into 4 separate testbeds based on the aforementioned fundamental abilities required to resolve the case. Then we evaluate 6 representative LLMs on RGB to diagnose the challenges of current LLMs when applying RAG. Evaluation reveals that while LLMs exhibit a certain degree of noise robustness they still struggle significantly in terms of negative rejection information integration and dealing with false information. The aforementioned assessment outcomes indicate that there is still a considerable journey ahead to effectively apply RAG to LLMs.
