---
layout: publication
title: 'Efficient Test-time Prompt Tuning For Vision-language Models'
authors: Zhu Yuhan, Zhang Guozhen, Xu Chen, Shen Haocheng, Chen Xiaoxin, Wu Gangshan, Wang Limin
conference: "Arxiv"
year: 2024
bibkey: zhu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05775"}
tags: ['Efficiency And Optimization', 'Interpretability And Explainability', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Vision-language models have showcased impressive zero-shot classification capabilities when equipped with suitable text prompts. Previous studies have shown the effectiveness of test-time prompt tuning; however these methods typically require per-image prompt adaptation during inference which incurs high computational budgets and limits scalability and practical deployment. To overcome this issue we introduce Self-TPT a novel framework leveraging Self-supervised learning for efficient Test-time Prompt Tuning. The key aspect of Self-TPT is that it turns to efficient predefined class adaptation via self-supervised learning thus avoiding computation-heavy per-image adaptation at inference. Self-TPT begins by co-training the self-supervised and the classification task using source data then applies the self-supervised task exclusively for test-time new class adaptation. Specifically we propose Contrastive Prompt Learning (CPT) as the key task for self-supervision. CPT is designed to minimize the intra-class distances while enhancing inter-class distinguishability via contrastive learning. Furthermore empirical evidence suggests that CPT could closely mimic back-propagated gradients of the classification task offering a plausible explanation for its effectiveness. Motivated by this finding we further introduce a gradient matching loss to explicitly enhance the gradient similarity. We evaluated Self-TPT across three challenging zero-shot benchmarks. The results consistently demonstrate that Self-TPT not only significantly reduces inference costs but also achieves state-of-the-art performance effectively balancing the efficiency-efficacy trade-off.
