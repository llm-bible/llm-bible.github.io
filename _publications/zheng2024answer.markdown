---
layout: publication
title: 'Kun: Answer Polishment For Chinese Self-alignment With Instruction Back-translation'
authors: Zheng Tianyu, Guo Shuyue, Qu Xingwei, Guo Jiawei, Du Xinrun, Jia Qi, Lin Chenghua, Huang Wenhao, Fu Jie, Zhang Ge
conference: "Arxiv"
year: 2024
bibkey: zheng2024answer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06477"}
  - {name: "Code", url: "https://github.com/Zheng0428/COIG-Kun"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques']
---
"In this paper, we introduce Kun, a novel approach for creating high-quality instruction-tuning datasets for large language models (LLMs) without relying on manual annotations. Adapting a self-training algorithm based on instruction back-translation and answer polishment, Kun leverages unlabelled data from diverse sources such as Wudao, Wanjuan, and SkyPile to generate a substantial dataset of over a million Chinese instructional data points. This approach significantly deviates from traditional methods by using a self-curation process to refine and select the most effective instruction-output pairs. Our experiments with the 6B-parameter Yi model across various benchmarks demonstrate Kun's robustness and scalability. Our method's core contributions lie in its algorithmic advancement, which enhances data retention and clarity, and its innovative data generation approach that substantially reduces the reliance on costly and time-consuming manual annotations. This methodology presents a scalable and efficient solution for improving the instruction-following capabilities of LLMs, with significant implications for their application across diverse fields. The code and dataset can be found at https://github.com/Zheng0428/COIG-Kun"
