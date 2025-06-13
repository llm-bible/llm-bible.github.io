---
layout: publication
title: 'Bridging The Gap: Self-optimized Fine-tuning For Llm-based Recommender Systems'
authors: Heng Tang, Feng Liu, Xinbo Chen, Jiawei Chen, Bohao Wang, Changwang Zhang, Jun Wang, Yuegang Sun, Bingde Hu, Can Wang
conference: "Arxiv"
year: 2025
bibkey: tang2025bridging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20771'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/Self-Optimized-Fine-Tuning-264E'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'RecSys', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Recent years have witnessed extensive exploration of Large Language Models (LLMs) on the field of Recommender Systems (RS). There are currently two commonly used strategies to enable LLMs to have recommendation capabilities: 1) The "Guidance-Only" strategy uses in-context learning to exploit and amplify the inherent semantic understanding and item recommendation capabilities of LLMs; 2) The "Tuning-Only" strategy uses supervised fine-tuning (SFT) to fine-tune LLMs with the aim of fitting them to real recommendation data. However, neither of these strategies can effectively bridge the gap between the knowledge space of LLMs and recommendation, and their performance do not meet our expectations.
  To better enable LLMs to learn recommendation knowledge, we combine the advantages of the above two strategies and proposed a novel "Guidance+Tuning" method called Self-Optimized Fine-Tuning (SOFT), which adopts the idea of curriculum learning. It first employs self-distillation to construct an auxiliary easy-to-learn but meaningful dataset from a fine-tuned LLM. Then it further utilizes a self-adaptive curriculum scheduler to enable LLMs to gradually learn from simpler data (self-distilled data) to more challenging data (real RS data). Extensive experiments demonstrate that SOFT significantly enhances the recommendation accuracy (37.59% on average) of LLM-based methods. The code is available via https://anonymous.4open.science/r/Self-Optimized-Fine-Tuning-264E
