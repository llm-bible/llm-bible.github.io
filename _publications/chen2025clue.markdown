---
layout: publication
title: 'Clueanchor: Clue-anchored Knowledge Reasoning Exploration And Optimization For Retrieval-augmented Generation'
authors: Hao Chen, Yukun Yan, Sen Mei, Wanxiang Che, Zhenghao Liu, Qi Shi, Xinze Li, Yuchun Fan, Pengcheng Huang, Qiushi Xiong, Zhiyuan Liu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: chen2025clue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24388"}
tags: ['Security', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning']
---
Retrieval-Augmented Generation (RAG) augments Large Language Models (LLMs) with external knowledge to improve factuality. However, existing RAG systems frequently underutilize the retrieved documents, failing to extract and integrate the key clues needed to support faithful and interpretable reasoning, especially in cases where relevant evidence is implicit, scattered, or obscured by noise. To address this issue, we propose ClueAnchor, a novel framework for enhancing RAG via clue-anchored reasoning exploration and optimization. ClueAnchor extracts key clues from retrieved content and generates multiple reasoning paths based on different knowledge configurations, optimizing the model by selecting the most effective one through reward-based preference optimization. Experiments show that ClueAnchor significantly outperforms prior RAG baselines in reasoning completeness and robustness. Further analysis confirms its strong resilience to noisy or partially relevant retrieved content, as well as its capability to identify supporting evidence even in the absence of explicit clue supervision during inference.
