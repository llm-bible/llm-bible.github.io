---
layout: publication
title: 'NAMET: Robust Massive Model Editing Via Noise-aware Memory Optimization'
authors: Yanbo Dai, Zhenlan Ji, Zongjie Li, Shuai Wang
conference: "Arxiv"
year: 2025
bibkey: dai2025robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11876"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Model editing techniques are essential for efficiently updating knowledge in large language models (LLMs). However, the effectiveness of existing approaches degrades in massive editing scenarios, particularly when evaluated with practical metrics or in context-rich settings. We attribute these failures to embedding collisions among knowledge items, which undermine editing reliability at scale. To address this, we propose NAMET (Noise-aware Model Editing in Transformers), a simple yet effective method that introduces noise during memory extraction via a one-line modification to MEMIT. Extensive experiments across six LLMs and three datasets demonstrate that NAMET consistently outperforms existing methods when editing thousands of facts.
