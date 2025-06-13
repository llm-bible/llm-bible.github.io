---
layout: publication
title: 'JOLT-SQL: Joint Loss Tuning Of Text-to-sql With Confusion-aware Noisy Schema Sampling'
authors: Jinwang Song, Hongying Zan, Kunli Zhang, Lingling Mu, Yingjie Han, Haobo Hua, Min Peng
conference: "Arxiv"
year: 2025
bibkey: song2025jolt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14305"}
tags: ['Security', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Text-to-SQL, which maps natural language to SQL queries, has benefited greatly from recent advances in Large Language Models (LLMs). While LLMs offer various paradigms for this task, including prompting and supervised fine-tuning (SFT), SFT approaches still face challenges such as complex multi-stage pipelines and poor robustness to noisy schema information. To address these limitations, we present JOLT-SQL, a streamlined single-stage SFT framework that jointly optimizes schema linking and SQL generation via a unified loss. JOLT-SQL employs discriminative schema linking, enhanced by local bidirectional attention, alongside a confusion-aware noisy schema sampling strategy with selective attention to improve robustness under noisy schema conditions. Experiments on the Spider and BIRD benchmarks demonstrate that JOLT-SQL achieves state-of-the-art execution accuracy among comparable-size open-source models, while significantly improving both training and inference efficiency.
