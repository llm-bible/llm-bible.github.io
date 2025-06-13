---
layout: publication
title: 'Anesbench: Multi-dimensional Evaluation Of LLM Reasoning In Anesthesiology'
authors: Xiang Feng, Wentao Jiang, Zengmao Wang, Yong Luo, Pingbo Xu, Baosheng Yu, Hua Jin, Bo Du, Jing Zhang
conference: "Arxiv"
year: 2025
bibkey: feng2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02404"}
  - {name: "Code", url: "https://github.com/MiliLab/AnesBench"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Distillation']
---
The application of large language models (LLMs) in the medical field has
gained significant attention, yet their reasoning capabilities in more
specialized domains like anesthesiology remain underexplored. In this paper, we
systematically evaluate the reasoning capabilities of LLMs in anesthesiology
and analyze key factors influencing their performance. To this end, we
introduce AnesBench, a cross-lingual benchmark designed to assess
anesthesiology-related reasoning across three levels: factual retrieval (System
1), hybrid reasoning (System 1.x), and complex decision-making (System 2).
Through extensive experiments, we first explore how model characteristics,
including model scale, Chain of Thought (CoT) length, and language
transferability, affect reasoning performance. Then, we further evaluate the
effectiveness of different training strategies, leveraging our curated
anesthesiology-related dataset, including continuous pre-training (CPT) and
supervised fine-tuning (SFT). Additionally, we also investigate how the
test-time reasoning techniques, such as Best-of-N sampling and beam search,
influence reasoning performance, and assess the impact of reasoning-enhanced
model distillation, specifically DeepSeek-R1. We will publicly release
AnesBench, along with our CPT and SFT training datasets and evaluation code at
https://github.com/MiliLab/AnesBench.
