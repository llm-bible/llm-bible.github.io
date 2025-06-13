---
layout: publication
title: 'Vcapsbench: A Large-scale Fine-grained Benchmark For Video Caption Quality Evaluation'
authors: Shi-xue Zhang, Hongfa Wang, Duojun Huang, Xin Li, Xiaobin Zhu, Xu-cheng Yin
conference: "Arxiv"
year: 2025
bibkey: zhang2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23484'}
  - {name: "Code", url: 'https://github.com/GXYM/VCapsBench'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Multimodal Models', 'Reinforcement Learning']
---
Video captions play a crucial role in text-to-video generation tasks, as their quality directly influences the semantic coherence and visual fidelity of the generated videos. Although large vision-language models (VLMs) have demonstrated significant potential in caption generation, existing benchmarks inadequately address fine-grained evaluation, particularly in capturing spatial-temporal details critical for video generation. To address this gap, we introduce the Fine-grained Video Caption Evaluation Benchmark (VCapsBench), the first large-scale fine-grained benchmark comprising 5,677 (5K+) videos and 109,796 (100K+) question-answer pairs. These QA-pairs are systematically annotated across 21 fine-grained dimensions (e.g., camera movement, and shot type) that are empirically proven critical for text-to-video generation. We further introduce three metrics (Accuracy (AR), Inconsistency Rate (IR), Coverage Rate (CR)), and an automated evaluation pipeline leveraging large language model (LLM) to verify caption quality via contrastive QA-pairs analysis. By providing actionable insights for caption optimization, our benchmark can advance the development of robust text-to-video models. The dataset and codes are available at website: https://github.com/GXYM/VCapsBench.
