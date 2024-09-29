---
layout: publication
title: Personalized Prompt Learning For Explainable Recommendation
authors: Li Lei, Zhang Yongfeng, Chen Li
conference: "Arxiv"
year: 2022
bibkey: li2022personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.07371"}
tags: ['Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Providing user45;understandable explanations to justify recommendations could help users better understand the recommended items increase the systems ease of use and gain users trust. A typical approach to realize it is natural language generation. However previous works mostly adopt recurrent neural networks to meet the ends leaving the potentially more effective pre45;trained Transformer models under45;explored. In fact user and item IDs as important identifiers in recommender systems are inherently in different semantic space as words that pre45;trained models were already trained on. Thus how to effectively fuse IDs into such models becomes a critical issue. Inspired by recent advancement in prompt learning we come up with two solutions find alternative words to represent IDs (called discrete prompt learning) and directly input ID vectors to a pre45;trained model (termed continuous prompt learning). In the latter case ID vectors are randomly initialized but the model is trained in advance on large corpora so they are actually in different learning stages. To bridge the gap we further propose two training strategies sequential tuning and recommendation as regularization. Extensive experiments show that our continuous prompt learning approach equipped with the training strategies consistently outperforms strong baselines on three datasets of explainable recommendation.
