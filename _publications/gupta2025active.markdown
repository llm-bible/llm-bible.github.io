---
layout: publication
title: 'AMPO: Active Multi-preference Optimization'
authors: Taneesh Gupta, Rahul Madhavan, Xuchao Zhang, Chetan Bansal, Saravan Rajmohan
conference: "Arxiv"
year: 2025
bibkey: gupta2025active
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18293"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Multi-preference optimization enriches language-model alignment beyond
pairwise preferences by contrasting entire sets of helpful and undesired
responses, thereby enabling richer training signals for large language models.
During self-play alignment, these models often produce numerous candidate
answers per query, rendering it computationally infeasible to include all
responses in the training objective. In this work, we propose \\(\textit\{Active
Multi-Preference Optimization\}\\) (AMPO), a novel approach that combines
on-policy generation, a multi-preference group-contrastive loss, and active
subset selection. Specifically, we score and embed large candidate pools of
responses and then select a small, yet informative, subset that covers reward
extremes and distinct semantic clusters for preference optimization. Our
contrastive training scheme is capable of identifying not only the best and
worst answers but also subtle, underexplored modes that are crucial for robust
alignment. Theoretically, we provide guarantees for expected reward
maximization using our active selection method, and empirically, AMPO achieves
state-of-the-art results on \\(\textit\{AlpacaEval\}\\) using Llama 8B.
