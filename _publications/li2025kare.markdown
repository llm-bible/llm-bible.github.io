---
layout: publication
title: 'KARE-RAG: Knowledge-aware Refinement And Enhancement For RAG'
authors: Yongjian Li, Haocheng Chu, Yukun Yan, Zhenghao Liu, Shi Yu, Zheni Zeng, Ruobing Wang, Sen Song, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: li2025kare
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02503"}
tags: ['RAG', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) enables large language models (LLMs) to access broader knowledge sources, yet factual inconsistencies persist due to noise in retrieved documents-even with advanced retrieval methods. We demonstrate that enhancing generative models' capacity to process noisy content is equally critical for robust performance. In this paper, we present KARE-RAG (Knowledge-Aware Refinement and Enhancement for RAG), which improves knowledge utilization through three key innovations: (1) structured knowledge representations that facilitate error detection during training, (2) Dense Direct Preference Optimization (DDPO)-a refined training objective that prioritizes correction of critical errors, and (3) a contrastive data generation pipeline that maintains semantic consistency while rectifying factual inaccuracies. Experiments show our method significantly enhances standard RAG pipelines across model scales, improving both in-domain and out-of-domain task performance without compromising general capabilities. Notably, these gains are achieved with modest training data, suggesting data-efficient optimization is possible through targeted learning strategies. Our findings establish a new direction for RAG improvement: by improving how models learn to process retrieved content, we can enhance performance across diverse inference paradigms. All data and code will be publicly available on Github.
