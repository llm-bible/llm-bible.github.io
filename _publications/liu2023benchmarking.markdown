---
layout: publication
title: 'Alignbench: Benchmarking Chinese Alignment Of Large Language Models'
authors: Liu Xiao, Lei Xuanyu, Wang Shengyuan, Huang Yue, Feng Zhuoer, Wen Bosi, Cheng Jiale, Ke Pei, Xu Yifan, Tam Weng Lam, Zhang Xiaohan, Sun Lichao, Gu Xiaotao, Wang Hongning, Zhang Jing, Huang Minlie, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2023
bibkey: liu2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18743"}
  - {name: "Code", url: "https://github.com/THUDM/AlignBench"}
tags: ['Has Code', 'Interpretability And Explainability', 'Merging', 'Reinforcement Learning', 'Uncategorized']
---
Alignment has become a critical step for instruction-tuned Large Language Models (LLMs) to become helpful assistants. However, the effective evaluation of alignment for emerging Chinese LLMs is still largely unexplored. To fill in this gap, we introduce AlignBench, a comprehensive multi-dimensional benchmark for evaluating LLMs' alignment in Chinese. We design a human-in-the-loop data curation pipeline, containing eight main categories, 683 real-scenario rooted queries and corresponding human verified references. To ensure the correctness of references, each knowledge-intensive query is accompanied with evidences collected from reliable web sources (including URLs and quotations) by our annotators. For automatic evaluation, our benchmark employs a rule-calibrated multi-dimensional LLM-as-Judge~\cite\{zheng2023judging\} approach with Chain-of-Thought to generate explanations and final ratings, ensuring high reliability and interpretability. All evaluation code, data, and LLM generations are available at \url\{https://github.com/THUDM/AlignBench\}. Since its release, AlignBench has been adopted by top (Chinese) LLMs for evaluating their alignment capabilities in Chinese, including ChatGLM, Qwen, DeepSeek, Yi, Baichuan, and Abab.
