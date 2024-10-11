---
layout: publication
title: 'Dual-space Hierarchical Learning For Goal-guided Conversational Recommendation'
authors: Chen Can, Liu Hao, Liu Zeming, Liu Xue, Dou Dejing
conference: "Arxiv"
year: 2023
bibkey: chen2023dual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00272"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Uncategorized']
---
Proactively and naturally guiding the dialog from the non-recommendation context (e.g., Chit-chat) to the recommendation scenario (e.g., Music) is crucial for the Conversational Recommender System (CRS). Prior studies mainly focus on planning the next dialog goal~(e.g., chat on a movie star) conditioned on the previous dialog. However, we find the dialog goals can be simultaneously observed at different levels, which can be utilized to improve CRS. In this paper, we propose Dual-space Hierarchical Learning (DHL) to leverage multi-level goal sequences and their hierarchical relationships for conversational recommendation. Specifically, we exploit multi-level goal sequences from both the representation space and the optimization space. In the representation space, we propose the hierarchical representation learning where a cross attention module derives mutually enhanced multi-level goal representations. In the optimization space, we devise the hierarchical weight learning to reweight lower-level goal sequences, and introduce bi-level optimization for stable update. Additionally, we propose a soft labeling strategy to guide optimization gradually. Experiments on two real-world datasets verify the effectiveness of our approach. Code and data are available here.
