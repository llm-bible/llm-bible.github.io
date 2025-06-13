---
layout: publication
title: 'Tcm-ladder: A Benchmark For Multimodal Question Answering On Traditional Chinese Medicine'
authors: Jiacheng Xie, Yang Yu, Ziyang Zhang, Shuai Zeng, Jiaxuan He, Ayush Vasireddy, Xiaoting Tang, Congyu Guo, Lening Zhao, Congcong Jing, Guanghui An, Dong Xu
conference: "Arxiv"
year: 2025
bibkey: xie2025tcm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24063"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Applications', 'Attention Mechanism']
---
Traditional Chinese Medicine (TCM), as an effective alternative medicine, has been receiving increasing attention. In recent years, the rapid development of large language models (LLMs) tailored for TCM has underscored the need for an objective and comprehensive evaluation framework to assess their performance on real-world tasks. However, existing evaluation datasets are limited in scope and primarily text-based, lacking a unified and standardized multimodal question-answering (QA) benchmark. To address this issue, we introduce TCM-Ladder, the first multimodal QA dataset specifically designed for evaluating large TCM language models. The dataset spans multiple core disciplines of TCM, including fundamental theory, diagnostics, herbal formulas, internal medicine, surgery, pharmacognosy, and pediatrics. In addition to textual content, TCM-Ladder incorporates various modalities such as images and videos. The datasets were constructed using a combination of automated and manual filtering processes and comprise 52,000+ questions in total. These questions include single-choice, multiple-choice, fill-in-the-blank, diagnostic dialogue, and visual comprehension tasks. We trained a reasoning model on TCM-Ladder and conducted comparative experiments against 9 state-of-the-art general domain and 5 leading TCM-specific LLMs to evaluate their performance on the datasets. Moreover, we propose Ladder-Score, an evaluation method specifically designed for TCM question answering that effectively assesses answer quality regarding terminology usage and semantic expression. To our knowledge, this is the first work to evaluate mainstream general domain and TCM-specific LLMs on a unified multimodal benchmark. The datasets and leaderboard are publicly available at https://tcmladder.com or https://54.211.107.106 and will be continuously updated.
