---
layout: publication
title: Leave No Document Behind Benchmarking Long-Context LLMs with Extended Multi-Doc QA
authors: Wang Minzheng, Chen Longze, Fu Cheng, Liao Shengyi, Zhang Xinghua, Wu Bingli, Yu Haiyang, Xu Nan, Zhang Lei, Luo Run, Li Yunshui, Yang Min, Huang Fei, Li Yongbin
conference: "Arxiv"
year: 2024
bibkey: wang2024leave
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17419"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Long-context modeling capabilities have garnered widespread attention leading to the emergence of Large Language Models (LLMs) with ultra-context windows. Meanwhile benchmarks for evaluating long-context LLMs are gradually catching up. However existing benchmarks employ irrelevant noise texts to artificially extend the length of test cases diverging from the real-world scenarios of long-context applications. To bridge this gap we propose a novel long-context benchmark Loong aligning with realistic scenarios through extended multi-document question answering (QA). Unlike typical document QA in Loongs test cases each document is relevant to the final answer ignoring any document will lead to the failure of the answer. Furthermore Loong introduces four types of tasks with a range of context lengths Spotlight Locating Comparison Clustering and Chain of Reasoning to facilitate a more realistic and comprehensive evaluation of long-context understanding. Extensive experiments indicate that existing long-context language models still exhibit considerable potential for enhancement. Retrieval augmented generation (RAG) achieves poor performance demonstrating that Loong can reliably assess the models long-context modeling capabilities.
