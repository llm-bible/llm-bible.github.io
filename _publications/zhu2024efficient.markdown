---
layout: publication
title: Efficient Test45;time Prompt Tuning For Vision45;language Models
authors: Zhu Yuhan, Zhang Guozhen, Xu Chen, Shen Haocheng, Chen Xiaoxin, Wu Gangshan, Wang Limin
conference: "Arxiv"
year: 2024
bibkey: zhu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05775"}
tags: ['Efficiency And Optimization', 'Interpretability And Explainability', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Vision45;language models have showcased impressive zero45;shot classification capabilities when equipped with suitable text prompts. Previous studies have shown the effectiveness of test45;time prompt tuning; however these methods typically require per45;image prompt adaptation during inference which incurs high computational budgets and limits scalability and practical deployment. To overcome this issue we introduce Self45;TPT a novel framework leveraging Self45;supervised learning for efficient Test45;time Prompt Tuning. The key aspect of Self45;TPT is that it turns to efficient predefined class adaptation via self45;supervised learning thus avoiding computation45;heavy per45;image adaptation at inference. Self45;TPT begins by co45;training the self45;supervised and the classification task using source data then applies the self45;supervised task exclusively for test45;time new class adaptation. Specifically we propose Contrastive Prompt Learning (CPT) as the key task for self45;supervision. CPT is designed to minimize the intra45;class distances while enhancing inter45;class distinguishability via contrastive learning. Furthermore empirical evidence suggests that CPT could closely mimic back45;propagated gradients of the classification task offering a plausible explanation for its effectiveness. Motivated by this finding we further introduce a gradient matching loss to explicitly enhance the gradient similarity. We evaluated Self45;TPT across three challenging zero45;shot benchmarks. The results consistently demonstrate that Self45;TPT not only significantly reduces inference costs but also achieves state45;of45;the45;art performance effectively balancing the efficiency45;efficacy trade45;off.
