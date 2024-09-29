---
layout: publication
title: Alignbench Benchmarking Chinese Alignment Of Large Language Models
authors: Liu Xiao, Lei Xuanyu, Wang Shengyuan, Huang Yue, Feng Zhuoer, Wen Bosi, Cheng Jiale, Ke Pei, Xu Yifan, Tam Weng Lam, Zhang Xiaohan, Sun Lichao, Gu Xiaotao, Wang Hongning, Zhang Jing, Huang Minlie, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2023
bibkey: liu2023benchmarking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18743"}
  - {name: "Code", url: "https://github.com/THUDM/AlignBench&#125;"}
tags: ['Has Code', 'Interpretability And Explainability', 'Merging', 'Pretraining Methods', 'Reinforcement Learning']
---
Alignment has become a critical step for instruction45;tuned Large Language Models (LLMs) to become helpful assistants. However the effective evaluation of alignment for emerging Chinese LLMs is still largely unexplored. To fill in this gap we introduce AlignBench a comprehensive multi45;dimensional benchmark for evaluating LLMs alignment in Chinese. We design a human45;in45;the45;loop data curation pipeline containing eight main categories 683 real45;scenario rooted queries and corresponding human verified references. To ensure the correctness of references each knowledge45;intensive query is accompanied with evidences collected from reliable web sources (including URLs and quotations) by our annotators. For automatic evaluation our benchmark employs a rule45;calibrated multi45;dimensional LLM45;as45;Judge~cite123;zheng2023judging125; approach with Chain45;of45;Thought to generate explanations and final ratings ensuring high reliability and interpretability. All evaluation code data and LLM generations are available at url123;https://github.com/THUDM/AlignBench&#125;. Since its release AlignBench has been adopted by top (Chinese) LLMs for evaluating their alignment capabilities in Chinese including ChatGLM Qwen DeepSeek Yi Baichuan and Abab.
