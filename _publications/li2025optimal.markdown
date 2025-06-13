---
layout: publication
title: 'Optimal Transport-based Token Weighting Scheme For Enhanced Preference Optimization'
authors: Meng Li, Guangda Huzhang, Haibo Zhang, Xiting Wang, Anxiang Zeng
conference: "Arxiv"
year: 2025
bibkey: li2025optimal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.18720'}
  - {name: "Code", url: 'https://github.com/Mimasss2/OTPO.'}
tags: ['Has Code', 'Interpretability and Explainability', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning']
---
Direct Preference Optimization (DPO) has emerged as a promising framework for aligning Large Language Models (LLMs) with human preferences by directly optimizing the log-likelihood difference between chosen and rejected responses. However, existing methods assign equal importance to all tokens in the response, while humans focus on more meaningful parts. This leads to suboptimal preference optimization, as irrelevant or noisy tokens disproportionately influence DPO loss. To address this limitation, we propose \textbf\{O\}ptimal \textbf\{T\}ransport-based token weighting scheme for enhancing direct \textbf\{P\}reference \textbf\{O\}ptimization (OTPO). By emphasizing semantically meaningful token pairs and de-emphasizing less relevant ones, our method introduces a context-aware token weighting scheme that yields a more contrastive reward difference estimate. This adaptive weighting enhances reward stability, improves interpretability, and ensures that preference optimization focuses on meaningful differences between responses. Extensive experiments have validated OTPO's effectiveness in improving instruction-following ability across various settings\footnote\{Code is available at https://github.com/Mimasss2/OTPO.\}.
